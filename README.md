# MFC-Market-Explorer
A single-page interactive dashboard for benchmarking and comparing industrial Mass Flow Controllers (MFCs) from Alicat, Bronkhorst, Brooks, Bürkert, and MKS.

Mass Flow Meter & Controller Benchmarking Dashboard
A comprehensive, interactive single-page application (SPA) for comparing, filtering, and analyzing industrial Mass Flow Controllers (MFCs) and Meters (MFMs). This tool aggregates specifications from major manufacturers into a unified "Command Center" interface.

📋 Project Overview
This project provides a "zero-dependency" dashboard contained entirely within a single HTML file. It allows engineers and procurement specialists to benchmark high-precision flow instruments based on critical specifications such as accuracy, flow range, pressure drop, and response time.

Targeted Manufacturers:

Alicat Scientific

Bronkhorst High-Tech

Brooks Instrument

Bürkert

MKS Instruments

✨ Key Features
🖥️ User Interface & Experience
Dual View Modes: Toggle between a detailed Data Table with sticky headers and a visual Card Grid view.

Dark/Light Mode: Fully responsive theming with an industrial color palette.

Responsive Design: collapsible sidebar ("Command Center") and adaptive layouts for mobile/desktop.

🔍 Search & Filtering
Smart Search: Real-time highlighting of search terms across all specifications.

Multi-Level Filtering: Filter by Manufacturer, Technology (Thermal/Coriolis), and Product Category.

Spec Visibility: Custom toggles to show/hide specific data columns (e.g., "Performance Only" vs "Installation Only" presets).

⚖️ Comparison Tools
Side-by-Side Comparison: Select multiple products to view in a dedicated comparison modal.

Dynamic Statistics: Real-time counters for total, visible, and selected products.

💾 Data Management (Serverless)
CSV Export: Download the current dataset for external analysis.

CSV Import: Upload updated CSV files to dynamically refresh the dashboard data.

Self-Updating: Includes logic to "Save" the current state back to an HTML file (local modification).

🛠️ Technical Stack
Core: Semantic HTML5

Styling: CSS3 with CSS Variables (:root), Flexbox, and CSS Grid.

Logic: Vanilla JavaScript (ES6+).

Dependencies: None. Runs directly in the browser.

🚀 Usage
Download: Clone the repo or download the index.html file.

Run: Open index.html in any modern web browser (Chrome, Firefox, Edge, Safari).

Data Update: To update specifications, use the "Upload CSV" button within the interface.

📊 Specifications Covered
The dashboard tracks over 20 distinct specifications, including:

Performance: Flow Range (Min/Max), Accuracy, Repeatability, Turndown Ratio, Response Time.

Mechanical: Operating Pressure, Temperature, Leak Integrity, Valve Type.

Electrical: Power Supply, Communications (Analog, EtherCAT, Profinet, Modbus, etc.).

Compliance: Hazardous Area Certifications, IP Ratings.
