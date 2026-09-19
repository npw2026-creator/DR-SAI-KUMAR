Stage 1 — Final Master Event Specification
Shri Vishnu College of Pharmacy (Autonomous)
World Pharmacist Day & National Pharmacy Week 2026 — Institutional Event Portal

I have now converted the supplied AP State-level event guideline document into an implementation-oriented specification. I am deliberately separating three things:

AP/State guideline — what is stated in your supplied document.
SVCP institutional configuration — what your college can decide/change through the Admin/Nodal Officer.
Platform behaviour — how the application should implement the above.

This distinction should become the foundation of the application.

A. GLOBAL PLATFORM SPECIFICATION
1. Institutional identity
Fixed initial configuration

Institution:

Shri Vishnu College of Pharmacy (Autonomous)

Programme

World Pharmacist Day 2026 & National Pharmacy Week 2026

Theme

स्वस्थ भारत: Combating Antimicrobial Resistance

The supplied AP document presents the theme in this form and identifies the institutional event period as 25 September 2026 to 5 October 2026.

Important architectural decision

The institution name, logo, contact information, website, etc. should be stored in Institution Settings, not hard-coded throughout the application.

B. GLOBAL PARTICIPATION POLICY

This should be displayed prominently on the homepage and registration pages.

Institutional policy

All institutional-level competitions will be conducted offline at Shri Vishnu College of Pharmacy (Autonomous).

Online facilities are provided for registration and for submission of abstracts, documents, videos or other materials wherever required.

Students may participate in multiple institutional-level events because the competitions are scheduled on different dates.

However, State-Level events will be conducted on a common day. Therefore, if a student is selected for more than one State-Level event, the student must choose only one event for State-Level representation.

Such multiple-selection cases must be immediately brought to the notice of the Institute Nodal Officer/Event Coordinator, who will finalize the student's State-Level representation.

Platform implementation

This rule is not a restriction on registration.

The application must:

Allow multiple registrations
        ↓
Allow multiple institutional selections
        ↓
When State-level selection is marked
        ↓
Check individual participants
        ↓
Detect duplicate State-level selections
        ↓
Flag conflict
        ↓
Admin/Nodal Officer resolves
C. MASTER EVENT MATRIX

Here is the core specification.

Event	Participation	Institute-level mode	Online submission	Institute selection	Important source deadline
SciToons	Up to 2/team	Offline	To be configured if required	Max 2 entries	Screening 3 Oct; state submission 8 Oct
Poster	1 presenting + 2 co-authors	Offline	Abstract	Best 3 posters	Screening 5 Oct; abstract/state submission 8 Oct
Pharma Quiz	3/team	Offline by default; online preliminary optional	Optional quiz	2 teams	Screening 25 Sep; state submission 8 Oct
Leaflet	1/student	Offline screening	PDF	2 entries	Screening 28 Sep; state submission 8 Oct
Drama/Nukkad Natak	Max 10/team	Offline	Video/Drive link	1 team	Screening before 1 Oct; video submission 8 Oct
Reel Making	2–4/team	Offline	Video	Institute winner/process	Screening 30 Sep; state submission 8 Oct

The dates above are initial values from the supplied document, not immutable application values. All SVCP operational dates will be editable by the Admin/Nodal Officer.

D. EVENT 1 — SCITOONS
AP/State guideline
Team
Maximum 2 participants
Maximum 2 entries from each college at State Level.
Activity

Original humorous cartoon conveying a meaningful message related to Antimicrobial Resistance (AMR).

Materials

Participants must bring drawing materials.

Organizer provides:

One A3 drawing sheet
Hanging clips
A3 drawing hardboard

Participants may use any colouring medium.

Decorative materials such as glitter, stones, sequins, cotton, beads etc. are prohibited.

Important restrictions
One round
Entirely original
Hand-drawn
No copying/tracing
No AI-generated images
No vulgar/offensive/defamatory/inappropriate content.
Judging
Drawing sheet utilization
Creativity
Colour/shading/sketching
Originality and humour/social message
Drawing technique
Neatness/presentation.
Duration

60 minutes

Source dates
Institute screening: 3 October 2026
State-level submission: 8 October 2026.
SVCP configurable fields

Admin can change:

Registration opening
Registration closing
Institute competition date
Reporting time
Competition time
Venue
Coordinator/contact
Internal submission requirement
Internal screening date
Number selected
State submission date
Additional institutional instructions
Registration fields
Team/Entry
Participant 1 ★ Contact Person
Participant 2

