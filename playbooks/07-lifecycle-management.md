# 7 Lifecycle management

## Principle

**(Secure by Design)**

Security responsibilities extend beyond initial development. Components must be maintained, updated and eventually retired in a controlled manner.

## Objective

Ensure security is maintained throughout the product’s full lifecycle, from requirements and design through deployment, maintenance, and end-of-life, so security does not degrade over time.

## Checklist

### Define support commitments and lifecycle states

- Publish (internally or externally) lifecycle states: Active, Maintenance, End-of-Sale, End-of-Support, End-of-Life.
- Define minimum support windows and internal guidelines for vulnerability triage and patch release timelines (e.g., critical vulnerabilities triaged in 48h; fixes released within X days where feasible).

### Make the product updateable and recoverable

- Implement a secure and transactional update mechanism (authenticated updates; integrity protected; rollback/recovery plan).
- Ensure safe failure modes (don’t brick devices; provide fallback/rollback where practical).
- During maintenance or recovery modes, restrict functionality and privileges to the minimum necessary to support update and recovery operations.

### Operate vulnerability and patch management

- Track vulnerabilities from: third-party components, internal findings, customer reports.
- Maintain an SBOM (at least per release) and a dependency update cadence.
- Triage, prioritise, and document risk decisions (fix, mitigate, accept with expiry).

### Monitor, log, and handle incidents

- Enable security-relevant logging (auth events, admin actions, update events, boundary-crossing requests).
- Define minimal incident response steps: detection, triage, containment, remediation, customer comms (as applicable)

### Learn from deployed products

- Collect evidence on how products are deployed and used, such as customer feedback, support cases, vulnerability reports, incident findings and privacy-preserving telemetry where appropriate.
- Review findings, including the results of root-cause analyses where applicable, and update the product context, risk assessment, threat model and secure defaults as necessary.

### Plan secure decommissioning and disposal

- Provide data erasure mechanisms and guidance (factory reset, key revocation, account de-provisioning).
- Revoke credentials/keys when devices/users/services are deactivated.
- Ensure end-of-life guidance includes what security updates cease and what customers must do.

## Minimum evidence

- Lifecycle policy: lifecycle states + support window + patch SLAs (1 page).
- Update/release process: secure update approach + rollback/recovery notes.
- Vulnerability management log: intake, triage, prioritisation, disposition, owner, dates (ticket board or spreadsheet).
- SBOM: SBOM generated in a machine-readable, widely adopted standard format (e.g. SPDX or CycloneDX) and stored with the release.
- Monitoring and Logging: Security logging baseline + sample logs showing admin/auth/update events.
- Field feedback record: summary of relevant operational evidence reviewed, deviations from deployment assumptions identified and resulting actions
- Decommissioning checklist: data wipe/reset, credential/key revocation, and customer guidance.

## Release gate

- [ ] Support status and lifecycle state for this release are clear (Active/Maintenance/etc.)
- [ ] Secure update path validated (integrity/authentication checks; rollback/recovery documented)
- [ ] Vulnerability triage completed for known issues (including third-party deps); decisions recorded (fix/mitigate/accept with expiry)
- [ ] SBOM generated (or dependency inventory updated) and stored for the release
- [ ] Security logging verified for critical events (auth, admin actions, updates)
- [ ] Decommissioning actions defined for components introduced/changed (reset, wipe, key revocation)
- [ ] Any accepted residual security risk has an owner and review/expiry date
