<p align="center">
  <img src="/assets/Logo.png" width="150">
</p>

<h1 align="center" style="color:#003366; font-size: 36px; margin-bottom:0;">
  Silver Leaf University – Faculty & Student Portal
</h1>

<p align="center" style="font-size:18px; color:#0059b3; margin-top:4px;">
  Team 4: Modern Research Pioneers
</p>

<p align="center">
  Akshaya Cheruku • Gowri Bhavani Bommareddy • Krishna Chaitanya Bodepudi • Krishna Chaitanya Nizam • Sai Tulasi Akarapu
</p>

---

<div align="center" style="font-size:17px; font-weight:600; margin-bottom:12px;">

[Executive Summary](#executive-summary) •  
[Problem](#problem-context--stakeholder-perspectives) •  
[Insights](#research--insights) •  
[Solution](#proposed-solution) •  
[Architecture](#architecture) •  
[Data](#data-structure) •  
[Dashboard](#dashboard) •  
[Ethics](#ethical--social-considerations) •  
[Outcomes](#outcomes-impact--next-steps) •  
[Team](#team-reflection)

</div>

---

# <span style="color:#003366;">Executive Summary</span>

Silverleaf University is preparing for a major shift in how its faculty operate by introducing AI-powered tools and improved teaching technologies. As the Modern Research Pioneers team, we focused on building a solution that supports faculty with AI while keeping workflows efficient and academically aligned. The **Faculty & Student Portal** provides assignment management, submission tracking, and syllabus-aligned AI assistance.

The solution integrates:
- **Gemini API** for AI Assistant + Feedback Analyzer
- **Local LM Studio AI** for privacy-first deployment
- **Modern frontend** with Next.js, TypeScript, Tailwind, and shadcn/ui

This project demonstrates a scalable, AI-ready academic system that improves faculty productivity, supports ethical AI adoption, and enhances student learning through clear communication and structured feedback.

---

# <span style="color:#003366;">Problem Context & Stakeholder Perspectives</span>

Silverleaf University needs modern, efficient academic workflows. Faculty lack tools that assist with grading, personalized support, and course-aligned content generation. Students expect clearer deadlines, transparent grading, and quick support. Administrators need structured oversight of course assignments and academic processes.

## <span style="color:#0059b3;">Stakeholders</span>

### <span style="color:#008060;">Faculty</span>
- Need help with grading and alignment  
- Want AI tools that support teaching  
- Require time-saving automation  

### <span style="color:#008060;">Students</span>
- Need clear assignment expectations  
- Benefit from faster feedback  
- Rely on structured course guidance  

### <span style="color:#008060;">Administrators</span>
- Manage courses and faculty mapping  
- Need oversight and transparency  

---

# <span style="color:#003366;">Research & Insights</span>

Our research highlights:
- Students actively use AI for learning support  
- AI reduces faculty workload significantly  
- Institutions must adopt AI ethically with transparency, privacy, and fairness  
- Governance frameworks and compliance (FERPA, GDPR) are essential  

Insights gathered from:
- EDUCAUSE  
- Deloitte AI in Education  
- Gartner Peer Insights  
- Ithaka S+R Studies  

---

# <span style="color:#003366;">Proposed Solution</span>

The **AI Faculty Support Portal** provides:

### <span style="color:#008060;">Key Features</span>
- AI-powered Feedback Analyzer (Gemini API)  
- Syllabus-aligned Course Chatbot  
- Assignment creation & posting  
- Student submission portal (PDF uploads)  
- Admin-to-faculty course assignment  
- Faculty AI workspace for content generation  

### <span style="color:#008060;">AI Model Setup</span>
- Gemini API for cloud inference  
- Local LM Studio (Llama models) for private on-device inference  
- No external sharing when executed locally  

---

# <span style="color:#003366;">System Architecture</span>

<p align="center">
  <img src="/assets/architecture.png" width="700">
</p>

### <span style="color:#008060;">Business Architecture</span>
- Supports faculty, student, and admin workflows  

### <span style="color:#008060;">Information System Architecture</span>
- Handles flow between syllabus, assignments, AI, feedback  

### <span style="color:#008060;">Technology Architecture</span>
- Next.js frontend  
- Custom API routes  
- Gemini and LM Studio models  

---

# <span style="color:#003366;">Data Flow Diagram</span>

<p align="center">
  <img src="/assets/data-flow.png" width="700">
</p>

Data flows from:
1. Admin creation of courses  
2. Faculty assignment posting  
3. Student submission  
4. AI analysis (Feedback Analyzer)  
5. Dashboard visualization  

---

# <span style="color:#003366;">Data Structure</span>

<p align="center">
  <img src="/assets/erd.png" width="700">
</p>

### <span style="color:#008060;">Key Entities</span>
- Admin roles  
- Faculty profiles  
- Courses  
- Assignments  
- Submissions (PDFs + extracted text)  
- AI logs  
- Feedback outputs  

---

# <span style="color:#003366;">Dashboard</span>

The dashboard provides:

- Submission status  
- Assignment counts  
- Course analytics  
- AI-generated feedback visibility  

(Add your screenshots below if needed)

---

# <span style="color:#003366;">Project Walkthrough Video</span>

### 🟦 **Option 1 — YouTube Embed**
```html
<iframe width="100%" height="400" 
src="https://www.youtube.com/embed/VIDEO_ID" 
title="Project Explanation" frameborder="0" allowfullscreen>
</iframe>
