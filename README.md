# AI Resume Builder

## Group Members
- Tshilidzi Madzhara  
- Tersh Kgaphola  
- Lucy Shai  
- Linda Hlazo  
- Lebogang Molepo  

---

## Project Overview
**AI Resume Builder** is a modern, full-stack application designed to convert complex career histories into professional, ATS-ready resumes. It goes beyond a simple text editor to act as a high-performance design engine, allowing users to create polished resumes quickly and effortlessly.

The platform emphasizes **speed, reliability, and usability**, offering a *“what-you-see-is-what-you-get”* experience while leveraging **Generative AI** for professional content suggestions.

---

## Key Features
- AI-powered resume generation with real-time preview  
- Safe data handling to ensure data integrity  
- Intelligent syncing between frontend and backend  
- Dual-format export:
  - PDF (high-quality, print-ready)  
  - Word (.docx, editable)  
- Responsive, modern UI/UX  
- Multiple templates tailored to different career goals:
  - ATS-Friendly: optimized for automated resume screening  
  - Creative: bold designs with data visualizations  
  - Modern Professional: balanced layout suitable for most industries  

---

## Tech Stack

### Frontend
- React 18  
- TypeScript  
- Tailwind CSS  
- Vite  

### AI Integration
- Lovable AI (Prompt Engineering)  

### State Management & Data Handling
- TanStack Query (asynchronous data fetching & caching)  
- React Hook Form (form handling)  
- Zod (data validation)  

### Export Tools
- html2pdf.js (PDF generation)  
- DOCX library (Word export)  

### Version Control & Deployment
- GitHub  
- Vercel  

---

## System Architecture & API Flow
The AI Resume Builder communicates with AI services through a secure and structured pipeline:

1. **Data Validation (Zod)**  
   - Ensures user input is correctly formatted before reaching the AI.  

2. **Smart Requests (TanStack Query)**  
   - Handles asynchronous API calls, displays loading states, and retries failed requests.  

3. **JSON-Based Responses**  
   - AI outputs structured JSON, allowing direct mapping to resume sections.  

### Asynchronous Processing
- Users can continue editing while AI generates content in the background.  
- Instant updates to specific resume sections without page reload.  

**Advantages:**  
- No frozen screens  
- Reliable results with minimal formatting errors  
- Safe handling of API keys and user data  

---

## Design & User Experience
- Atomic Design methodology for modular, reusable components  
- Typography:
  - DM Serif Display (headings)  
  - Inter (body text)  
- Real-time resume preview  
- Seamless form validation and feedback  

---

## Export Functionality
- **PDF Export**: Captures exactly what is displayed using html2pdf.js  
- **Word Export**: Editable .docx files for further customization  

---

## Performance & Optimization
- Tree shaking and CSS purging for fast loading  
- Optimized for mobile and low-bandwidth connections  

---

## Future Improvements
- Migration to Next.js for better performance and SEO  
- User accounts with resume saving (Supabase integration)  
- Server-side PDF generation for consistency  
- Enhanced AI personalization  

---

## Deployment
The project was created using Lovable AI, version-controlled on GitHub, and deployed through Vercel.

🔗 **GitHub Repository:** [https://github.com/TershK/apt-aptitude.git](https://github.com/TershK/apt-aptitude.git)  

---

## User Guide
1. **Get Started**: Click the green “Get Started” button on the homepage  
2. **Personal Information**: Enter personal details and professional summary  
3. **Work Experience**: Input job history with real-time preview  
4. **Education**: Add educational background; navigate pages as needed  
5. **Skills & Industry**: Add skills and target industries  
6. **Customize Resume**: Select template, layout, and color  
7. **Export**: Download as PDF or Word document  

---

## Conclusion
AI Resume Builder blends **Generative AI**, **type-safe development**, and **user-centric design** to simplify the resume creation process. It empowers users to present their professional stories with clarity, confidence, and efficiency.

---

## License
This project is for **educational and demonstration purposes**.
