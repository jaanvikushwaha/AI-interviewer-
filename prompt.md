Act as a senior frontend engineer, UI/UX designer, and AI product architect.

Build a polished, responsive web application called:

"AI Interview Agent"

The application is an AI-powered technical interview command center that conducts personalized technical interviews based on a candidate's actual learning journey, curriculum, skills, and profile.

IMPORTANT:
Do not make this a generic AI interview dashboard.
Recreate the visual style, information architecture, layout, and overall experience described below.

==================================================
1. CORE PRODUCT
==================================================

The product should have four primary sections:

1. Interview
2. Dashboard
3. Candidates
4. Curriculum

The default landing screen should be the:

"AI Interview Command Center"

Subtitle:

"Personalized technical interviews powered by the candidate's actual learning journey."

Include a prominent:

"Start Interview →"

CTA.

==================================================
2. VISUAL DESIGN
==================================================

Use a sophisticated editorial/product-dashboard aesthetic.

The design should be:

- Minimal
- Clean
- Premium
- Professional
- Highly readable
- Spacious
- Modern but not overly futuristic
- AI-product focused
- Suitable for a hackathon presentation

Use:
- White/off-white primary content background
- Dark black/dark charcoal text
- Thin light-gray borders
- Subtle rounded corners
- Small uppercase labels
- Strong serif-style headings where appropriate
- Clean sans-serif supporting text
- Monospace/technical typography for labels and statistics where appropriate

Do NOT use:
- Excessive gradients
- Glassmorphism everywhere
- Neon colors
- Excessive animations
- Cluttered cards
- Generic template-looking UI

Use subtle accent colors only for card top borders and important status indicators.

==================================================
3. TOP NAVIGATION
==================================================

Create a horizontal navigation bar at the top.

Brand:

"AI Interview Agent"

Navigation items:

Interview
Dashboard
Candidates
Curriculum

The active section should be visually distinguished.

On smaller screens, make the navigation responsive without destroying the clean desktop layout.

==================================================
4. COMMAND CENTER HEADER
==================================================

The main page should begin with a small uppercase eyebrow label:

COMMAND CENTER

Then a large heading:

AI Interview Command Center

Then:

Personalized technical interviews powered by the candidate's actual learning journey.

Below this, show:

Start Interview →

The CTA should be simple and editorial rather than looking like a generic rounded SaaS button.

==================================================
5. METRIC CARDS
==================================================

Under the header, create a responsive grid of metric cards.

The cards should have:

- White background
- Thin gray border
- Slightly rounded corners
- Large numeric value
- Small uppercase title
- Supporting description
- A very thin colored line along the top edge

Create these cards:

CARD 1:

Label:
CANDIDATES

Value:
3

Description:
synthetic profiles

Accent:
warm yellow/orange

CARD 2:

Label:
INTERVIEW READINESS

Value:
72%

Description:
cohort average

Accent:
teal/turquoise

CARD 3:

Label:
TOPICS COVERED

Value:
8

Description:
curriculum topics

Accent:
muted blue/gray

CARD 4:

Label:
INTERVIEW PROGRESS

Value:
—

Description:
no active session

Accent:
warm yellow/orange

CARD 5:

Label:
TECHNICAL SCORE

Value:
—

Description:
n/a

Accent:
teal/turquoise

The grid should automatically adapt:
- Desktop: multiple columns
- Tablet: 2 columns
- Mobile: 1 column

==================================================
6. CANDIDATE PREVIEW SECTION
==================================================

Below the metrics, display candidate cards.

Use realistic synthetic candidate information.

Example candidate:

Maya Okoro

candidate_001

Readiness:
92%

Candidate summary:

"A support-ticket RAG assistant with semantic ..."

Create a clean candidate card containing:

- Candidate name
- Candidate ID
- Readiness percentage
- Short profile/project description
- Relevant skills
- Interview readiness indicator
- View Candidate action

Use synthetic candidate data only.

Add at least 3 candidate profiles.

Example:

Maya Okoro
candidate_001
92%

Arjun Mehta
candidate_002
78%

Sofia Chen
candidate_003
66%

==================================================
7. CANDIDATES PAGE
==================================================

Create a dedicated Candidates page.

Display all synthetic candidate profiles.

Each candidate should include:

- Name
- Candidate ID
- Education
- Skills
- Learning progress
- Curriculum completion
- Interview readiness
- Technical score
- Projects
- Recommended interview difficulty

Allow the user to select a candidate.

When selected, show a detailed candidate profile.

==================================================
8. CURRICULUM PAGE
==================================================

Create a Curriculum section showing the learning journey that powers the interviews.

Example curriculum topics:

1. Programming Fundamentals
2. Data Structures
3. Algorithms
4. Databases
5. APIs
6. JavaScript
7. React
8. AI/ML Fundamentals

For each topic show:

- Topic name
- Completion percentage
- Difficulty
- Status
- Related skills
- Interview questions available

The AI interviewer should use this curriculum to determine which questions are appropriate.

==================================================
9. INTERVIEW EXPERIENCE
==================================================

When the user clicks:

"Start Interview →"

open an interview setup flow.

First select candidate.

Then show:

Candidate:
Maya Okoro

Target:
Technical Interview

Interview based on:
Candidate's learning journey

Difficulty:
Adaptive

Then start the interview.

==================================================
10. AI INTERVIEW SCREEN
==================================================

Create a focused interview interface.

