UML 2 - Renting School Facility

Activity Diagram and Sequence Diagram

Goal
You will describe how a school facility rental system works. You will make two UML diagrams. The first diagram
shows the steps in the process (Activity Diagram). The second diagram shows how the software parts
communicate (Sequence Diagram).
Scenario

A school wants to earn money by renting its facilities after school hours. People and companies can use a
website to rent a gym, classroom, parking lot, or sports field. The renter chooses a facility and a date. The
school checks the request. If the request is approved and payment succeeds, the renter receives a
confirmation.

People and software parts
Name ---- Meaning
Renter A person or company that wants to rent a facility.
Website The system used to submit and track a rental request.
School Staff Checks the request and approves or rejects it.
Payment Service Processes the payment.
Email Service Sends confirmation or rejection messages.

Words used in this assignment
Word ---- Simple meaning
Request Information sent by the renter.
Available The facility is free on the requested date and time.
Approve School Staff accepts the request.
Reject School Staff does not accept the request.
Guard A condition written in brackets, such as [available].
Message Information sent from one participant to another.

System rules
• The renter selects a facility, date, time, and event type.
• The website checks if the facility is available.
• If the facility is not available, the website tells the renter. The renter may choose a different date or stop.
• If the facility is available, the renter enters contact information and submits the request.
• School Staff reviews the request. Staff may approve or reject it.
• If staff rejects the request, the website records the rejection and sends an email to the renter.
• If staff approves the request, the Payment Service charges the renter.
• If payment fails, the website records the failure and sends an email to the renter.
• If payment succeeds, the website saves the booking and sends a confirmation email.

Important Model only the process from the renter submitting a request through approval, rejection, or
payment result. Do not model how the payment company works inside.


Task 1: Activity diagram
Create one activity diagram for the complete rental process. Use swimlanes. A swimlane shows who performs
each action.
Your diagram must show:
• Renter, Website, and School Staff as swimlanes. You may add Payment Service and Email Service if
helpful.
• A start point and at least three end points: rejected, payment failed, and booking confirmed.
• A decision for [available] and [not available].
• A decision for [approved] and [rejected].
• A decision for [payment succeeds] and [payment fails].
• The main actions in the correct order.
• Short action names, such as “Choose facility” or “Check availability”.


Task 2: Sequence diagram
Create one sequence diagram for a normal request. Start when the renter submits an available facility request.
End when the booking is confirmed.
Your diagram must show:
• These participants: Renter, Website, School Staff, Payment Service, and Email Service.
• Messages for submitting the request, checking availability, reviewing the request, approving it,
processing payment, saving the booking, and sending co
