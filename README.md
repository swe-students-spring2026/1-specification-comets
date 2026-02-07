# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## Team members

- Kara Jin - [Kara's Github](https://github.com/cynikjinchen)
- Ethan Tan - [Ethan's Github](https://github.com/ethantyr)
- Sheldon Xie - [Sheldon's Github](https://github.com/FilthyS)

## Stakeholders

### Robert (Patient):

Goals/needs:

- I want to quickly find freelance nurses who can travel to my location and provide regular, consistent care at a fixed time.
- I want to be able to find nurses quickly if I need urgent care that doesn’t warrant a hospital visit yet.
- I want to choose a nurse who suits my needs, price range, and preferences.
- I want to be able to upload any relevant medical history and share any requests through the app, which should help link me to a suitable nurse who can help with my medical needs.
- I want to link my payment details so that my payments, tips, and other transactions are automatically done for me through the app.

Problems/Frustrations:

- I find it difficult to find freelance nurses through sketchy websites, word of mouth, or online forums. These tend to be unreliable and sometimes even a scam.
- It is hard to individually vet the validity of a nursing license or evaluate a freelance nurse’s ability without reviews or any other evaluation metric.
- If I cannot vet a nurse’s legitimacy, I may become paranoid about sharing any personal, financial, or medical information, especially if I have yet to meet the nurse.
- It might be difficult for nurses to provide the relevant healthcare and medicine unless they have my medical background logged somewhere. Thus, it would be incredibly helpful for both parties if they could view my most recently logged medical information prior to a sudden appointment.

### Linda (Family Caregiver):

Goals/needs:

- I want to find a reliable nurse who can visit my parent at a fixed, recurring time so that their routine stays stable and I don’t have to reorganize my work schedule constantly.
- I want to be able to monitor visits remotely and receive notifications when the nurse arrives, leaves, or reports something important so that I feel reassured even when I’m not physically there.
- I want to clearly see each nurse’s license verification, experience with elderly patients, and reviews so that I can confidently choose someone qualified.
- I want transparent pricing and a clear cancellation policy before booking so that I can budget long-term care costs without unexpected fees.

Problems/Frustrations:

- It took me weeks to find a nurse through word of mouth in NYC, and most online listings were outdated or unresponsive.
- I often feel anxious about whether a nurse will show up on time or cancel last minute, especially when I cannot leave work to step in.
- Coordinating schedules, payments, and communication through calls and texts feels disorganized and stressful.
- I worry about scams or unverified caregivers when using random websites or forums, especially when it involves my parent’s safety and medical needs.

### Megan (Administrator):

Goals/needs:

- I want to verify nurse licenses and credentials before they are approved on the platform so that patients can trust that every listed nurse is legitimate and qualified.
- I want to monitor user feedback, complaints, and ratings so that I can quickly identify unsafe behavior or recurring service issues.
- I want to have access to activity logs, such as bookings, cancellations, disputes, and payments, so that I can investigate conflicts fairly and transparently.
- I want tools to suspend or remove nurses or patients who violate platform policies so that the platform maintains safety and professional standards.

Problems/Frustrations:

- If verification is done manually through emails and spreadsheets, it becomes slow and error-prone, especially as the platform grows.
- It is difficult to detect fake licenses or fraudulent users without a centralized verification system.
- Negative reviews or disputes can escalate quickly if there is no structured process to investigate and respond.
- Without clear data dashboards, it is hard to identify patterns such as repeated cancellations, suspicious activity, or low-rated providers.

### Dr. Martin (NYC Health Commissioner):

Goals/needs:

- I want platforms that connect nurses with elderly residents to comply with state licensing and healthcare regulations so that patient safety is not compromised.
- I want access to anonymized usage statistics from the platform so that the city can identify areas with high demand and limited nurse availability.
- I want mechanisms in place to prevent fraud, impersonation, or unsafe medical practices so that vulnerable residents are protected.
- I want clear accountability structures, like audit logs and complaint tracking, so that regulatory oversight is possible if needed.

Problems/Frustrations:

- Many digital health platforms operate in gray areas without clear regulation, which creates legal and ethical risks.
- Much of freelance caregiving happens privately without centralized oversight, making it difficult to monitor quality and safety standards.
- Unverified providers may endanger elderly residents if licensing and credential checks are not enforced properly.
- When complaints arise, platforms often lack structured documentation or traceability, making investigations hard.

## Product Vision Statement

To create a trusted mobile platform that connects verified freelance nurses with elderly patients in need of reliable and flexible care.

## User Requirements

### Elderly Patient

- As an elderly patient, I want to enter my care needs, such as medication help and mobility support, so I can be matched with a nurse who fits my situation.
- As an elderly patient, I want to search for nurses by location and availability, so I can find someone nearby who can come to my home when I need them or in case of any emergencies.
- As an elderly patient, I want to view a nurse’s profile, including but not limited to his/her license status, experience, languages, and services, so I can decide if I trust and prefer them.
- As an elderly patient, I want to book a visit for a specific date and time with only some taps on the app, so I can schedule care without phone calls or email.
- As an elderly patient, I want to save my preferred nurses as favorites, so I can quickly rebook someone I already know and trust.
- As an elderly patient, I want to add accessibility preferences like hearing support or wheelchair-friendly visits, so I can receive care that fits my physical needs.
- As an elderly patient, I want to choose in-home services like wound dressing or vital checks, so I can request the exact type of care I need without confusion.
- As an elderly patient, I want to be able to write reviews and/or ratings for nurses, so I can provide feedback on my experience.
- As an elderly patient, I want to be able to choose a freelance nurse at a suitable price, so I can stay within my budget.

### Family Caregiver

- As a family caregiver, I want to book recurring visits, so I can worry less and have my family members receive stable care on a routine basis.
- As a family caregiver, I want to see transparent pricing and a cancellation policy before booking, so I can be prepared for any unexpected charges.
- As a family caregiver, I want to receive notifications when a nurse accepts the order, is en route, arrives, or is running late, so I can stay informed about any situation.
- As a family caregiver, I want to manage multiple patient profiles in one account, so I can coordinate care for more than one family member easily.
- As a family caregiver, I want to upload medical notes and care instructions for the nurse to review, so I can ensure the nurse follows the correct routine.
- As a family caregiver, I want to share visit details with other approved family members, so everyone stays aligned on schedules and responsibilities.

### Freelance Nurse

- As a freelance nurse, I want to submit my license and identity for verification, so I can be trusted with proof of qualifications, and I can get straight to work.
- As a freelance nurse, I want to set my availability and service area, so I can only receive requests when and where I am free.
- As a freelance nurse, I want to message the patient along with caregivers of any emergency on the road, absence, or any missing information, so I can contact the clients seamlessly and reduce misunderstandings.
- As a freelance nurse, I want to accept or decline requests within a time limit, so patients get quick confirmations and I can control my workload.
- As a freelance nurse, I want to view a clear summary of care needs before accepting a job, so I can confirm I’m qualified and prepared for the visit.
- As a freelance nurse, I want to log visit completion notes and tasks performed, so I can document care and support continuity for future visits.

### Platform Administrator

- As a platform administrator, I want to flag suspicious accounts or inconsistent credentials, so I can protect patients and maintain trust in the marketplace.
- As a platform administrator, I want to easily view user statistics, overall nurse availability, and any other high-level data to monitor app usage and performance.

## Activity Diagrams

See instructions. Delete this line and place images of your UML Activity diagrams here.

## Clickable Prototype

See instructions. Delete this line and place a publicly-accessible link to your clickable prototype here.