Participant 1 gets the primary communication responsibility.

E. EVENT 2 — POSTER PRESENTATION
AP/State guideline
Team

1 Presenting Author + 2 Co-authors

Eligible students include:

Diploma
UG
PG
Pharm.D.
Ph.D.

from PCI-approved colleges.

Institute screening

The institute conducts screening and selects the:

Best three posters

for State-level competition.

Theme

Antimicrobial Resistance.

Suggested topics
AMR epidemiology and surveillance
Antimicrobial stewardship/rational use
Infection prevention/control/vaccination
One Health
AI and digital health in AMR
Novel antimicrobial therapeutics
Rapid diagnostics and precision medicine.
Poster

4 ft × 3 ft

Presentation

3 minutes + 2 minutes Q&A

Judges

Two academic/industrial experts with minimum 10 years' relevant experience.

Source dates
Institute screening: 5 October 2026
State-level submission: 8 October 2026
Abstract before 8 October 2026.
Abstract requirements

Maximum:

250 words

Required:

Title
Authors
Affiliations
Presenting author
Registered participant email
Abstract
3–5 keywords

Formatting includes Times New Roman requirements specified in the document.

Submission:

.doc
.docx
.pdf

Only abstracts accepted by the Scientific Committee become eligible for poster presentation.

Platform workflow
Register
   ↓
Generate code
   ↓
Submit abstract
   ↓
Admin reviews
   ↓
Accepted / Revision / Rejected
   ↓
Institute screening
   ↓
Select top 3
   ↓
State submission
F. EVENT 3 — PHARMA QUIZ
AP/State guideline
Eligibility

Bona fide:

Diploma
UG
Pharm.D.
PG
Ph.D.

students enrolled in pharmacy programmes.

Team

3 students

Institute selection

The document says the institute will finalize:

two teams

for State-level Pharma Quiz.

Possible screening

Written MCQ covering:

Pharmaceutical sciences
Clinical knowledge
General awareness
Interactive rounds

Possible formats:

Rapid fire
Buzzer
Case-based
Audio-visual
Tie-breaker.
Platform implementation
Default
OFFLINE
Optional

Admin can enable:

ONLINE PRELIMINARY QUIZ

if the number of registered teams makes this operationally useful.

The platform therefore has:

Quiz Mode

○ Offline
○ Online Preliminary + Offline Finals

No threshold is hard-coded.

Source date

Institute screening:

25 September 2026

State-level submission:

8 October 2026.

G. EVENT 4 — LEAFLET PREPARATION
AP/State guideline
Participant

1 student per leaflet

Language

Telugu

Size

A4

Format

PDF

Maximum file size

5 MB

Must not contain
Student name
Institute name
Logo
Identification marks.
Theme

World Pharmacists Day 2026 + official AMR theme.

Institute selection

Maximum:

2 shortlisted entries per institute

through the institute Nodal Officer.

State recognition

The document says the best three leaflets receive awards.

Source dates
Institute screening: 28 September 2026
State submission: 8 October 2026.
Platform validation

Before submission:

☐ Telugu
☐ A4 PDF
☐ ≤5 MB
☐ No student name
☐ No institute name
☐ No logo
☐ AMR-related

Some of these can be displayed as participant declarations; file metadata/actual visual content should not be claimed to be automatically verified unless we explicitly implement image/PDF inspection.

H. EVENT 5 — DRAMA / NUKKAD NATAK
AP/State guideline
Team

Maximum:

10 members

including cast and crew.

All members must belong to the same pharmacy institution.

Duration

Maximum:

10 minutes

Location

Must be performed in:

Villages
Street corners
Markets
Parks

The video should include attending public footage.

Language
Telugu
Hindi
Combination

English words where appropriate.

Institute selection

Institute conducts preliminary round and selects:

One winning team

for State level.

Video

Google Drive link required.

The supplied document states that the link should be accessible to the organizing committee/judges and specifies Editor permission.

Technical requirements
Single shot
No edits/cuts
Clear audio/video
Preferably landscape
Minimum 720p
Video starts with title
No student/institution identity.
Prohibited
Vulgarity
Abusive language
Personal remarks
Character assassination
Political content
Religious content
Discriminatory content
Disclosure of identity.
Source deadlines
Institute screening before 1 October 2026
Video submission 8 October 2026
Late submissions not entertained.
I. EVENT 6 — REEL MAKING
AP/State guideline
Eligibility
D.Pharm
B.Pharm
M.Pharm
Pharm.D

