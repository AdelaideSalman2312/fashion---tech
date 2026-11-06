# Title : Fashion Smart Thought Wheel 

An intelligent, human-centered fashion-tech system that treats personal style as an HCI, computer vision, and wardrobe knowledge graph problem rather than a generic recommender.




<img width="1000" height="1490" alt="wardrobe_experience" src="https://github.com/user-attachments/assets/d912995c-a9d7-4978-9752-d9a247676313" />


# How to Quickstart

**1. Start the Backend Intelligence Engine**
Open a terminal and run:

*cd backend*

*python -m uvicorn main:app --reload --port 8000*

Interactive API Documentation (Swagger UI): http://localhost:8000/docs

System Health Check: http://localhost:8000/

**2. Start the Interactive Frontend Client**
In a second terminal window, run:

*cd frontend*

*npm run dev*

Web Application: http://localhost:5173

# Syncing the Notion Wardrobe
To connect the  existing Notion closet database to the knowledge graph engine:

1. In Notion, open your Wardrobe Database table view.
2. Click the ••• options icon in the top-right corner.
3. Select Export $\rightarrow$ set format to Markdown & CSV.
4. Launch The Thought Wheel web application and navigate to Spoke 4 (Your Closet).
5. Click "Choose Notion CSV File" and upload your exported
6. The NetworkX backend graph engine will automatically extract garment categories, silhouettes, fabric composition blends, and sensory comfort scores to construct your personal wardrobe graph.

# Design Philosophy

   **Minimalist Editorial Vector Sketch** : Uses architectural, lightweight 1.3px line-art vectors inspired by high-fashion technical flats (MediaPipe / HTML5 Canvas). Provides full dynamic body proportions without heavy 3D mesh rendering or WebGL lag.

   **Tactile Pixel-Art Micro-UI** : Retro physical-style stamps used exclusively for deliberate tactile feedback during style reasoning ("Why?" evaluation stamps: Craft, Silhouette, Movement, Weirdness, and Sensuality).

##  Tech Stack Summary

| Layer | Technologies |
| :--- | :--- |
| **Backend Core** | Python 3.13, FastAPI, NetworkX, Pydantic v2 |
| **Frontend Framework** | React 19, Vite, Tailwind CSS |
| **Computer Vision / Canvas** | HTML5 Canvas API, MediaPipe Pose |
| **Data Synchronization** | Notion API / CSV Parser, Pandas |
   


