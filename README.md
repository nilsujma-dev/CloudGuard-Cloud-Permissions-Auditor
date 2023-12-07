### "Cloud Account Permissions Audit Tool using Dome9 API"

This GitHub repository presents a Python script for auditing permissions in cloud environments such as AWS, Azure, and GCP. The script uses Dome9 API to gather and analyze permissions data, streamlining cloud security management.

#### Repository Contents:
1. **Cloud Platform Argument Validation**:
   - Ensures valid platform argument ('aws', 'azure', 'gcp') is provided.
2. **Dome9 API Integration**:
   - Utilizes Dome9 API for fetching missing permissions data for specified cloud platforms.
3. **Data Processing with Pandas**:
   - Transforms JSON data into a structured DataFrame.
   - Exports data to an Excel file for comprehensive analysis.

#### Usage Scenario:
This tool is designed for cloud administrators and security professionals to perform comprehensive audits of cloud account permissions.

#### Prerequisites:
- Python environment with Pandas library.
- Dome9 API credentials.

#### Deployment and Development:
- Set environment variables with Dome9 credentials.
- Execute the script to generate a permissions audit report.

#### Security and Best Practices:
- Ensure secure handling of API credentials.
- Regularly update the script to align with the latest cloud platform updates.

This readme provides an overview of the script's functionality, setup, and deployment, emphasizing its role in enhancing cloud account security audits.
