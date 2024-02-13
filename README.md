# Working with Existing Projects

### 1. Fork the Main Repository

Fork the main repository by creating a copy of the project in your GitHub account.
  - Original Repository: [revolution-software-club/revolution-software-club.github.io](https://github.com/revolution-software-club/revolution-software-club.github.io)
  - **Note: while giving name by default it will came as `revolution-software-club.github.io` so remove `.github.io` and keep file name as `revolution-software-club`**
  - After forking, your repository will be located at 
  ```bash 
  https://github.com/<your_username>/revolution-software-club
```

### 2. Clone the Repository

Go to code option copy https URL and clone the repository to your local system using the following command:
```bash
  git clone https://github.com/<your_username>/revolution-software-club.github.io.git
```

### 3. Navigate to the Directory

Change directory to the cloned repository:

```bash
cd revolution-software-club
```

### 4. Add Upstream URL

Add the upstream URL to track the original repository:

```bash
git remote add upstream https://github.com/revolution-software-club/revolution-software-club.github.io.git
```

### 5. Verify Remote URLs (Optional)

Optionally, verify remote URLs using:

```bash 
git remote -v
```

### 6. Create a New Branch

Create a new branch to work on your feature.

```bash
git checkout -b feature1
```

### 7. Work on the Feature
Implement your feature or make changes in this branch.

### 8. Stage and Commit Changes

```bash
git add .
git commit -m "Your descriptive message"
```

### 9. Push Changes to Your Branch
Push your changes to your branch on GitHub :

```bash
git push origin feature1
```

# Once setup is done then follow this command till end of your project

### 1. Sync with Main Repository
daily go on the repo click on sync button then come on terminal fire this cmd
```bash 
git pull origin main
```
### 2. Create a New Branch

Create a new branch to work on your feature.

```bash
git checkout -b feature2
```

### 3. Work on the Feature
Implement your feature or make changes in this branch.

### 4. Stage and Commit Changes

```bash
git add .
git commit -m "Your descriptive message"
```

### 5. Push Changes to Your Branch
Push your changes to your branch on GitHub :

```bash
git push origin feature2
```



