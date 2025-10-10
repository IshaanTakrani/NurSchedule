# NurSchedule
### Built at the TerraHacks 2025 Hackathon.

> Ishaan Takrani
> Venujan Suthakaran
> Kusal Amarathunge
> Thiveyan Nadeswaran 

## AI-assisted scheduling platform 
NurSchedule uses natural language processing (NLP) powered by the Gemini API to interpret user instructions, update staff schedules in a Supabase database, and send automated email notifications to relevant personnel.

## Overview

Scheduling staff shifts in healthcare and other fast-paced environments is tedious and time consuming. It consists of staff having to call each and every staff member individually to "drop" or "pick up" shifts.
NurSchedule streamlines this process by allowing staff to input schedule changes through a portal in plain English, such as:

“Drop my night shift next Thursday”
“Pick up the open day shift on Wednesday, August 13”

Within seconds, NurSchedule:

Parses the instruction using the Gemini LLM

Updates the relevant records in the Supabase PostgreSQL database

Sends automated confirmation emails to affected staff using Nodemaier


🧠 Features

🗣️ Natural Language Input — Uses the Gemini Developer API to process user commands and extract scheduling intents.

🗓️ Automated Schedule Updates — Updates a Supabase PostgreSQL database directly through secure REST endpoints.

📧 Automated Notifications — Sends out personalized email notifications to applicable staff when schedules are modified.

⚙️ Full-Stack Integration — Built with Next.js using TypeScript and Supabase for fast development and maintainability.

⚡ Hackathon-Ready Deployment — Designed, developed, and shipped in 48 hours for TerraHacks 2025.