All members must belong to the same institute.

Team

2–4 members

Submission

Registration followed by Final Submission Form containing:

Google Drive video link
Team declaration
References.
Theme/content

Strictly AMR.

Possible angles include:

Rational antibiotic use
Stewardship
Self-medication risks
Completing full courses
AMR prevention
Infection control
Pharmacist's role
Public awareness.
Requirements
Original work
Evidence-based
Authentic references
English/Hindi/Telugu or combination
Subtitles required
Generic drug names
No brand promotion.
Video
MP4/Reel
Minimum 1080p
9:16 or 16:9
60–180 seconds
≤1 GB.
AI

AI-generated content is explicitly permitted if disclosed.

Suggested declaration is provided in the guideline.

Evaluation
Relevance
Scientific accuracy
Creativity/originality
Message clarity
Educational/social impact
Audio-visual quality
Overall presentation.
Competition stages

The document describes:

Institute → Scrutiny → State level.

Source dates
Institute screening: 30 September 2026
State submission: 8 October 2026.
J. COMMON REGISTRATION ENGINE

This is now the most important technical component.

Instead of six different registration systems, we create one registration engine.

Step 1 — Select event
Which event are you registering for?

[ SciToons ]
[ Poster ]
[ Pharma Quiz ]
[ Leaflet ]
[ Drama ]
[ Reel ]
Step 2 — Team details

System automatically loads the correct team structure.

For example:

Quiz
Participant 1 ★ Contact Person
Participant 2
Participant 3
Leaflet
Participant 1 ★ Contact Person
Drama
Participant 1 ★ Contact Person
Participant 2
...
Participant 10
K. PARTICIPANT DATA
Participant 1

Clearly labelled:

⭐ CONTACT PERSON / TEAM LEADER

Required:

Student ID/Roll No.
Name
Programme
Year/Class
Mobile
Email
Other members
Student ID/Roll No.
Name
Programme
Year/Class

This allows us to calculate meaningful participation statistics.

L. PROGRAMME/YEAR MASTER

Initial configuration:

D.Pharm
I Year
II Year
B.Pharm
I Year
II Year
III Year
IV Year
Pharm.D
I Year
II Year
III Year
IV Year
V Year
VI Year
M.Pharm
I Year
II Year
Ph.D.

Configured appropriately by Admin.

Important: These are initial institutional configuration assumptions, not rules extracted from the AP document. We should confirm the exact classes/labels you want before final deployment.

The Admin should be able to add/change programme/year options.

M. UNIQUE REGISTRATION CODE

Each entry receives:

SVCP26-SCI-001
SVCP26-POST-001
SVCP26-QUIZ-001
SVCP26-LEAF-001
SVCP26-DRAMA-001
SVCP26-REEL-001

The code identifies the entry/team, not an individual student.

N. DUPLICATE STUDENT ENGINE

This is now a core requirement.

If the same Student ID appears in:

SVCP26-POST-014
SVCP26-QUIZ-021
SVCP26-REEL-008

the system recognizes:

One unique student, three event participations.

This allows us to distinguish:

Total entries

from

Total participant records

from

Unique students.
O. STATE-LEVEL CONFLICT ENGINE

This is activated only when the Admin selects State-level representatives.

Example:

POSTER
SVCP26-POST-014
       │
       └── Student A

REEL
SVCP26-REEL-008
       │
       └── Student A

System:

⚠ MULTIPLE STATE-LEVEL SELECTION

Then:

Student A has been selected for more than one State-Level event.

Admin must select:

Final State Representation

[ Poster Presentation ▼ ]

[ CONFIRM ]

The other selection becomes:

Not represented at State Level due to common-day scheduling conflict.

Again, the system flags; the Nodal Officer decides.

P. ADMIN-CONFIGURABLE EVENT SETTINGS

This is a P0 architectural requirement.

Every event has:

Basic
Name
Short description
Full instructions
Theme
Eligibility
Team size
Registration
Registration open/closed
Opening date
Closing date
Maximum entries, if applicable
Event
Date
Time
Reporting time
Venue
Mode
Coordinator/contact
Submission
Required?
Opening date
Closing date
File types
File size
Drive link
Submission instructions
Screening
Screening date
Time
Venue
Selection limit
State
State submission date
State event date
State event information
Q. ADMIN CAN CHANGE THESE WITHOUT DEVELOPER

