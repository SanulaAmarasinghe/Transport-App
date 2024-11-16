# Transport Request Management App

## Overview
The Transport Request Management App is a PowerApps-based solution designed to streamline transport request management within an organization. It enables users to submit transport requests, specify locations and stops, and send automated notifications. The app integrates with a SharePoint list for data storage and uses Power Automate to handle automatic reminder emails.

---

## Features
- **User-Friendly Form**: Capture essential transport details, including:
  - Name and Department
  - Date and Time
  - Start ('From') and End ('To') locations
  - Additional stops
  - Advance Payment details (if applicable)
- **Automated Email Notifications**:
  - Notify relevant parties of new requests via PowerApps.
  - Send reminder emails 2 hours before scheduled transport times using Power Automate.
- **Data Storage**:
  - Submit requests to a SharePoint list for easy access and reporting.
- **Dynamic Fields**:
  - Location suggestions for 'From' and 'To' fields.
  - Conditional logic for advance payment details.
- **Stop Management**:
  - Add multiple stops to transport routes.

---

## Technology Stack
- **Microsoft Power Apps**:
  - User Interface and Logic
- **SharePoint**:
  - Backend for data storage
- **Office 365 Outlook Integration**:
  - Email functionality
- **Power Automate**:
  - Automation of reminder emails

---

## How It Works
1. **Submit Request**:
   - Users fill out the form with required details.
   - Data is stored in a SharePoint list.
2. **Email Notification**:
   - Upon submission, an email is sent to the designated recipient(s) through PowerApps.
   - Advance payment requirements, if applicable, are included.
3. **Reminder**:
   - Power Automate triggers a reminder email 2 hours before the scheduled time.
4. **Add Stops**:
   - Additional stops can be added to transport routes.

---

## Benefits
- Simplifies transport management processes.
- Reduces manual errors with automated notifications.
- Provides real-time data visibility via SharePoint.
- Saves time with automated workflows using Power Automate.

---

## Future Enhancements
- Integration with Power BI for advanced reporting.
- GPS-based route optimization.

---

