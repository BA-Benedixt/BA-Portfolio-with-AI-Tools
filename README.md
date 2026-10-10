# BA Command Center & Dynamic AI Workspace

A professional, single-file (`index.html`) portfolio workspace and dynamic multi-provider AI gateway designed for Business Analysts, Product Managers, and Technical Architects. It bridges traditional requirement-gathering frameworks with modern client-side generative AI through a dark glassmorphic interface.

---

## Architecture & Design Principles

- **Zero-Dependency Single-File Execution:** Built with pure HTML5, Tailwind CSS via utility styling, and Vanilla JavaScript. It requires no complex build steps, backend servers, or external databases.
- **Client-Side Data Persistence:** All workspace data, project logs, sprint phases, and settings are saved securely within the browser storage (`localStorage`).
- **Bring Your Own Key (BYOK) Model:** The application is provider-agnostic. Billing and rate limits are managed at the provider level, meaning a single API key seamlessly powers standard and higher-tier models without code modification.
- **Intelligent Mock Mode Fallback:** If no API key is provided, the application automatically falls back to a robust mock generator. This ensures recruiters and site visitors can instantly test all analytical workflows offline without entering credentials.

---

## Core Features & Module Breakdown

### 1. Dynamic Multi-Provider AI Gateway
The application features a centralized control panel that supports live generation across multiple leading LLM providers:
- **Google Gemini (AI Studio):** Defaults to `gemini-3.5-flash-lite`, offering a high-throughput, zero-cost developer experience. Also supports frontier Flash and Pro model variants.
- **Anthropic Claude:** Integrates advanced reasoning presets for rigorous technical and business documentation.
- **OpenAI:** Connects standard GPT ecosystem endpoints for general text and requirement generation.
- **Groq:** Provides lightning-fast inference access to open-source powerhouses like Llama.

### 2. Cross-Functional Swimlane Diagramming
Powered by Mermaid.js, the diagram module shifts away from basic sequence messaging to deliver true business process visualizations:
- **Department Subgraphs:** Organizes process steps into distinct role columns (Customer/User, Business Analyst, System/IT, Approver) using structural subgraphs.
- **Standard Process Symbols:** Incorporates precise flowchart shape syntax including start/end ovals (`([Start])`), process rectangles (`[Task]`), decision diamonds (`{Decision?}`), and document outputs.
- **Cross-Lane Handoffs:** Maps conditional routing between lanes (e.g., `-->|Yes|`, `-->|No|`) and supports direct image export (PNG/SVG).

### 3. Business Analysis Toolsuite
- **User Story & Gherkin Generator:** Enforces INVEST principles to produce structured user stories accompanied by Behavior-Driven Development (BDD) acceptance criteria, edge case lists, and business value metrics.
- **UAT Test Case Matrix:** Automatically parses requirements into executable test tables categorized by Positive, Negative, and Boundary paths, complete with pass/fail tracking and CSV export capabilities.
- **Multi-Screen Wireframer:** Renders side-by-side SVG wireframes illustrating both a primary layout view and a corresponding modal interaction window, supporting direct image downloads.

### 4. Dashboards & Delivery Tracking
- **Career Project Portfolio (Dashboard 1):** An interactive register tracking delivered enterprise projects across major companies and platforms, featuring dynamic status filters and real-time Chart.js analytics.
- **Sprint Tracker (Dashboard 2):** A 4-phase agile delivery timeline (Discovery, Sprint 1, Sprint 2, Release) that monitors documentation milestones, target dates, and completion metrics.

---

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/BA-Benedixt/your-repo-name.git](https://github.com/BA-Benedixt/your-repo-name.git)
