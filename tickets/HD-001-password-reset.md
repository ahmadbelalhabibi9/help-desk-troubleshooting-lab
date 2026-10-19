
# HD-001: User Cannot Log In — Password Reset

## Ticket Information
- **Ticket ID:** HD-001
- **Category:** Account and Authentication
- **Priority:** Medium
- **User in simulator:** Maria Garcia (`mgarcia`)
- **Environment:** ServiceDesk Simulator
- **Status:** Resolved in the simulator

## Reported Issue
The user reported that her password was not working and she could not log in to her computer. Her identity needed to be verified before resetting the password.

## Troubleshooting and Resolution Steps
1. Opened Tools → Directory in the ServiceDesk Simulator.
2. Searched for `mgarcia` and selected Maria Garcia's account.
3. Opened the Authentication tab and selected Send Verification Code.
4. Requested the verification code through Company Chat and entered it to verify the user's identity.
5. After successful verification, selected Reset Password to generate a temporary password.
6. Sent the temporary password through Company Chat, following the simulator's required procedure.
7. Instructed the user to change the temporary password at first login.

## Resolution
The password-reset workflow was completed according to the simulator's required procedure. The user's identity was verified before the reset, and the temporary password was delivered through the designated communication channel.

## Security Considerations
- Verify the user's identity before resetting a password.
- Never bypass identity verification.
- Follow the organization's approved procedure for delivering temporary credentials.
- Require a password change at first login when required by policy.
- Never include actual passwords or verification codes in ticket documentation.

## Skills Demonstrated
- User account lookup
- Identity verification
- Password-reset procedures
- Secure credential handling
- User communication
- IT ticket documentation

## Lessons Learned
A password-reset request is not just a technical issue. A technician must verify the user's identity and follow secure procedures before changing an account password.

## Practice Environment
This scenario was completed in the ServiceDesk Simulator. It demonstrates practice with a simulated service desk workflow, not a password reset performed on a real company account.
