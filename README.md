# **Scripted_Insights** (**Automated Reporting with Google Apps Script, Gmail, G-Sheets, and Looker Studio**)
Google Apps Script projects designed to automate data workflows and generate live-updating reports. These scripts highlight my expertise in streamlining report generation, automating processes, and delivering actionable insights. Proficient in data management, automation, and reporting solutions to drive business intelligence and decision-making.

## **Description**

This repository contains Google Apps Script projects designed to automate data workflows and reporting, leveraging the power of Gmail, Google Sheets, and Looker Studio. By automating repetitive tasks, these scripts enable the seamless extraction and transformation of data, leading to more efficient reporting processes and timely delivery of insights.

Using **Gmail**, the scripts can automatically parse emails for key information and trigger actions such as sending notifications or updating Google Sheets with incoming data. This integration allows for real-time updates based on emails received, eliminating manual data entry and reducing human error. Google Sheets serves as the central hub for data storage and manipulation, with the scripts performing complex transformations to organize and analyze the data.

Once the data is structured in **Google Sheets**, it is directly connected to **Looker Studio** to generate live-updating dashboards. This pipeline enables automated visual reporting, providing users with a clear, real-time view of data insights without the need for manual updates. Together, these tools create a powerful system for automating data analysis and reporting, delivering insights that drive decision-making.

---

## **Getting Started**

To use these Google Apps Script projects, follow the steps below:

1. **Clone the Repository:**  
   Clone this repository to your local environment or directly to your Google Drive.

2. **Set Up Gmail API:**  
   Enable the Gmail API to allow the scripts to automatically parse emails and trigger actions. You’ll need to provide appropriate permissions to access your Gmail account.

3. **Connect to Google Sheets:**  
   Set up your Google Sheets file where the scripts will store, manipulate, and organize data. Ensure the Google Sheets file is linked to the appropriate datasets.

4. **Looker Studio Integration:**  
   Connect your Google Sheets file to Looker Studio to create live dashboards. Follow these steps to link the data sources and generate real-time visualizations.

5. **Set Up Time-Based Triggers:**  
   To automate the script and ensure it runs at scheduled intervals, set up time-based triggers in Google Apps Script. This will allow the script to automatically update Google Sheets and Looker Studio reports without manual intervention. Go to the Apps Script dashboard, select **Triggers**, and create a new time-driven trigger based on your preferred schedule (e.g., daily or hourly).

6. **Run the Script:**  
   Open the script editor in Google Apps Script and run the function to initiate the automated workflows. Make sure the required permissions are granted when prompted.

---

**Note:**  
For a live-updating dashboard, this system works only if a live report with relevant data is sent to your Gmail in alignment with the trigger schedule. The script is configured to search and parse data from the most recent file received via email.

---

## **Usage**

This section highlights the key features and examples of how to use the scripts effectively. The scripts are designed to streamline automated reporting and data management processes, working across Gmail, Google Sheets, and Looker Studio—all free, widely available tools that are encrypted to ensure secure data protection.

1. **Automated Email Parsing:**  
   The script searches your Gmail for the most recent report file sent to a specific email address or matching certain criteria (e.g., subject line). Once identified, it parses relevant data and imports it directly into Google Sheets.

2. **Data Transformation in Google Sheets:**  
   After the report is imported, the script automates data cleaning and transformation steps, preparing it for analysis. This includes organizing rows and columns, removing duplicates, and applying any necessary formatting.

3. **Live-Updated Dashboards in Looker Studio:**  
   Once the data is processed in Google Sheets, it automatically feeds into Looker Studio to generate live-updating visualizations. With time-based triggers, the dashboard remains current and reflective of the latest data without manual intervention.

4. **Customizable Triggers and Workflows:**  
   You can adjust the time-based triggers based on your reporting needs (e.g., daily, weekly updates). Additionally, the script can be customized to handle different types of reports or data sources.

---

## **Benefits**

- All the tools used—Gmail, Google Sheets, Looker Studio, and Google Apps Script—are free, widely accessible, and encrypted for secure data workflows.
- This solution is particularly beneficial for small- to medium-sized organizations that may not have the resources to afford larger platforms like Tableau Server or PowerBI. By leveraging these free tools, organizations can still achieve effective automation and live-reporting without the high cost of larger, enterprise-level platforms.

---

## **Contributing**

We welcome contributions to enhance the functionality of these scripts and improve the overall project. Whether you have suggestions for optimizations, bug fixes, or feature additions, your input is valuable.

1. **Fork the Repository:**  
   Start by forking this repository to your own GitHub account.

2. **Create a New Branch:**  
   For new features or bug fixes, create a new branch with a descriptive name (e.g., `feature-update`, `bugfix-report-parsing`).

3. **Submit Pull Requests:**  
   After making your changes, submit a pull request detailing the changes you’ve made and why they improve the project. Please include relevant documentation for any new features or updates.

4. **Code Style and Guidelines:**  
   Ensure that your code follows proper formatting and includes comments where necessary. We encourage clean, readable code for ease of maintenance and collaboration.

5. **Report Issues:**  
   If you encounter any problems or have suggestions for improvements, feel free to open an issue in the repository. Detailed bug reports and improvement suggestions are appreciated.

---

## **Contact/Support**

If you have any questions, need support, or want to report issues with the project, please use GitHub Issues.

1. **GitHub Issues:**  
   For any bugs, improvements, or feature requests, open an issue in the repository. Detailed reports help improve the project and ensure that any issues are addressed efficiently.

2. **Documentation and Updates:**  
   Keep an eye on the repository for regular updates, as new features and enhancements will be added. Documentation is continuously improved to ensure ease of use.