This is critical.

Suppose the original AP guideline says:

Poster screening — 5 October

but SVCP later decides:

Institutional screening — 4 October.

Admin simply changes:

Institute Screening Date

from:

05-10-2026

to:

04-10-2026

The website immediately displays the new institutional date.

The original state guideline remains separately displayed.

R. EDITABLE INSTITUTIONAL INSTRUCTIONS

Every event should have:

Shri Vishnu College of Pharmacy — Institutional Instructions

Admin can edit:

reporting instructions
venue
dress code if applicable
materials to bring
internal submission procedure
screening procedure
faculty coordination instructions
deadlines
contact details
any additional notices.

This should use a simple rich-text editor.

S. ANNOUNCEMENT SYSTEM

Admin can publish:

Normal announcement

Poster registration extended until...

Important announcement

Quiz venue changed...

Urgent announcement

Today's event reporting time changed...

Each can have:

title
message
publication date
expiry date
priority.
T. ADMIN DASHBOARD — FINAL SPECIFICATION
Top KPIs
TOTAL ENTRIES
TOTAL PARTICIPANT RECORDS
UNIQUE STUDENTS
TOTAL EVENTS

Then:

Event-wise
SciToons
Poster
Quiz
Leaflet
Drama
Reel
Programme-wise
D.Pharm
B.Pharm
Pharm.D
M.Pharm
Ph.D.
Class-wise
B.Pharm I
B.Pharm II
...
Pharm.D I
...
U. CROSS-EVENT ANALYTICS

Admin should be able to answer immediately:

How many students participated?

How many entries?

How many teams?

Which event has maximum participation?

How many B.Pharm I-year students participated?

How many Pharm.D students participated?

How many students participated in multiple events?

Who is participating in three events?

Who has been selected for two State-level events?

These should all be dashboard/filter operations, not manual Excel work.

V. PRINCIPAL VIEW

The Principal sees:

Institutional Event Overview

Read-only.

Key numbers
Total entries
Unique students
Total participations
Event-wise participation
Programme-wise participation
Year-wise participation
Selected entries
State-level final representation
Multiple-selection conflicts
Submission completion

No editing controls.

W. PARTICIPANT VIEW

No complicated account creation initially.

MY REGISTRATION

Enter:

Registration Code

Example:

SVCP26-POST-014

Then:

Registration
✓ Complete

Team
✓ Complete

Abstract
✓ Submitted

Screening
✓ Completed

Selection
✓ Selected

State Representation
✓ Finalized
X. ONLINE SUBMISSION ENGINE

The submission engine should be event-specific.

Poster

Abstract upload

Leaflet

PDF upload

Drama

Google Drive video link

Reel

Google Drive video link

Quiz

No submission unless online quiz is activated.

SciToons

No online competition; any submission mechanism can be activated by Admin if required.

Y. OFFLINE-FIRST DESIGN

This is now a fundamental principle.

The application should never make internet connectivity necessary for conducting the physical event, except for optional digital services.

For example:

Poster

Offline presentation.

SciToons

Offline drawing.

Drama

Offline performance.

Leaflet

Offline/institutional activity with online submission as required.

Quiz

Offline by default.

Reel

Offline/institutional process with digital submission.

Z. QUIZ ENGINE — OPTIONAL MODULE

The quiz engine exists inside the platform but can remain disabled.

Admin:

Quiz Mode

OFFLINE

If needed:

ONLINE PRELIMINARY

Then Admin can create:

Round
Round name
Questions
Duration
Marks
Negative marks
Randomization
Number of questions
Pass/shortlist criteria

This remains flexible.

AA. DATABASE — FINAL HIGH-LEVEL MODEL

I would now design approximately:

institution_settings
programmes
academic_years

events
event_rules
event_schedules
event_instructions
announcements

students

registrations
registration_members

submissions
submission_files

screenings
screening_scores
selections

state_selections
selection_conflicts

quiz_rounds
quiz_questions
quiz_attempts
quiz_answers

admin_users
principal_users

audit_logs

We don't need dozens of roles or dozens of separate modules.

AB. VERY IMPORTANT: STUDENT MASTER

I recommend that we support a student master table even if we initially populate it manually.

Student ID
Name
Programme
Year
Section
Status

Then the registration engine can verify:

