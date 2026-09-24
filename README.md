An interactive Power BI dashboard designed to provide actionable business insights. This repository contains the report files, dataset metadata, and configuration details required to run, modify, and deploy the application.

🌟 Key Features
Multi-Page Navigation: Structured reporting environment with distinct pages and view states tailored for varied analytical scopes [cite: 1].

Custom Theming: Utilizes the Fluent2-CY26SU08 and CopilotDefault JSON themes to maintain a modern, cohesive, and accessible user interface 

State Management: Integrated bookmarking system for saving specific filter states, toggling visual visibility, and creating guided analytical narratives 

Rich Visualizations: Employs a variety of dynamic visuals mapped to a structured relational data model and custom metadata .

📂 Repository Structure
This project is version-controlled by exposing the underlying Power BI archive structure:

/Report/StaticResources/ - Contains embedded media and shared theme JSON files.

/Report/definition/pages/ - Stores the JSON definitions for individual report pages and their corresponding visual configurations 

/DataModel/ - Houses the schema, table relationships, and metadata for the underlying datasets .

/SecurityBindings/ - Contains the security definitions and potential Role-Level Security (RLS) configurations.

🚀 Getting Started
Prerequisites
Power BI Desktop

Necessary credentials or gateway access to authenticate the underlying data sources.

Installation
Clone this repository to your local machine:

Bash
git clone https://github.com/your-username/your-powerbi-app.git
Open the main .pbix (or .pbip) file using Power BI Desktop.

If prompted, update the data source credentials via Home > Transform Data > Data source settings.

Click Refresh to load the latest data into the model.

🛠️ Development & Collaboration
To ensure smooth collaboration and proper version control, this repository utilizes Power BI Project (.pbip) files. Saving the report as a .pbip extracts the report and dataset definitions into plain text (JSON) folder structures. This enables proper Git tracking, branching, and pull request reviews without the merge conflicts associated with binary .pbix files.

Ensure the Power BI Project (.pbip) save option is enabled in Power BI Desktop's Preview Features.

Save your changes as a .pbip file.

Commit the resulting folder structure rather than the raw binary file.
