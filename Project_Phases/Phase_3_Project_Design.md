# Phase 3: Project Design

## System Architecture
- **Client Tier:** Dynamic HTML5/CSS3 templates served via Jinja2.
- **Server Tier:** Asynchronous FastAPI backend running on Uvicorn.
- **AI Processing Tier:** Google Generative AI API (Gemini 1.5 Flash) for multimodal parsing.
- **Infrastructure:** Containerized web service running on Render cloud.

## Data Flow
1. User uploads a receipt image via the web client.
2. FastAPI processes the payload and forwards the image to the Gemini multimodal endpoint.
3. Gemini extracts itemized details and spending insights.
4. Jinja2 renders and returns the structured results view to the user.
5.
## Step 1: Brainstorm and Idea Listing

| S.No | Team Member | Idea / Suggestion | Category | Group No. |
|------|-------------|-------------------|----------|-----------|
| 1 | Deepika S | AI-based expense tracking and automatic budget management | Budget Management | 1 |
| 2 | Sharmila B | AI receipt scanning to extract and categorize expenses automatically | AI & Receipt Analysis | 1 |
| 3 | Bhavana G| Personalized budget recommendations and spending insights using AI | Smart Recommendations | 1 |
# Phase 1: Brainstorming & Ideation

- *Date:* 29 September 2026
- *Team ID:* 05
- *Project Name:* PocketSmart AI
- *Maximum Marks:* 3 Marks
