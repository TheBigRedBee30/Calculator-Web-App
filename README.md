Here’s a simple `README.md` for your Calculator Web App to help users set it up and run it using VS Code.

---

Calculator Web App

This is a simple calculator web application built using **Blazor** and **ASP.NET Core**.

Prerequisites

Before running this app, ensure you have the following installed:

- [.NET SDK](https://dotnet.microsoft.com/en-us/download) (Latest version recommended)
- [Visual Studio Code](https://code.visualstudio.com/)
- Git (Optional, for version control)
- Blazor WebAssembly or Server Template** (Included in .NET SDK)

Getting Started

1. Clone the Repository

If you haven't already cloned the repository, open VS Code and run the following command in the terminal:


git clone https://github.com/TheBigRedBee30/Calculator-Web-App.git
cd Calculator-Web-App


2. Open the Project in VS Code

- Open **Visual Studio Code**.
- Click on File > Open Folder and select the Calculator-Web-App folder.

3. Restore Dependencies

Run the following command in the terminal to restore required dependencies:


dotnet restore


4. Build the Application

To ensure everything compiles correctly, run:


dotnet build


5. Run the Application

Start the app using:

dotnet run

This will start a local server, and you should see an output similar to:

Now listening on: http://localhost:5156

6. Open the App in Browser

- Open your browser and go to:  
  `http://localhost:5156`
  _(The port may vary; check the terminal output.)_

7. Using the Calculator

- Navigate to the Calculator page via the sidebar.
- Use the number buttons to enter calculations.
- Click = to compute results.
- Click C to clear input.

8. Debugging & Hot Reload

While the app is running, you can use:

dotnet watch run


This enables hot reload, meaning changes you make in the code will update automatically without restarting.

---

Deployment

To publish the app, run:

dotnet publish -c Release -o publish


This generates the necessary files in the publish directory.

---

Troubleshooting

- App doesn't start?  
  Ensure your .NET SDK is correctly installed by running:

  dotnet --version
  

- Port conflict? 
  Stop any running processes on the same port or change the port by modifying `launchSettings.json`.

- Errors while pushing to GitHub?
  Try running:

  git pull origin main --rebase
  git push origin main
  

---

Contributing

Feel free to submit pull requests or report issues on the GitHub repository.

---

Author
Brady Loggins  

---

Let me know if you need any modifications! 🚀