Does this student actually belong to SVCP?

and prevent accidental duplicate student records.

If you can provide the student master later, we can import it.

AC. DATA VALIDATION

At registration:

Required
Contact person's name
Contact mobile
Contact email
Student ID
Programme
Year
Team members according to event
Required event-specific fields.
Automatic validation
Valid email
Valid mobile
Maximum team size
Required members
Duplicate Student ID
Registration deadline
Event status.
AD. DEADLINE ENGINE

This is another P0 component.

Suppose Admin sets:

Registration closes 30 September 11:59 PM.

At that exact time:

Registration button

automatically changes:

REGISTER NOW

→

REGISTRATION CLOSED

No developer intervention.

Similarly for submissions.

AE. DATE CONFLICT WARNING

When Admin edits an event schedule, the system can warn:

⚠ This date overlaps with another institutional event.

This is useful but should not prevent saving.

The Admin decides.

AF. EVENT CONFIGURATION — THE MOST IMPORTANT DATABASE PRINCIPLE

Every event should be represented as data.

Conceptually:

{
  "event_code": "POST",
  "name": "Poster Presentation",
  "registration_open": true,
  "registration_deadline": "...",
  "screening_date": "...",
  "venue": "...",
  "team_max": 3,
  "submission_required": true,
  "submission_deadline": "...",
  "state_submission_deadline": "...",
  "selection_limit": 3
}

The frontend simply reads this configuration.

No dates/rules should be buried in React components.

AG. SOURCE-OF-TRUTH HIERARCHY

This should be explicitly documented inside the developer specification.

Level 1

AP State Guideline PDF

Source of state-level rules.

Level 2

SVCP Institutional Configuration

Dates, venues, local instructions, registration deadlines etc.

Level 3

Application Logic

Implements those rules.

Therefore:

Application logic must never silently override the source or institutional configuration.

AH. ITEMS THAT NEED NO FURTHER CLARIFICATION NOW

We have enough information to begin the software architecture.

I would not delay development for minor details.

The following can have sensible defaults and remain editable:

registration deadline
event times
venues
reporting times
contact details
announcements
institutional instructions
class labels
maximum internal registrations
quiz mode.
AI. ITEMS I WILL NOT INVENT

There are some things the supplied document doesn't establish completely.

For example, it does not give us your actual:

SVCP event dates/times
venue
internal registration deadline
nodal officer details
student master data
exact institutional screening arrangements
exact quiz online/offline decision.

Therefore the application will initially use:

TO BE ANNOUNCED / CONFIGURE IN ADMIN

rather than inventing values.

This is important.

AJ. FINAL USER JOURNEY

The student experience becomes:

OPEN WEBSITE
      ↓
SEE SVCP IDENTITY + THEME
      ↓
READ IMPORTANT NOTICE
      ↓
EXPLORE EVENTS
      ↓
SELECT EVENT
      ↓
READ RULES
      ↓
REGISTER TEAM
      ↓
PARTICIPANT 1 = CONTACT PERSON
      ↓
SUBMIT
      ↓
RECEIVE UNIQUE CODE
      ↓
PARTICIPATE OFFLINE
      ↓
SUBMIT ABSTRACT/PDF/VIDEO IF REQUIRED
      ↓
CHECK STATUS
      ↓
INSTITUTE SCREENING
      ↓
SELECTION
      ↓
STATE-LEVEL CONFLICT CHECK
      ↓
FINAL STATE REPRESENTATION
AK. ADMIN JOURNEY
LOGIN
 ↓
ADMIN DASHBOARD
 ↓
CONFIGURE EVENTS
 ↓
SET DATES
 ↓
SET DEADLINES
 ↓
SET VENUES
 ↓
PUBLISH INSTRUCTIONS
 ↓
MONITOR REGISTRATIONS
 ↓
SCREEN
 ↓
SELECT WINNERS
 ↓
CONFLICT DETECTION
 ↓
FINALIZE STATE REPRESENTATIVES
 ↓
EXPORT REPORTS
AL. PRINCIPAL JOURNEY
LOGIN
 ↓
VIEW DASHBOARD
 ↓
Participation
 ↓
Programme/Class analysis
 ↓
Event-wise analysis
 ↓
Selection status
 ↓
State-level final representation
 ↓
Reports
AM. FINAL P0/P1 SCOPE
P0 — must work before deployment

Public

