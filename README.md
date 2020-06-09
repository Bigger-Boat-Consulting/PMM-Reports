# PMM-Reports
This repository contains three add-on reports for the Salesforce.org Program Management Module (PMM). These reports are designed to help front-line staff (case managers, program managers, etc.) track their service deliveries with clients:
1. <b>My Service Deliveries Last Month</b>. This report provides front-line staff with a list of services they delivered to clients sorted by date. This can help with time tracking or workload management. Report notes:
<ul>
<li>As configured, this only shows service deliveries from last month.</li>
<li>The running user of the report is the owner of the service delivery records as this report only shows “My Service Deliveries”</li>
<li>The timeframe for the report can be changed via a filter</li>
  </ul>

2. <b>My Services by Client Last Month</b>. This report lets front-line staff see what services they have delivered to clients, grouped by client. Report notes:
<ul>
<li>As configured, this only shows service deliveries from last month.</li>
<li>The running user of the report is the owner of the service delivery records as this report only shows “My Service Deliveries”</li>
<li>The timeframe for the report can be changed via a filter</li>
  </ul>

3. <b>My Service Deliveries by Program/Client</b>. This report can help front-line staff see what services they have delivered, grouped by program and client in this month and last month. Report notes:
<ul>
<li>As configured, this only shows service deliveries from this month and last month.</li>
<li>The running user of the report is the owner of the service delivery records as this report only shows “My Service Deliveries”</li>
<li>The timeframe for the report can be changed via a filter</li>
  </ul>

Requirement: The Salesforce.org Program Management Module must be installed before installing these reports. The PMM can be installed at: https://install.salesforce.org/products/program-management

To install in a production or sandbox environment, click on this button (step by step instructions below):

<a href="https://githubsfdeploy.herokuapp.com?owner=Bigger-Boat-Consulting&amp;repo=PMM-Reports">
  <img src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png" alt="Deploy to Salesforce" />
</a>

# Step by step installation instructions

1. Click the "Deploy to Salesforce" button above

2. Choose the environment (Production/Developer or Sandbox) you want to install the reports into. We recommend installing in a sandbox first. Leave the other fields as they are. Click "Login to Salesforce"

![Choose environment](https://biggerboatconsulting.com/wp-content/uploads/2020/06/Choose_the_environment.png)

3. Login in to Salesforce

![Login](https://biggerboatconsulting.com/wp-content/uploads/2020/06/Salesforce-login.png)

4. Confirm it's targeting the correct environment and then hit "Deploy"

![Deploy](https://biggerboatconsulting.com/wp-content/uploads/2020/06/Ready_to_deploy.png)

5. Deployment will begin. When it's complete the screen will update with the status

![Deploy Complete](https://biggerboatconsulting.com/wp-content/uploads/2020/06/Deploy_complete.png)

6. Close the window and go to your Salesforce environment to confirm the installation of the reports in the Program Managment Reports folder

Please report any issues to **info [at] biggerboatconsulting [dot] com**