Show:

AI INTERVIEW

Candidate name

Question progress:

Question 1 / 10

Current topic:

Retrieval-Augmented Generation

Question example:

"Explain how you would evaluate the quality of a retrieval-augmented generation system."

Provide a response area.

Actions:

Submit Answer
Skip
End Interview

Include a subtle progress indicator.

==================================================
11. ADAPTIVE INTERVIEW LOGIC
==================================================

This is a core feature.

The AI must NOT simply ask 10 predetermined questions.

Instead:

Candidate Profile
        ↓
Learning Journey
        ↓
Curriculum
        ↓
Current Skill Level
        ↓
Interview Question
        ↓
Candidate Answer
        ↓
AI Evaluation
        ↓
Adaptive Follow-up Question
        ↓
Next Topic

If the candidate answers correctly:
- Increase difficulty
- Ask deeper follow-up questions

If the candidate struggles:
- Ask a simpler diagnostic question
- Identify the knowledge gap
- Move appropriately through the curriculum

==================================================
12. AI EVALUATION
==================================================

After every answer, internally evaluate:

- Technical correctness
- Conceptual understanding
- Relevance
- Problem-solving ability
- Depth
- Communication clarity

Do not immediately expose every internal evaluation during the interview.

Use the collected results to create the final report.

==================================================
13. INTERVIEW RESULTS
==================================================

After completing the interview, generate a detailed result page.

Show:

Technical Score
Communication
Problem Solving
Curriculum Understanding
Overall Score

Example:

Technical Score: 84%
Problem Solving: 79%
Communication: 88%
Curriculum Understanding: 81%

Overall:
83%

Then show:

STRENGTHS

- Strong understanding of core concepts
- Good technical reasoning
- Clear explanations

AREAS TO IMPROVE

- Advanced system design
- Retrieval evaluation
- Database optimization

Then show:

RECOMMENDED NEXT STEPS

The AI should recommend specific curriculum topics based on weaknesses.

==================================================
14. DASHBOARD ANALYTICS
==================================================

The Dashboard section should provide aggregate information.

Show:

Candidates
Interview Readiness
Topics Covered
Interview Progress
Technical Score

Add useful analytics such as:

- Average candidate readiness
- Curriculum completion
- Interview performance
- Topic-level strengths
- Topic-level weaknesses
- Recent interview activity

Keep charts minimal and consistent with the editorial design.

==================================================
15. DATA MODEL
==================================================

Use synthetic data for:

Candidates
Curriculum
Interview sessions
Questions
Answers
Scores
Learning progress

Do NOT use real personal information.

==================================================
16. FUNCTIONALITY
==================================================

Make the prototype interactive.

Implement:

- Navigation between Interview / Dashboard / Candidates / Curriculum
- Candidate selection
- Candidate detail view
- Curriculum browsing
- Interview setup
- Start interview
- Question progression
- Answer submission
- Adaptive question simulation
- Interview completion
- Score generation
- Results page
- Dashboard updates

Use realistic mock AI responses if a real AI API is not connected.

==================================================
17. AI ARCHITECTURE
==================================================

Structure the code so an LLM API can be integrated later.

Create service functions such as:

generateQuestion()
evaluateAnswer()
generateFollowUp()
calculateTechnicalScore()
analyzeSkillGap()
generateInterviewReport()
recommendCurriculum()

For the prototype, use mock data.

Never expose API keys in frontend code.

==================================================
18. TECH STACK
==================================================

Use:

React
TypeScript or JavaScript
Tailwind CSS
Lucide React icons
Recharts if charts are required

Create reusable components.

Suggested structure:

App
Navigation
CommandCenter
MetricCard
CandidateCard
CandidateProfile
CurriculumCard
InterviewSetup
InterviewSession
QuestionPanel
EvaluationPanel
ResultsPage
Analytics
Dashboard

==================================================
19. RESPONSIVE DESIGN
==================================================

The design must work on:

Desktop
Tablet
Mobile

On mobile:

- Keep the top navigation clean
- Stack metric cards vertically
- Make candidate cards full-width
- Maintain readable typography
- Keep interview controls easy to use
- Avoid horizontal overflow

==================================================
20. IMPORTANT DESIGN REFERENCE
==================================================

The visual direction should resemble a refined editorial AI command center:

Top:
AI Interview Agent
Interview | Dashboard | Candidates | Curriculum

Main:

COMMAND CENTER

AI Interview Command Center

Personalized technical interviews powered by the
candidate's actual learning journey.

Start Interview →

Then:

[CANDIDATES]
3
synthetic profiles

[INTERVIEW READINESS]
72%
cohort average

[TOPICS COVERED]
8
curriculum topics

[INTERVIEW PROGRESS]
—
no active session

[TECHNICAL SCORE]
—
n/a

Then candidate profiles.

The final product should feel like an actual internal AI interview operations platform rather than a generic student dashboard.

==================================================
FINAL GOAL
==================================================

Build a polished, functional AI Interview Command Center that demonstrates:

1. Candidate-aware interviewing
2. Curriculum-aware questioning
3. Adaptive AI interviews
4. Technical evaluation
5. Interview readiness scoring
6. Skill-gap identification
7. Personalized learning recommendations
8. Candidate analytics

The core product idea should be:

"An AI interviewer that understands what the candidate has actually learned and interviews them accordingly."

Make the result visually impressive, technically credible, responsive, and ready for a hackathon demo.