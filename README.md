# App Service PHP WebJobs QuickStart

Getting started with Azure App Service WebJobs using PHP. Deploy and run your first PHP WebJob on App Service. This WebJob outputs the current time to the console.

### Prerequisites
You need to have an App Service Plan and Web App using PHP 8.4 to run this application.

### Running the App
After cloning the repo, create a zip archive of run.sh and webjob.php, for example, zip webjob.zip run.sh webjob.php. Then upload this zip to your App Service Web App under Settings > WebJobs > Add. After naming your WebJob and choosing Scheduled or Continuous, you can run the WebJob manually and inspect the logs to ensure it ran properly.
