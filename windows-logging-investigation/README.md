This is a fundamental lab that explores windows event logs to detect security-related actions like logons, user creation, privilege usage.

Tools used:
- Windows 11 VM
- Event viewer

Event IDs observed
- 4624 (successful logon) ![successful logon](./Screenshot-event-logon-successful)
    -This event shows a successful log in attempt

- 4625 (failed logon) ![Failed logon](./Screenshot-event-logon-failed)
    -This event shows a failed log in attempt

- 4720 (user account creation) ![net user cmd](./Screenshot-event-user-creation) ![user created security logs](./Screenshot-event-security-log-for-account-creation)
    -This shows the "net user" command used to create a single local user account and adding it as an admin. The event logs show who created the account and when.

Summary

-Event viewer logs all local security-related actions
-Event Ids help correlate system events with attacker or admin behavior
-Amazing starting point for blue team investigations.
