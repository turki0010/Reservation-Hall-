EADME — Reservation Hall
An Arabic prototype demonstrating the request process for booking training and meeting rooms. Employees can view room availability, choose an available date, enter meeting details, and see the request in a simulated approval queue.
Note: This is a local demo with fictional data. It is not connected to the university’s room schedule or booking system and does not create real reservations.

Project Files
- Reservation Hall.html — Interactive booking prototype.
- capstone-project-board-draft.md — Capstone project board with eight sections.
- capstone-delivery-pack.md — Five-minute presentation script, experiment logs, peer feedback form, and evidence checklist.
- paired-scenario-simulation.md — Comparison of typical, ambiguous, and edge-case scenarios with and without an assistant.
Opening the Prototype
1. Download Reservation Hall.html or extract it from the ZIP file.
2. Open it in a modern browser such as Microsoft Edge or Google Chrome.
3. Choose a room and a date marked “Available,” then complete the request form.
The prototype does not require installation or an internet connection. Demo requests are stored in the browser’s local storage, so they will not automatically appear on another device or in another browser.
Rooms Included
- University Council Hall: capacity is more than 30 people; the maximum capacity is not specified. Approval from an authorized person must be attached.
- Two university theatres.
- Three circular meeting rooms.
The capacities of the theatres and circular rooms have not been entered. The prototype displays a reminder to confirm capacity with the room coordinator.
What the Prototype Demonstrates
- A fictional availability calendar for each room covering the next two months, with “Available,” “Booked,” and “Maintenance” statuses.
- Booked and maintenance dates cannot be selected.
- Fields for date, start and end times, attendee count, and meeting purpose.
- Submission blocking for the University Council Hall when no approval file has been selected.
- A simulated request queue with pending, approved, and returned-for-editing statuses.
- The return reason “Room already booked,” with a flow for selecting another room.
Limitations
- Calendar statuses are generated for demonstration and do not reflect the university’s actual schedule.
- There is no login, permission management, or shared database.
- The approval-file field only checks that a file was selected and displays its name. It does not upload or save the file contents.
- Requests and status changes are stored only in the current browser.
- The approval queue is simulated; it does not send notifications or requests to a room coordinator.
- Code checks and scenario simulations are not field user tests and do not measure time savings.
Scenario Comparison
paired-scenario-simulation.md contains three fictional scenarios: a typical request, an ambiguous request, and an edge case involving a conflict and required approval. The results are desk simulations. They do not represent employee performance and include no time or satisfaction measurements.
Initial Baseline
According to the project owner, the employee spends two hours of active work per booking request. The result takes one full workday to arrive, and there are approximately 23 requests per month. This gives a calculated baseline of 46 staff work hours per month (2 hours × 23 requests). The figures are based on the project owner’s description and should be verified against actual records; the 46-hour monthly figure is a calculation, not an independently measured result.
Requirements Before Internal Use
1. Obtain university approval for the hosting location and employee sign-in method.
2. Connect room availability to an approved, up-to-date schedule and recheck it before submission.
3. Add a shared database that prevents conflicts and stores request records.
4. Confirm room capacities, operating hours, and booking and cancellation rules.
5. Approve a process for uploading and storing University Council Hall approvals under university policy.
6. Test the prototype with employees and an approver, recording request duration, staff effort, errors, and peer feedback.
