🌱 Eco Cycle

Eco Cycle is a web-based platform that promotes sustainable living and environmental awareness. The project aims to empower individuals and communities to adopt eco-friendly habits through intuitive tools, community engagement, and actionable insights.This project aims to bridge the gap between eco-conscious individuals and actionable sustainability efforts by offering a centralized platform that's interactive, informative, and community-driven.


🚀 Features

- ♻️ Track and manage recycling habits
- 🗺️ Google Maps integration to locate nearby recycling centers
- 📊 Visualize environmental impact with personalized data insights
- 🧠 AI-powered sustainability tips (via Replicate.com API)
- 🌐 Offline accessible & mobile-responsive (PWA support)
- 👥 Community-driven eco challenges and tips

## 🛠️ Tech Stack

| Layer       | Technology                  |
|-------------|-----------------------------|
| Frontend    | Next.js, Tailwind CSS       |
| Backend     | Supabase, EdgeDB            |
| Database/API| Google Maps API, Replicate API, PocketBase |
| PWA         | Service Workers, Manifest   |

📸 Screenshots
                                  [Landing Page]
                                  
![Landing Page](https://github.com/user-attachments/assets/f8517ec6-3b17-4176-92e7-2049504ff8bb)

                                  [Map Integration]
                                  
![Map](https://github.com/user-attachments/assets/80753aaa-ae2b-4b50-8332-5f6024952a85)

                                     [Dashboard]
![Dashboard](https://github.com/user-attachments/assets/d89f7682-0d1c-4604-bd35-a825d1c6fbd2)

                    [Leaderboard, Challenges, Recycling Assistant, Activity History]
                    
![Screenshot 2025-06-12 183316](https://github.com/user-attachments/assets/7376b7f3-e00f-4294-ac7e-a2c6eb7ecb43)


🧑‍💻 How It Works

1. **User Registration/Login** (via Supabase authentication)
2. **Location Services** access for showing nearby recycling centers.
3. **Recycling Tracker** allows logging daily/weekly recycled material.
4. **AI Tip Engine** (via Replicate API) generates sustainability tips based on usage.
5. **Dashboard** summarizes individual progress and community challenges.
6. **PWA Support** enables offline use, caching key functionality.

🧪 Run Locally

### ⚙️ Prerequisites

Make sure you have the following installed:

- Node.js (v18 or later)
- npm (v9 or later)
- Git

### 📥 Installation Steps

```bash
# Clone the repo
git clone https://github.com/singhravish486/eco-cycle.git
cd eco-cycle

# Install dependencies
npm install

# Create environment config
touch .env.local

⚙️ Environment Variables
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
REPLICATE_API_TOKEN=your_replicate_api_token
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key

📲 PWA Capabilities

Add to Home Screen
Works offline with cached content
Optimized for mobile & desktop

for any contact
emailid- singhravish2900@gmail.com
insta - ravish_singh486


