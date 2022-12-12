# Wordpress_on_Azure

## Wordpress, and My SQL flexible server deployment using Azure portal

- [Go to Azure portal](https://portal.azure.com/#home)
- Search for wordpress in the search panel
- Enter required informations
- Select your subscription 
- Create a ressource group name or select an existant if your already have one.
- Select the region you would like the ressource to be deploy to
- Enter the web application name 
- Select the hosting plan (Basic, less expensive)
- Enter your login information for Wordpress

    - Note: This will be your username and admin password.
    - We do not need Content delivery network for this project
- Click on create to deploy your Wordpress + Database.

- The username and password for your Database will be auto generated during the deployment.
    - To retrieve this information after the deployment has been concluded, go to application configuration page.
    - This information information may also be displayed ont the last page before Wordpress deployment process.
    
    
- After the deployment has has completed, go to Ressource Group.
    
    
    
    
- Copy the url in the browzer to get the first view of your Wordpress.




    - Note: to access the Wordpress Account by adding the following to "\wp-admin" in front of the Wordpress url displayed int he browzer.
    - You will use the credentials entered before deployement.
    - It is important to know that this deployment also creates MySQL flexible server.
    
## Managing MyQSL flexible server

- Use the following syntax to log into my SQL flexible server:
        - > site name @azurewebsites.net/phpmyadmin 
        
- Get your login credentials here: 
    - On the left panel clock on configuration > application settings
    
- Congratulations, you have successfully deployed Wordpress and SQL flexible server on Azure.
        
