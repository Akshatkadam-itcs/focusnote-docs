### 🛠️ Git Push Troubleshooting

**[Git Push Failing?]**  
→ No → ✅ Check another issue  
→ Yes 👇

**1. Run:**  
```bash
git push origin master

**2. Error:**  

Did you get:

error: failed to push some refs to 'origin'

If No → ✅ Check branch/token issues
Yes 👇

**3. Pull Before Push:**

git pull origin master --no-rebase

**4. Merge screen appears?:**

→ No → Try pushing again
→ Yes 👇

Write commit message and save (in terminal screen)

**4. Now push again:**

git push origin master

**5. Worked?:**

→ Yes → ✅ Done!
→ No → Check:

- Are you pushing to the correct branch?
- Is the remote URL set correctly?
- Is your auth token valid?





