# React Basic - Azure Static Web App

[Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview) allows you to easily build [React](https://reactjs.org/) apps in minutes. Use this repo with the [React quickstart](https://docs.microsoft.com/azure/static-web-apps/getting-started?tabs=react) to build and customize a new static site.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

![React logo](https://user-images.githubusercontent.com/1741522/104033874-1c1d7c80-5c1c-11eb-8f5c-2d7d2b3a8c8d.png)

[Quickstart guide: Azure Static Web Apps](https://github.com/azure/static-web-apps/blob/master/README.md)

[Getting started guide](https://learn.microsoft.com/en-us/azure/static-web-apps/getting-started?WT.mc_id=APC-StaticWebApps&tabs=react)

Steps:

1. Inside Visual Studio Code, select the Azure logo in the Activity Bar to open the Azure extensions window.
2. Select F1 to open the Visual Studio Code command palette.
3. Enter `Create static web app` in the command box.
4. Select **Azure Static Web Apps: Create static web app...**.
5. Select your Azure subscription.
6. Enter `my-first-static-web-app` for the application name.
7. Select the region closest to you.
8. Enter the settings values that match your framework choice.

   - Framework: Select React
   - Location of application code: Enter /
   - Build location: Enter build

9. Once the app is created, a confirmation notification is shown in Visual Studio Code.
10. To view the website in the browser, right-click the project in the Static Web Apps extension, and select **Browse Site**.
11. To remove the app: In the Visual Studio Code Azure window, return to the Resources section and under Static Web Apps, right-click my-first-static-web-app and select Delete.

## How to associate your app with a custom domain:

1. Azure -> Static Web Apps -> app_neme -> Settings -> Custom Domains
2. **Open Custom Domains**: In the menu, select **Settings** > **Custom domains**.
3. **Add a New Domain**: Click the **+ Add** button.
4. **Enter Domain Details**: Choose **Custom domain on other DNS** and enter your new domain name.
5. **Validate and Propagate**: Azure will validate the domain and propagate the changes. This might take some time depending on your DNS provider's TTL settings.

Once the DNS changes are propagated, your new domain should be associated with your Azure Static Web App.