SVCP-branded homepage
six event pages
rules
dates
important notice
editable institutional instructions
announcements
registration
unique codes

Registration

team registration
Contact Person
programme/year
duplicate detection
multiple-event participation

Submission

abstract
PDF
Drive links
event-specific requirements

Admin

one Admin/Nodal Officer
complete configuration
deadlines
venues
announcements
screening
selections
conflict detection
exports

Principal

read-only dashboard

Analytics

entries
teams
participant records
unique students
event-wise
programme-wise
year-wise
multiple-event participation
State-level conflicts.
P1 — after the core platform is stable
QR codes
QR attendance
digital judging
quiz engine
live quiz
live event timer
certificate generation
advanced reporting
automated email
event-day control panel.
AN. One final architectural decision

I recommend that we do not build P1 features before the P0 registration/admin system is working.

The sequence should be:

Build 1

Website + database + admin configuration

Build 2

Registration + unique codes

Build 3

Submission + screening

Build 4

Analytics + Principal dashboard

Build 5

Quiz

Build 6

Event-day enhancements

This gives us a functioning system very early and prevents the quiz/certificate/QR features from delaying the essential event-management platform.

Next: Stage 2 — actual build

I consider the functional specification sufficiently defined to start development.

We can now move away from planning and start creating the actual application.

I suggest our next build sequence will be:

1. Create the production database schema and Supabase migrations

2. Create the React/Vite application

3. Create the SVCP-branded homepage

4. Create the six event configuration records from the AP guideline

5. Create the Admin/Nodal Officer interface

6. Create registration + unique code engine

7. Connect Google Drive/Sheets

8. Build dashboards

9. Build quiz module

10. Test and deploy

For the actual implementation, I can generate the project files/code and progressively test them here. When we reach the GitHub/Supabase/Google integration stage, we'll use the appropriate connected access/secrets securely rather than putting private tokens into the conversation.

I would start next with the Supabase schema + migration set, because that will lock the data model for registrations, participants, events, submissions, screening, State-level conflict detection and analytics before we build the UI around it.

proceed

Proceeding. I have now moved from specification into the actual implementation foundation.

What I created

I prepared the first production-oriented project package containing:

Supabase PostgreSQL schema
Initial migration
Institution configuration
Admin/Principal role model
Programme/year structure
Six event definitions
Event schedules
Editable event rules/instructions
Submission requirements
Students
Team registrations
Contact-person structure
Unique registration-code architecture
Screening
Institute/State selection
Multiple-State-selection conflict structure
Quiz rounds/questions/attempts
Announcements
Audit logging
Row-level security foundation
Environment-variable template
Master specification/README
Download the current foundation

Download SVCP WPD & NPW 2026 Foundation ZIP

Important implementation decision

The migration deliberately treats dates and institutional operational settings as data, rather than putting them into frontend code.

So later the Nodal Officer can change:

Registration deadline
Screening date
Event date
Venue
Submission deadline
Instructions
Announcements
Selection limits

without touching the code.

The six events and their initial state-derived values are seeded from your supplied AP guideline. For example, the source specifies the SciToons 60-minute duration and 3 October institute screening, poster 5 October screening, quiz 25 September screening, leaflet 28 September screening, drama before 1 October, and reel 30 September screening, with several state submissions due 8 October.

One thing I want to improve before we call the database migration "production ready"

The foundation is deliberately conservative, but before applying it to your live Supabase project I would add the registration transaction/API layer rather than allowing the browser to insert registrations directly.

That layer will be responsible for:

Generating SVCP26-POST-001 style codes safely.
Validating team size.
Validating registration deadlines.
Detecting duplicate Student IDs.
Ensuring exactly one Contact Person.
Creating the registration + members atomically.
Preventing race conditions when two students register simultaneously.
Creating audit records.
Returning the confirmation/code to the participant.

This is important because registration-code generation and duplicate checking should be server-controlled, not trusted to the browser.

Next build milestone

I recommend we now proceed in this exact order:

Milestone 2 — Registration Engine

Build:

Public homepage → Event selection → Dynamic registration form → Student validation → Team registration → Unique code → Confirmation → My Registration lookup

Then:

Milestone 3

Admin/Nodal Officer dashboard.

Milestone 4

Principal read-only dashboard.

Milestone 5

Submission engine.

Milestone 6

Screening + State-selection conflict system.

Milestone 7

Quiz engine.

Milestone 8

Google Drive/Sheets integration.

