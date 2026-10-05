# Jerry Valentine

## Production AI & Data Engineering Portfolio

I design and deploy production AI applications, data platforms, and cloud-native services using Python, Google Cloud, Large Language Models, APIs, and modern data engineering practices.

This portfolio highlights three systems demonstrating applied decision support, investment evaluation, and reusable AI application creation.

Email: jerryevalentine@gmail.com


# Featured Applications

## ODIN — Decision Support System

* 🌐 **Video Demo:** Watch the Odin workflow demonstration:https://youtu.be/jTVuXRZ2mzc
* 📖 **Instructions:** https://odin.instructions.agilesolutionsinc.org/
* 💻 **GitHub Code and Documentation:** https://github.com/JerryValentine2/odin

ODIN is a decision-support system that transforms raw data into actionable insights through a structured **ETL → DEP** process.

**ETL:** Extract → Transform → Load
**DEP:** Describe → Explain → Predict

ODIN prepares and analyzes data using reports, visualizations, summary statistics, correlation, regression, and machine-learning predictive models to help users understand what happened, why it happened, and what is likely to happen next.

The results of the DEP analysis are transmitted to AI, which interprets the analytical results and returns additional insights to help users understand their significance. ODIN also provides an interactive AI chat feature that allows users to ask questions and explore the results conversationally.

**Status:** User tested and ready for use. Independent user testing found the workflow easy to use, the AI analysis clear and useful, and the discussion feature helpful for exploring specific findings.

**Upcoming Features:**
* Expanded user customization of analysis and visualizations.
* Metadata upload for defining dataset columns and providing additional context for analysis.

**Technologies:** Python, Google Cloud, Large Language Models, REST APIs, data analytics, machine learning

--- 

## ARES — Investment Evaluation System

* 🌐 Video Demo: Watch the Ares Investor workflow demonstration: https://youtu.be/iHmND8maYxQ
* 📖 **Instructions:** https://ares.instructions.agilesolutionsinc.org/
* 💻 **GitHub Code and Documentation:** https://github.com/JerryValentine2/ares-investor

**Usage Note:** Ares performs an in-depth analysis using seven independent investor perspectives followed by a synthesized investor-readiness assessment. Analysis may take 30–60 seconds to complete.

ARES evaluates potential investments to determine whether an investment decision is financially sound. It analyzes expected costs, benefits, returns, risks, and financial performance to provide a structured evaluation of whether an investment makes economic sense.

After evaluating a decision in ODIN, a decision that leads to a potential investment can be evaluated further in ARES. ARES determines whether that investment is justified by the underlying financial analysis.

**Status:** UAT tested and validated; customer testing has not yet been completed.

**Technologies:** Python, Google Cloud, Large Language Models, REST APIs, financial analysis, data analytics


## HARMONIA — AI Application Factory

* 🌐 **Video Demo:** https://www.youtube.com/watch?v=IKsp66UEGbU
* 📖 **Instructions:** Forthcoming.
* 💻 **GitHub Code and Documentation:** Forthcoming.

HARMONIA is an evidence-governed AI application factory designed to help minimally trained users turn natural-language requirements into reusable, shareable AI application packages.

The factory creates coordinated agent roles, structured data files, operating instructions, and persistent knowledge artifacts. Applications use Google Drive to retain their definitions, data, and accumulated knowledge across conversations. Initial application packages have been created in approximately one hour, depending on scope and integration requirements.

HARMONIA incorporates **TVDM behavioral contracts** that define agent responsibilities, permitted actions, required evidence, and PASS/STOP conditions. These contracts guide evidence-based execution, traceability, and verification.

**Application Examples:**

* **PDF Organizer:** Organizes PDF metadata and supports conversational searches across a document collection.
* **GCP System Navigator:** Supports system documentation, education, and problem investigation. After generation, the application was independently extended with an MCP connection that successfully listed 129 Cloud Run services and retrieved service configuration details.

The GCP extension demonstrates how generated applications can gain live integration capabilities without returning to the factory.

**Status:** Functional prototype used by its creator to generate and extend application packages. Initial Cloud Run integration demonstrated; independent novice-user testing, automated evaluation, and production validation are forthcoming.

**Upcoming Features:**

* Published walkthrough, setup instructions, and GitHub documentation.
* Independent testing of application creation, initialization, and sharing.
* Expanded automated evaluation and runtime enforcement of behavioral contracts.
* Improved documentation refresh and reconciliation with live system configuration.

**Technologies:** Large Language Models, Markdown agent definitions, Google Drive, CSV/JSON, Model Context Protocol (MCP), Google Cloud Platform integration, TVDM behavioral contracts, systems analysis
