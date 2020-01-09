id: "patch"
name: "Apply OS patches"
cron: "0 0 0 15 * *"
---

# OS Patch Procedure

Resolve this ticket by executing the following steps:

- [ ] Pull the latest scripts from the Ops repository
- [ ] Execute scripts to deploy changes to `STAGING`
- [ ] Inspect output
    - [ ] Errors? Investigate and resolve
- [ ] Execute scripts to deploy changes to `PROD`
- [ ] Attach log output to this ticket