Milestone 9

Mobile/PWA optimisation, testing and deployment.

This order means we can get the core registration system working very early, instead of spending time on decorative features first.

proceed and wherever and whenever necessary provide instructions / guidance for me what i should do 

Yes. I have proceeded with the actual application build, not just the specification.

What is completed in this build

The current V1 foundation now contains:

Modern responsive SVCP WPD/NPW 2026 homepage
Six institutional events
Event directory
Online team/entry registration
Participant 1 automatically treated as Contact Person / Team Leader
Programme + academic-year selection
Multiple participants according to event-specific limits
Secure server-side registration function
Automatic registration codes such as SVCP26-POST-001
Registration deadline enforcement
"My Registration" lookup using registration code + contact mobile/email
Supabase RLS/security foundation
Admin/Nodal Officer authentication
Principal read-only authentication
Admin control centre foundation
Event open/close controls
Registration/submission enable controls
Editable institutional homepage information
Editable schedules/deadlines/venues
Editable rules/instructions
Separate state_guideline and institutional_instruction classifications
Announcement management
Registration statistics:
entries/registrations
participant records
unique students
Principal event-wise overview
Netlify deployment configuration
Secure .env structure
Admin bootstrap instructions

The source guideline has been kept as the basis for competition requirements, while institutional operational information is deliberately separated so that an SVCP date or venue can be changed without modifying the state-level rules. This is particularly important because the supplied guideline contains different event-specific screening/submission dates rather than one universal operational date.

Download the current project

Download SVCP WPD & NPW 2026 V1 project

What you need to do now

Don't start changing the code yet. First complete the following setup.

STEP 1 — Create the Supabase project

Go to your Supabase account and create a new project specifically for this application.

For example:

Project name:
svcp-wpd-npw-2026

You will eventually need:

Project URL
Supabase anon/public key

You do not need to give me your service-role key.

STEP 2 — Run the database migrations

After opening the Supabase project:

SQL Editor → New query

Run these three files in this exact order:

supabase/migrations/001_initial_schema.sql
supabase/migrations/002_registration_api.sql
supabase/migrations/003_security_and_deadlines.sql
Important

Do not combine them randomly.

The order is:

001 → 002 → 003

The first migration creates the database architecture.

The second creates the secure public registration engine.

The third adds the additional security/read-only access and deadline enforcement.

STEP 3 — Create the Admin/Nodal Officer account

In Supabase:

Authentication → Users → Add user

Create the account for the person who will manage the portal.

For example:

Email: your institutional admin email
Password: strong unique password

Do not use a temporary weak password for the production account.

After creating the user, Supabase will show a User UID.

Copy that UID.

STEP 4 — Connect that user to the Admin role

Open:

docs/ADMIN_BOOTSTRAP.sql

You will see:

insert into public.app_users (id, role, display_name, email)
values ('AUTH_USER_UUID', 'admin', 'SVCP Nodal Officer', 'admin@example.com')

Replace:

AUTH_USER_UUID

with the actual Supabase Auth User UID.

Replace the name/email as appropriate.

Then execute it in Supabase SQL Editor.

After this, the user becomes:

Admin / Nodal Officer

and gets editing privileges.

STEP 5 — Principal account

You can create the Principal account now or later.

If you want it now:

Create another Supabase Auth user.
Obtain the UID.
Use the commented SQL in ADMIN_BOOTSTRAP.sql.
Assign:
role = principal

The Principal dashboard is intentionally read-only.

So the architecture is:

                    SVCP PORTAL
                         │
             ┌───────────┴───────────┐
             │                       │
       PUBLIC USERS              AUTH USERS
             │                       │
      Registration              ┌────┴────┐
      My Registration            │         │
      Event information        ADMIN    PRINCIPAL
                                 │         │
                              EDIT ALL    VIEW ONLY

This follows your decision to have only Admin/Nodal Officer + Principal initially.

STEP 6 — Do NOT open registrations immediately

This is important.

The migration intentionally seeds the six events as:

draft

That is deliberate.

After logging into:

#admin

you will configure each event.

For example:

SCI
POST
QUIZ
LEAF
DRAMA
REEL

For an event that is ready:

Status → open
Registration → ON

Then add its:

registration deadline
event date
event time
venue
screening date
submission deadline
institutional instructions

This means you won't have to ask me to change the code every time a date or venue changes.

STEP 7 — Important distinction we have preserved

