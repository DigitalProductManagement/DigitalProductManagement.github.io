# 🚀 Getting Started: Digital Product Management MBA Onboarding Guide

Welcome to the **Digital Product Management MBA** at Estonian Business School! Over the coming semesters, you will transition from thinking like a student to operating like a modern tech industry leader.

In this programme, we believe in **learning by doing**. You won't just study frameworks; you will build real digital products, write living strategies, collaborate asynchronously, and leverage cutting-edge AI tools ("vibe coding", "agenting coding").

To level the playing field, we start our journey using the **"Startup Stack"** centered around GitHub and Discord. Please complete all steps below **before the first day of class**.

> [!TIP]
> **The PM Mindset:** Treat this onboarding process as your very first product assignment. If you run into technical blockers, log them, look for solutions online, or ask your peers in Discord.

---

## 💻 1. Setting Up Your Computer

A product manager’s laptop is their primary leverage tool. Ensure your operating system is fully up to date and that your machine has at least 16GB of RAM to handle multiple browser layers, local AI tools, and code environments simultaneously.

Please download and install the following three foundational applications:

### A. Discord (Our Communication Hub)
We use Discord as our central communication repository for real-time collaboration, peer support, virtual standups, and sharing AI prompts.
1. Go to [discord.com/download](https://discord.com/download) and download the app for your desktop and smartphone.
2. Create an account if you don't have one.
3. Join the official EBS DPM MBA server via the invitation link sent to your personal email.

### B. Visual Studio Code (Your Code & Text Editor)
VS Code is the industry-standard lightweight text and code editor. You will use this to edit documentation, write product strategies in Markdown, and prototype.
1. Go to [code.visualstudio.com](https://code.visualstudio.com/) and download the installer for Mac or Windows.
2. Install the application following the default wizard instructions.

### C. Git (The Version Control Engine)
Git tracks changes in files and coordinates work on those files among multiple people.
* **Mac Users:** Open your terminal (Cmd + Space, type "Terminal") and type `git --version`. If it’s not installed, a prompt will appear asking you to install Xcode Command Line Tools. Click "Install".
* **Windows Users:** Go to [git-scm.com/download/win](https://git-scm.com/download/win) and download the 64-bit Git for Windows Setup. Run the installer and keep the default settings.

---

## 🛠️ 2. Getting Started with GitHub.com

GitHub is where your product's code, strategy, task management, and documentation will live during the Autumn semester.

### Step 2.1: Join GitHub with your EBS E-mail
1. Go to [github.com](https://github.com/) and sign up for a free account.
2. **Crucial:** Use your official `@ebs.ee` student e-mail address to register, or add it as a primary/secondary email in your GitHub Account Settings.
3. Once registered, apply for the **GitHub Student Developer Pack** here: [education.github.com/pack](https://education.github.com/pack). This unlocks free cloud tools, advanced repository features, and access to industry-grade services.

### Step 2.2: Create Your First Repository
A repository (or "repo") is like a digital project folder that stores all your code, strategy documentation, and history.
1. Log into GitHub, click the **`+`** icon in the top right corner, and select **New repository**.
2. **Repository name:** Name it `dpm-learning-reflection`.
3. **Visibility:** Select **Private** (this ensures only you and your chosen collaborators/teachers can see your work).
4. **Initialize this repository with:** Check the box that says **Add a README file**.
5. Click **Create repository**.

### Step 2.3: Invite Teachers as Viewers
To get graded and receive feedback on your assignments, you must grant access to your faculty.
1. Inside your new repository, click the **Settings** tab (the gear icon on the top repository menu).
2. On the left sidebar, click **Collaborators**.
3. Click the green **Add people** button.
4. Type in the GitHub usernames of your module professors (these usernames will be pinned in the Discord server before the first module).
5. Select them and invite them to the repository.

---

## 🔄 3. Your Local-to-Remote Git Workflow

Now, let's connect your local computer to your cloud-based GitHub account so you can do your assignments locally and back them up to the cloud.

### Step 3.1: Clone the Repository to Your Local Machine
"Cloning" means creating a local, working copy of your remote GitHub repository on your computer.
1. On your repository page on GitHub.com, click the green **`<> Code`** button and copy the HTTPS URL (e.g., `https://github.com/your-username/dpm-learning-reflection.git`).
2. Open **VS Code**.
3. Open the Command Palette (`Cmd+Shift+P` on Mac, `Ctrl+Shift+P` on Windows), type **`Git: Clone`**, and press Enter.
4. Paste the repository URL you copied and press Enter.
5. Select a folder on your computer (e.g., your Desktop or Documents folder) where you want the repository folder to live.

### Step 3.2: Make Local Updates and "Push" to Remote
Every time you complete a homework task or modify a file, you follow this exact three-step pipeline: **Add ➡️ Commit ➡️ Push**.

1. In VS Code, open the `README.md` file. Add a line of text: `## My DPM Journey Starts Here`. Save the file (`Cmd+S` / `Ctrl+S`).
2. Click the **Source Control** icon on the left sidebar of VS Code (it looks like a branch with points).
3. You will see your modified `README.md` file. Click the **`+`** icon next to the file name to **Stage Changes** (this runs `git add`).
4. In the message box at the top, type a meaningful comment explaining what you did, e.g., `Update README with intro headline`.
5. Click the **Commit** button.
6. Click **Sync Changes** or **Push** to upload your work back to GitHub.com. Refresh your GitHub browser page—you will see your updates live!

---

## 📝 4. Managing Documentation & Learning Reflections

As a Product Manager, documentation is your superpower. We will use two core features of GitHub to document our thinking and interact as a product team:

### A. The GitHub Wiki & Markdown (`.md`) Files
You will write your strategy assignments, market research, and meeting notes in Markdown. Markdown is a lightweight text formatting language.
* `#` represents a Heading 1
* `##` represents a Heading 2
* `-` or `*` creates bullet points
* `[Text](URL)` creates a hyperlink

Inside your GitHub repository, click on the **Wiki** tab at the top. Here, you can click **Create the first page**. Use this space to write your **Daily/Weekly Learning Reflections** and Sprint Retrospectives.

### B. GitHub Issues (Tracking Blockers and Questions)
Product teams use issues to log bugs, request features, and track tasks. You will use Issues to raise questions, log learning hurdles, and get peer feedback.
1. Go to the **Issues** tab in your repository and click **New Issue**.
2. Give it a clear title, such as `Blocker: Trouble configuring Lovable.ai with Git repo`.
3. In the description, write down your specific question or problem.
4. **Peer Reviews:** When reviewing a classmate's work, you will open an Issue in *their* repository or comment on their existing issues to leave constructive feedback. You can mention them using `@their-username` to trigger a notification.

---

## 🎯 Next Steps Checklist

Before our first weekend session kicks off, make sure you have checked off the following items:

- [ ] I have installed Discord, VS Code, and Git locally.
- [ ] I have joined the EBS Digital Product Management MBA Discord Server.
- [ ] I have a GitHub account linked with my `@ebs.ee` student email.
- [ ] I have created a private repository named `dpm-learning-reflection`.
- [ ] I have successfully cloned the repo, modified the README locally, and pushed it back to GitHub.
- [ ] I am ready to build products!

*See you on Discord and in the first module sprint!*

