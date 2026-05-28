MeetMind AI
An AI-powered workplace assistant that automatically summarises meetings and turns them into actionable tasks.

What is MeetMind AI?
MeetMind AI is a web application designed to eliminate the manual work that follows every meeting. It listens to your meetings, generates concise summaries, detects action items, assigns owners, and pushes tasks directly to the tools your team already uses — all without anyone lifting a finger.
Whether you are running a quick stand-up or a two-hour planning session, MeetMind AI ensures nothing falls through the cracks.
Features
•	Live transcription — Live transcription
•	Captures audio from video calls or in-person meetings and converts it to a searchable transcript in real time.
•	AI-generated summaries — AI-generated summaries
•	Produces a concise recap of key decisions, discussion points, and outcomes immediately after the meeting ends.
•	Automatic task detection — Automatic task detection
•	Identifies action items from the conversation, assigns them to the relevant person, and sets due dates.
•	Integration push — Integration push
•	Sends tasks directly to Slack, Jira, Asana, or Notion with one click — no copy-pasting required.
•	Follow-up scheduling — Follow-up scheduling
•	Suggests and books follow-up meetings based on open or unresolved action items.
•	Calendar sync — Calendar sync
•	Connects to Google Calendar or Outlook and joins meetings automatically.
Pages
Page	Description
Home / Landing	Overview of the product, feature highlights, and call-to-action
Dashboard	List of recent meetings with summaries and task counts
Meeting Detail	Full transcript, AI summary, and interactive task checklist
Upload / Connect	Upload audio or video files, or link your calendar
Settings	Manage profile, integrations, and notification preferences

Tech Stack
This app is built with Lovable and uses the following:
Layer	Technology
Frontend	React, Tailwind CSS
AI	Claude API (Anthropic) for summarisation and task extraction
Auth	Supabase Auth
Database	Supabase (PostgreSQL)
Integrations	Slack API, Jira API, Asana API, Notion API
Calendar	Google Calendar API, Microsoft Graph API (Outlook)

Getting Started
1. Clone the repository
git clone https://github.com/your-username/meetmind-ai.git
cd meetmind-ai
2. Install dependencies
npm install
3. Set up environment variables
Create a .env file in the root of the project and add the following:
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_ANTHROPIC_API_KEY=your_anthropic_api_key
VITE_SLACK_CLIENT_ID=your_slack_client_id
VITE_GOOGLE_CLIENT_ID=your_google_client_id
4. Run the development server
npm run dev
The app will be available at http://localhost:5173.
Design System
MeetMind AI uses a warm beige and brown palette designed to feel calm and professional.
Token	Hex	Usage
Background	#f5f0e8	Page background
Espresso	#3d2b1f	Headers, nav, hero
Accent	#8b5e3c	Buttons, links, active states
Cream	#fffaf4	Cards and surfaces
Muted	#7a6655	Secondary text
Border	#d8c4ac	Card and input borders

Folder Structure
meetmind-ai/
├── public/
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Route-level page components
│   ├── hooks/            # Custom React hooks
│   ├── lib/              # API clients and utilities
│   ├── integrations/     # Supabase and third-party connectors
│   └── main.tsx
├── .env
├── package.json
└── README.md
Roadmap
•	[ ]  Speaker identification in transcripts
•	[ ]  Mobile app (iOS and Android)
•	[ ]  Multilingual transcription support
•	[ ]  Team workspace with shared meeting history
•	[ ]  Analytics dashboard (meeting frequency, task completion rates)
•	[ ]  Microsoft Teams and Zoom native bots
Contributing
Contributions are welcome. Please open an issue first to discuss what you would like to change, then submit a pull request against the main branch.
1.	Fork the repository
2.	Create a feature branch:  git checkout -b feature/your-feature
3.	Commit your changes:  git commit -m 'Add your feature'
4.	Push to the branch:  git push origin feature/your-feature
5.	Open a pull request
License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
Built with care and AI. Questions or feedback? Open an issue or reach out via the repository discussions tab.