There are now three conceptual layers:

1. State-level guideline

For example:

eligibility
team limits
AMR requirements
poster specifications
reel specifications
drama requirements
judging criteria
state submission requirements

These are derived from the supplied guideline.

For example, the poster guideline specifies the 1 presenting author + 2 coauthors structure and the 4 ft × 3 ft poster size.

The Reel guideline contains its own team size, video duration, resolution, language, AI disclosure and originality requirements.

2. SVCP institutional instructions

Things such as:

Registration opens:
Registration closes:
Screening venue:
Reporting time:
Faculty coordinator:
Room:
Institute screening date:

These can change.

3. Application behaviour

Things such as:

team_min
team_max
registration code generation
duplicate/conflict detection
selection workflow
submission workflow
analytics

These are implemented in software.

This separation is one of the most important architectural decisions in the project.

STEP 8 — Configure the frontend

In the project directory:

svcp-wpd-npw-2026

create:

.env.local

using .env.example.

It should contain:

VITE_SUPABASE_URL=https://YOUR-PROJECT.supabase.co
VITE_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY
Very important

Only use the:

anon/public key

in the React application.

Never put:

service_role key

into the frontend.

Never commit it to GitHub.

STEP 9 — Deploy to Netlify

The project already contains:

netlify.toml

So the intended deployment flow is:

GitHub
   ↓
Netlify
   ↓
React/Vite application
   ↓
Supabase

In Netlify environment variables add:

VITE_SUPABASE_URL
VITE_SUPABASE_ANON_KEY

Then deploy.

One limitation I want to be transparent about

I attempted to install the npm dependencies and run the Vite production build in this environment, but the package installation timed out because the environment did not complete the npm download.

Therefore, I do not want to falsely tell you that V1 has passed a local production build test.

The source/project structure has been created, but your environment should perform:

npm install
npm run build

before deployment.

If npm install completes normally on your machine/GitHub/Netlify, the next validation step is:

npm run build

and we should fix any compiler/runtime issue before calling this production-ready.

What I recommend we build next

I would not stop at the current V1.

The next development milestone should be the actual Institutional Event Management Engine, particularly because your requirement is more than simple registration.

The next version should add:

Admin analytics
TOTAL ENTRIES
TOTAL PARTICIPANTS
UNIQUE STUDENTS

        ↓

EVENT-WISE
PROGRAMME-WISE
YEAR-WISE
SECTION-WISE

        ↓

MULTIPLE-EVENT PARTICIPANTS

For example:

Programme	Year	SciToons	Poster	Quiz	Leaflet	Drama	Reel
B.Pharm	I Year						
B.Pharm	II Year						
B.Pharm	III Year						
Pharm.D	I Year						

This will directly answer your management-level question:

How many students actually participated and from which programme/year?

Then the selection engine

This is particularly important.

The system should allow:

Registration
     ↓
Institute Screening
     ↓
Score / Eligibility
     ↓
Selected / Not Selected
     ↓
State-Level Selection
     ↓
Conflict Detection

If the same student appears in:

Poster → Selected
Reel → Selected
Quiz → Selected

the system should flag:

STATE-LEVEL PARTICIPATION CONFLICT

It must not automatically choose one, because you explicitly decided that the student/institute coordinator must make the final decision.

That is the correct approach.

Then submission management

Especially for:

Poster abstract
Leaflet PDF
Drama video/Drive link
Reel video/Drive link
declarations
AI disclosure where applicable

The supplied guideline specifically requires online submission elements for several of these events, while the actual institutional competition remains offline.

Then Google Drive/Sheets integration

We should not use Supabase Storage for the large video files.

For the Reel/Drama workflows, the better architecture remains:

Student
   ↓
SVCP Portal
   ↓
Google Drive link
   ↓
Admin verification
   ↓
Submission record

while:

Supabase
   ↓
metadata + registration + status + audit

and:

Google Sheets
   ↓
management/export/reporting
Your immediate action

For now, please do only these four things:

1. Download the V1 ZIP

Download project

2. Create the Supabase project

3. Run migrations 001 → 002 → 003

4. Create the Admin Auth user and execute ADMIN_BOOTSTRAP.sql

Then tell me simply:

"Supabase setup completed"

At that point, I can take the project to the next implementation milestone: full Admin/Nodal Officer management + comprehensive analytics + event rules/schedules + screening/selection/conflict engine, rather than leaving you with a prototype.
