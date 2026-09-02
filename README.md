# Lesley Nkateko Chauke - Software

🔗 **Live Site:** [https://professionalpersonalportfolio.netlify.app/](https://professionalpersonalportfolio.netlify.app/)

Visit the link above to view and use the website directly — no installation required.

\---

## Opening This Project Locally

This project should be opened with **Visual Studio** (not Visual Studio Code).

To open it:

1. Open **Visual Studio**.
2. Go to **File > Open > Folder...**
3. Select this project folder (the one containing `package.json`).

\---

## Running the Project

Once the folder is open in Visual Studio, follow these steps to run it on your machine:



1. **Open a terminal.**

Go to `View > Terminal` in Visual Studio to open the built-in terminal panel.

2. **Install the dependencies.**
In the terminal, run:

```
   npm install
   ```

   This downloads all the packages the project needs (React, Vite, TypeScript, etc.). This may take a minute or two.



3. **Start the development server.**
Once installation finishes, run:

```
   npm run dev
   ```

4. **Open the app in your browser.**
The terminal will display a local address, typically:

```
   http://localhost:5173/
   ```

   Open that link in your browser to view the app running locally.



5. **Stop the server.**
When you're done, click into the terminal and press `Ctrl + C` to stop the dev server.

\---

## Notes

* Do **not** use the green "Run" (▶) button in Visual Studio — this project runs through the terminal commands above, not through Visual Studio's built-in run/debug feature.
* If you run into a `npm install` permissions error in PowerShell, run this once in the terminal:

```
  Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
  ```

* **Disable your ad blocker** in whichever browser you use to view `http://localhost:5173/`. Ad blockers (e.g. Brave Shields, uBlock Origin) can block the local dev files from loading, resulting in a blank page. Turn off the ad blocker/shields for `localhost` specifically before opening the link.

