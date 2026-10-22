README — Reservation Hall
An Arabic prototype demonstrating a process for requesting training and meeting rooms. Employees can view room availability, select an available date, enter meeting details, and see the request in a simulated approval queue.
Important: This is a local demo with fictional availability data. It is not connected to the university’s booking system and does not create real reservations.

Project Files
- Reservation Hall.html — Interactive booking prototype.
- capstone-project-board-draft.md — Capstone project board with eight sections.
- capstone-delivery-pack.md — Experiment records, a five-minute presentation script, a peer feedback form, and an evidence checklist.
- paired-scenario-simulation.md — Three fictional scenarios compared with and without an assistant.
Opening the Prototype
1. Download Reservation Hall.html or extract it from the ZIP package.
2. Open it in a modern browser such as Microsoft Edge or Google Chrome.
3. Select a room and a date marked “Available,” then complete the request form.
No installation or internet connection is required. Demo requests are stored in the current browser only, so they will not appear automatically on other devices or browsers.
Rooms Included
- University Council Hall: More than 30 people; maximum capacity is not specified. Approval from an authorized person is required.
- Two university theatres.
- Three circular meeting rooms.
The capacities of the theatres and circular rooms have not been provided. The prototype reminds users to confirm capacity with the room coordinator.
What the Prototype Demonstrates
- A fictional calendar for each room covering the next two months, with “Available,” “Booked,” and “Maintenance” statuses.
- Booked and maintenance dates cannot be selected.
- Request fields for date, start and end times, attendee count, and meeting purpose.
- Submission is blocked for the University Council Hall if no approval file is selected.
- A simulated request queue with pending, approved, and returned-for-editing statuses.
- The return reason “Room already booked,” with a flow for choosing another room.
Limitations
- Calendar statuses are generated for demonstration and do not reflect the university’s actual schedule.
- The prototype has no login, permissions, or shared database.
- The approval-file field checks that a file was selected and displays its name. It does not upload or save the file contents.
- Requests and status changes are stored only in the current browser.
- The approval queue is simulated. It does not notify or send requests to a room coordinator.
- Code checks and scenario simulations are not field user tests and do not measure time savings.
Scenario Comparison
paired-scenario-simulation.md describes a typical request, an ambiguous request, and an edge case involving a booking conflict and required approval. The scenarios use fictional data and are desk simulations; they do not represent employee performance or include measured times or satisfaction ratings.
Initial Baseline
According to the project owner, an employee spends two hours of active work per booking request. The booking result takes one full workday to arrive, and there are approximately 23 requests per month. This gives a calculated baseline of 46 staff work hours per month (2 hours × 23 requests).
These figures are based on the project owner’s description and should be verified against actual records. The 46-hour monthly figure is a calculation, not an independently measured result.
Requirements Before Internal Use
1. Obtain university approval for the hosting location and employee sign-in method.
2. Connect availability to an approved, up-to-date room schedule and recheck it before submission.
3. Add a shared database that prevents booking conflicts and stores requests.
4. Confirm room capacities, operating hours, and booking and cancellation rules.
5. Approve how University Council Hall approval documents will be uploaded and stored under university policy.
6. Conduct employee and approver tests; record request duration, staff effort, errors, and peer feedback.
