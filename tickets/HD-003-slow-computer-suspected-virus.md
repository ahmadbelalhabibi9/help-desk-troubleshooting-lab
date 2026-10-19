# HD-003: Slow Computer — Suspected Virus

## Ticket Information
- **Ticket ID:** HD-003
- **Reported by:** Priya Sharma
- **Department:** Engineering
- **Location:** Floor 3
- **Category:** Performance Troubleshooting / Endpoint Security
- **Environment:** ServiceDesk Simulator
- **Status:** Resolved in the simulator

## Reported Issue
Priya Sharma reported that her computer had become extremely slow. Applications took several minutes to open, and the system seemed to be working continuously. She suspected a virus because the computer had worked normally the previous day.

## Business Impact
The computer's poor performance significantly slowed the user's daily work. Tasks that should have taken a short time were taking several minutes to complete.

## Initial Troubleshooting
The user had already:
- Restarted the computer, but the slowdown returned after about a minute.
- Closed all open applications.

These actions did not permanently resolve the problem.

## Troubleshooting and Resolution Steps
1. Opened **Tools → Remote Desktop** in the ServiceDesk Simulator and selected **Connect** next to the user's PC.
2. Opened Task Manager from the Start menu.
3. Checked the Startup tab. The listed publishers were known, and no suspicious startup entries were identified.
4. Reviewed the Processes tab and sorted the columns to investigate resource usage.
5. Observed that CPU usage was nearly idle, suggesting the processor was not the cause of the slowdown.
6. Identified the Cloud Drive synchronization engine as heavily using disk and network resources without making progress.
7. Opened Cloud Drive in File Explorer and selected **Sync** to force synchronization to restart.
8. Contacted the user through Company Chat to confirm that the computer was running at normal speed again.

## Resolution
The simulator identified a stuck Cloud Drive synchronization process rather than a confirmed malware infection. Forcing synchronization resolved the performance issue, and the user confirmed that the computer was back to normal speed.

## Skills Demonstrated
- Remote desktop troubleshooting
- Windows Task Manager
- Startup application review
- CPU, disk, and network resource analysis
- Cloud synchronization troubleshooting
- Evidence-based diagnosis
- User communication and confirmation

## Lessons Learned
A slow computer does not always have a virus. Checking resource usage and startup applications helps identify the actual cause before taking unnecessary security actions. In this scenario, the evidence pointed to a stuck cloud synchronization process rather than an infection.

Technicians should investigate the symptoms systematically instead of assuming the user's initial diagnosis is correct.

## Practice Environment
This scenario was completed in the ServiceDesk Simulator. The troubleshooting workflow and outcome represent simulated IT support practice, not an incident handled at an actual workplace.
