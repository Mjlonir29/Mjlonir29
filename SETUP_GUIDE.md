# 🚀 2-Minute Quick Setup Guide for your GitHub Profile

Follow these simple steps to activate your new custom front page on GitHub:

---

### Step 1: Create your Special GitHub Repository
1. Go to GitHub and click **New Repository** (or open: `https://github.com/new`).
2. Set the **Repository name** to match your exact GitHub username:
   ```text
   Mjlonir29
   ```
3. GitHub will show a special banner:
   > *"You found a secret! `Mjlonir29/Mjlonir29` is a special repository that you can use to add a `README.md` to your GitHub profile."*
4. Ensure the repository is set to **Public**.
5. Check the box **"Add a README file"** (or leave it unchecked if you plan to push from git).
6. Click **Create repository**.

---

### Step 2: Add the Custom `README.md`
1. Open the created `Mjlonir29/Mjlonir29` repository.
2. Replace or paste the contents of [`github-profile/README.md`](./README.md) into the `README.md` file of that repository.
3. Click **Commit changes**.

---

### Step 3: (Optional) Activate the Contribution Snake Game Animation
To have the snake game automatically animate and eat your GitHub contribution grid:

1. Inside your `Mjlonir29/Mjlonir29` repo, create the directory structure:
   `.github/workflows/`
2. Create a file named `snake.yml` inside `.github/workflows/` and paste the contents from [`github-profile/.github/workflows/snake.yml`](./.github/workflows/snake.yml).
3. Commit the file to the `main` branch.
4. Go to the **Actions** tab in your repository, click on **Generate Snake Animation**, and click **Run workflow**.
5. Once it completes (takes ~30 seconds), your profile will display the live animated snake eating your contribution dots!

---

### Step 4: Personalize Any Links
Open your `README.md` to update:
- Your LinkedIn URL (`https://linkedin.com/in/your-username`)
- Your contact email (`mailto:your-email@example.com`)
