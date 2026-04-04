Security Policy for Golden Timer

1. Supported Versions

Golden Timer is a client-side web application. Because it is a standalone tool, we only provide security updates for the most recent version available in the repository.

Version

Supported

Latest

:white_check_mark:

< 1.0

:x:

2. Our Security Philosophy

The Golden Timer is designed with Privacy by Design. Our security model is based on isolation:

Zero Server Interaction: The application does not communicate with any external servers. All calculations and timing logic occur strictly within your browser's memory.

No Data Visualization: As the developer, I have no visibility into your data. Your equipment IDs, staff names, and cycle measurements never leave your device.

Local Storage Only: Data is stored in your browser's temporary memory during a session. If you refresh the page without exporting, the data is wiped for your protection.

No Tracking: There are no cookies, no ads, and no third-party tracking scripts (like Google Analytics) included in the application.

3. Reporting a Vulnerability

If you discover a security vulnerability or have concerns about the data handling logic, please help us keep the community safe.

How to Report:

Private Message: Contact me directly via LinkedIn to discuss the findings.

GitHub Issues: If the issue does not involve sensitive data leaks (as the app has no database), you may open a GitHub Issue in this repository.

Please do not include any of your own industrial process data in your report.

4. User Responsibilities

While the app is secure by design, users should follow these best practices:

Device Security: Ensure your mobile device or laptop is password-protected, as the exported CSV files are stored in your local "Downloads" folder.

Clear Session: Use the "Reset All" or "Clear Data" buttons if you are using the tool on a shared or public terminal.

Secure Sharing: When using the "Share Report" feature, ensure you are sending the data through encrypted channels (e.g., corporate email or secure messaging).

5. Disclaimer

Educational Purpose Only: This application is provided "as is" for educational and productivity-enhancement purposes. While every effort is made to ensure data integrity, the developer is not responsible for any data loss, hardware failure, or business decisions made based on the measurements provided by this tool.

Developed by Golden Michael
