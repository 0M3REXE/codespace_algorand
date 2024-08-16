# The All-in-One Algorand Codespace

Welcome to the all-in-one Algorand Codespace! This repository is designed to provide you with everything you need to start developing on the Algorand blockchain, whether you're attending a workshop, completing a challenge, or just exploring on your own.

## 🌟 Quick Start Guide

### 🚀 Start with Codespaces
This is the fastest way to get up and running!

### 1. **Fork the Repo:**

To create your own copy of this repository:

1. **Go to the GitHub Repository:**
   - Navigate to the main page which is the current one your on.

2. **Click the "Fork" Button:**
   - In the top-right corner of the page, click the **Fork** button. This will create a copy of the repository under your GitHub account.

3. **Select Your Account:**
   - If prompted, select your GitHub account as the destination for the fork.

4. **Wait for the Forking Process to Complete:**
   - GitHub will take a few moments to create the fork. Once complete, you’ll be redirected to your newly created fork.


2. **Create a Codespace:**


https://github.com/user-attachments/assets/1513fd15-b55a-48e5-8b97-ba128a74fe43


     *Click the image above to watch a quick 15-second video on how to create your Codespace.*
   - Click the green "Code" button at the top right of your forked repo.
   - Select "Create codespace on main".
   - Once your Codespace is fully loaded, run the following command in the terminal:
     ```bash
     sh algorand_setup.sh
     ```

3. **Start Coding:**
   - Open the `main.py` file to start coding and interact with the Algorand blockchain (no smart contracts needed).
   - To start a smart contract/dApp project, run:
     ```bash
     algokit init
     ```

4. **Workshop Follow-Along:**
   - If you're participating in a workshop, the code we’ll be using is available [here](https://github.com/Ganainmtech/python_algokit_demo).

5. **Explore on Your Own:**
   - Use this environment to write your own scripts or modify existing ones.

### 💻 Advanced Setup for Local Development

Prefer a local environment? Follow these steps:

#### 🧰 Prerequisites

- Install Python 3.12 or higher.
- Install [AlgoKit](https://developer.algorand.org/algokit/?utm_source=af_employee&utm_medium=social&utm_campaign=algokit_sarajane&utm_content=download&utm_term=EME).
- Install Docker (for running a local Algorand network).

#### 🔧 Setup Instructions

1. **Fork & Clone the Repository:**


https://github.com/user-attachments/assets/6942cc23-72c1-4d89-a4aa-f2f4fe8fcfe0


     *Watch this video to see how to fork and clone the repository.*
   - Fork this repository to your GitHub account.
   - Clone the repository to your local machine:
     ```bash
     cd [DIRECTORY_OF_YOUR_CHOICE]
     git clone [FORKED_REPO_URL]
     ```

2. **Open in VSCode:**
   - Open the repository with your code editor.

3. **Bootstrap Your Project:**
   - Navigate to the challenge folder.
   - Run the following command to set up your environment:
     ```bash
     algokit project bootstrap
     ```
   - This installs dependencies and generates a `.env` file.

4. **Activate Python Virtual Environment:**
   - Run:
     ```bash
     poetry shell
     ```
   - The virtual environment will automatically activate the next time you open the project.

## 🎓 Workshop Challenges

If you’re taking part in a workshop challenge you can choose to fork and enter codespace or fork and work locally:

1. **Live coding follow along:** 
   - Complete the task provided during the workshop.

2. **Submit Your Answer:**
   - Push your changes to your forked GitHub repository.
   - Create a Pull Request (PR) to the original repository.
   - In your PR, include:
     - What your script achieves. (Optional)

## 📚 Additional Resources

- **Level Up:** Move to a local development environment when you're ready! Check out the [AlgoKit Landing Page](https://developer.algorand.org/algokit/?utm_source=af_employee&utm_medium=social&utm_campaign=algokit_sarajane&utm_content=download&utm_term=EME) for a quick setup guide.
- **Join the Community:**
  - [![Join Algorand Discord](https://img.shields.io/discord/discord_channel_id?logo=discord)](https://discord.com/invite/algorand)
  - [![Follow Algodevs on Twitter](https://img.shields.io/twitter/follow/algodevs?style=social)](https://x.com/algodevs)

## 🏁 Conclusion

This repository serves as both a playground for exploration and a platform for structured learning through workshops and challenges. Whether you're a beginner or an experienced developer, we hope you find this environment useful and engaging. Happy coding!

