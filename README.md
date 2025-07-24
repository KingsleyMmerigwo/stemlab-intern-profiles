# StemLab Intern Profiles

Welcome to **StemLab Intern Profiles**!  
This repository is for all interns to practice Git and GitHub basics by adding their profile.

---

## Steps to Contribute

### 1. Fork and Clone the Repo
1. Fork this repository to your GitHub account.
2. Clone it to your local machine:
   ```bash
   git clone https://github.com/<your-username>/stemlab-intern-profiles.git
   cd stemlab-intern-profiles
2. Create a New Branch
bash
Copy
Edit
git checkout -b add-my-profile
3. Add Your Details
Open interns.md.

Add your details to the table at the end:

markdown
Copy
Edit
| Your Name  | Your School        | Fun Fact Here            | @yourx  | linkedin.com/in/yourusername | facebook.com/yourusername |
4. Commit Your Changes
bash
Copy
Edit
git add .
git commit -m "Added my profile"
5. Push Changes
bash
Copy
Edit
git push origin add-my-profile
6. Create Pull Request
Go to your fork on GitHub.

Click "Compare & pull request".

Add a short description and click "Create pull request".

Resolving Merge Conflicts
When multiple interns edit the same file (like interns.md), merge conflicts may happen.
To fix:

Pull the latest changes from the main repo:

bash
Copy
Edit
git pull origin main
If you see conflict markers like:

diff
Copy
Edit
<<<<<<< HEAD
| Your Row ... |
=======
| Someone Else's Row ... |
>>>>>>> main
Edit the file manually to keep both rows, remove <<<<<<<, =======, and >>>>>>> lines.

Add and commit the fixed file:

bash
Copy
Edit
git add interns.md
git commit -m "Resolved merge conflict"
git push origin add-my-profile
Then create/update your pull request.

Sample Result After Contributions
markdown
Copy
Edit
| Name            | School                | Fun Fact                     | X Username   | LinkedIn                        | Facebook                   |
|-----------------|----------------------|------------------------------|--------------|---------------------------------|----------------------------|
| John Doe        | Bayero University    | I can solve a Rubik's cube!  | @johndoe     | linkedin.com/in/johndoe         | facebook.com/johndoe       |
| Aisha Bello     | ABU Zaria            | I love skydiving.            | @aishabello  | linkedin.com/in/aishabello      | facebook.com/aishabello    |
| Chinedu Eze     | UNILAG               | I speak 4 languages.         | @chinedueze  | linkedin.com/in/chinedueze      | facebook.com/chinedueze    |
