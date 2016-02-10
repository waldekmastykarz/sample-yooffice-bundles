# Optimizing Office web apps and add-ins for release with Gulp

When building Office web applications and add-ins there comes the time where they are ready for release. What's good for development however, isn't necessarily leading to best performance. Luckily using Gulp you can pretty easily improve your solution's performance.

This sample illustrates how you can extend an Office add-in generated using the Yeoman Office Generator with the additional optimization tasks.

## Running this sample

1. Clone this repository
1. Register a new web application in your Azure Active Directory
1. Copy the application ID and paste it in the `app/app.config.js` file
1. Upload the `manifest-my-office-project.xml` file to your Office catalog
1. Run the **serve-dist** Gulp task to run the optimized version of the add-in
1. Insert the add-in to an Office document
