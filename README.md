# ✨ Luxe Aura | Soft Life Marketing Studio

> *The Ultimate AI-Powered Creative Suite for High-End Beauty, Skincare, and Lifestyle Branding.*

Luxe Aura is a specialized, multimodal AI application designed to democratize high-end
creative direction. Built for the **Soft Life** aesthetic, it allows influencers,
consultants, and boutique brands to generate professional-grade marketing assets —
from cinematic model variations to cohesive Instagram carousels — using only a
smartphone and the power of Google Gemini AI.

---

## 🔗 Live App

[View Luxe Aura Live](https://aistudio.google.com/apps/6dbb3094-b0c8-4353-a9f0-40303a485a54?fullscreenApplet=true&showPreview=true&showAssistant=true)

---

## 🚀 Core Systems & Studio Modes

Luxe Aura is divided into five high-performance Studio Engines, each targeting a critical pillar of modern digital marketing:

### 1. 🪞 Model Studio — The Avatar Engine
Transform simple portraits into high-fashion editorial assets.
- **Avatar Variations** — Generate high-end Soft Life variations of a model's likeness
- **Angle Variations** — Intelligently re-render the subject from different cinematic perspectives
- **Director's Cut** — Let the AI take full creative control to produce Vogue-style artistic interpretations

### 2. 🧴 Product Studio — The Mockup Engine
Elevate raw product photography into professional studio shots.
- **Aesthetic Mockups** — Place products in curated environments (Minimalist Spa, Marble Vanity, Sun-drenched Balcony)
- **Product Variations** — Generate alternative versions of product shots while maintaining brand integrity

### 3. 🤝 Model + Product Studio — The Integration Engine
The most advanced feature of the suite — merging subjects and objects seamlessly.
- **Multimodal Composition** — Upload a model and a product; the AI intelligently composes a scene where the model appears to be interacting with or promoting the product in a luxury setting

### 4. 📱 IG Carousel Studio — The Content Engine
Automate the creation of cohesive, multi-slide social media stories.
- **Thematic Consistency** — Select a theme color and assets to generate a 3–5 slide series that tells a visual story
- **Social Optimization** — Assets generated with correct aspect ratios and aesthetic flow for Instagram

### 5. ✍️ Marketing Copy Studio — The Copy Engine
AI-powered copywriting tailored specifically for the beauty and wellness niche.
- **Context-Aware Captions** — Generates high-converting captions based on product, context (e.g., "New Launch"), and target audience
- **Soft Life Tone** — Copy tuned to sound sophisticated, aspirational, and approachable

---

## ✨ Key Features

- **Multimodal AI Integration** — Leverages Gemini's ability to see images and write creative prompts simultaneously
- **Advanced Tweak Panel** — Fine-tune generations by selecting specific sceneries (Minimalist Spa, Parisian Apartment) and styles (Cinematic, Editorial, Golden Hour)
- **Local History Gallery** — All generated images saved to the browser's IndexedDB for offline-style persistence without a backend
- **One-Click Export** — Download high-resolution assets or copy marketing text directly to clipboard
- **Responsive Design** — Fully optimized for both desktop creative work and mobile on-the-go content creation

### The Soft Life Design System
A custom-engineered UI/UX featuring a warm, luxurious palette:

| Name | Hex | Role |
|------|-----|------|
| Alabaster | `#F8F4EC` | Primary background — light, airy, clean |
| Warm Taupe | `#D0C0B2` | Mid-tone — soft luxury neutral |
| Espresso | `#46352D` | Dark anchor — editorial depth |

Typography: **Playfair Display** (Serif) + **Lato** (Sans)

---

## 🛠️ Tech Stack

| Technology | Description |
|------------|-------------|
| React 19 | Functional components and hooks for robust, type-safe UI management |
| TypeScript | Strict typing across AI schemas and application state |
| Vite 6 | Near-instantaneous HMR and optimized production builds |
| Google Gemini API | Multimodal AI engine — text + image (`@google/genai`) |
| Tailwind CSS | Custom Soft Life design system |
| IndexedDB | Local browser storage for generation history via custom `db.ts` service |
| Lucide React | Clean, consistent, professional iconography |
| Playfair Display + Lato | Editorial serif and clean sans-serif typography pairing |

---

## 📖 How to Use

1. **Choose Your Studio** — Select a mode from the sidebar (Model, Product, Carousel, etc.)
2. **Upload Source Assets** — Provide base images (portraits or product shots)
3. **Configure the Vibe** — Open the Tweak Panel to select your scenery and style
4. **Generate** — Hit Generate. The AI processes the multimodal request
5. **Review & Refine** — View results in the studio or gallery. Use Tweak to iterate
6. **Deploy** — Download images and copy marketing text for social media

---

## 🎯 Target Market

| Audience | Use Case |
|----------|----------|
| Beauty Consultants | High-end personal branding for Farmasi, Mary Kay, or Sephora consultants |
| Skincare Brands | Professional product mockups without the cost of a studio shoot |
| Lifestyle Influencers | Maintaining a consistent Soft Life aesthetic across all social channels |
| DTC Marketing | Rapidly prototype ad creatives and social media carousels |

---

## 🏗️ Architecture Notes

- **Multimodal Prompting** — Constructs complex System Instructions that guide the AI to maintain specific lighting, skin textures, and luxury brand standards
- **Base64 Processing** — Images handled as Base64 generative parts for low-latency communication with the Gemini API
- **State Management** — Uses React's `useState` and `useRef` for a highly responsive, app-like feel
- **Data Persistence** — IndexedDB via custom `db.ts` service ensures generation history survives sessions without a backend

---

## 📦 Installation & Setup

### Prerequisites
- Node.js (v18 or higher)
- A Google AI Studio API Key — get one free at [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)

### Clone & Install

```bash
git clone https://github.com/quillein/luxe-aura.git
cd luxe-aura
npm install
```

### Environment Variables

```env
GEMINI_API_KEY=your_api_key_here
```

### Run Development Server

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

---

*Developed with ❤️ for the Soft Life community.*
