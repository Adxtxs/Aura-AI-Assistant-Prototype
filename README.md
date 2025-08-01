# Aura Health AI: Corporate Wellness Dashboard Prototype

This project is an interactive web application prototype developed using **Python and Dash**. It's designed to fulfill the requirements of the **Product Analyst assignment** to build an AI assistant that enhances both the employee and HR experience in corporate health services.

The application includes two primary user-focused dashboards:
- **Employee Dashboard**: A personal space for employees to explore their benefits, get notifications, book services, and receive personalized wellness suggestions.
- **HR Analytics Dashboard**: A management dashboard for monitoring workforce health trends, analyzing ROI, and generating reports.

---

### Key Features & Insights

#### For Employees (`/employee` view)
The employee dashboard is designed for ease of use and personalized assistance, making health services easy to discover and use.

- **AI Chat Assistant** Enables booking appointments (clinic, video, or lab), explains health benefits in simple terms, and answers contextual questions like *"Which doctor should I see for back pain?"*

- **Personalized Suggestion Cards** Analyzes an employee's visit history to recommend and highlight relevant wellness programs, such as a Mindfulness program for stress-related issues.

- **Benefits Usage Tracker** Simple progress bars provide a clear, at-a-glance view of how much of their annual benefits they have utilized.

- **Health Notifications** The AI assistant can be prompted to set reminders for health checkups or medication, addressing a key requirement for proactive employee engagement.

---

#### For HR & Benefits Teams (`/hr` view)
The HR dashboard provides macro-level insights into workforce health, enabling data-driven decisions.

- **KPI Cards & Interactive Graphs** Visualizes key data like total visits, costs, and common health issues, all of which can be filtered by department.

- **Simulated ROI Table** A clear table breaks down the simulated costs and savings of various wellness programs to help track the value of health benefits.

- **AI Insights Panel & HR Chat Assistant** Summarizes workforce health patterns to recommend targeted wellness initiatives (e.g., *Ergonomics Workshop* for prevalent back pain). The chatbot can also answer aggregate questions like *"What’s our ROI?"*

- **CSV Report Generation** A "Generate CSV Report" button allows HR to easily download filtered data for management reporting.

---

### Technical Stack

- **Backend & Framework**: Python, Dash
- **Data Handling**: Pandas, NumPy
- **Interactive Visualizations**: Plotly Express
- **UI Styling**: Dash Bootstrap Components, Font Awesome

> **Note**: The AI assistant is a **rule-based simulation** created to demonstrate the core product concept and functionality.

---

### How to Run This Project

1.  **Install Dependencies**
    ```bash
    pip install pandas numpy dash dash-bootstrap-components plotly
    ```

2.  **Run the Application**
    ```bash
    python your_file_name.py
    ```

3.  **View in Your Browser** Open `http://127.0.0.1:8052` to see the application running.

---

### Dummy Data Assumptions

- **Employees**: Data for 100 dummy employees is randomly generated with various attributes.
- **Visits**: 2,500 simulated visit records are created across different departments and health concerns.
- **Benefits**: The application assumes benefit limits for different health plans to demonstrate the usage tracker.
- **ROI**: All ROI figures are based on mock values for cost reduction through wellness programs.

> This application does not connect to any real APIs or external databases. All data is generated locally at runtime for demonstration purposes only.

---

### Project Deliverables Overview

- **Aura Health App (`.py`)**: The functional Python Dash application that serves as an interactive prototype.
- **Aura Design Mockups (`.pdf`)**: Visual designs showing the look and feel of the employee and HR dashboards.
- **Aura - Product Outline Presentation (`.pdf`)**: A strategic pitch deck detailing the product vision, features, market analysis, privacy, technical challenges and success metrics.
- **Final Insights (`.pdf`)**: A summary of key takeaways on the market problem, product solution, and competitive landscape.
