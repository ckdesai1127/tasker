# Action Plan Bowl 🎲

A beautiful, interactive task management app with a crumpled paper bowl UI. Pick random tasks from your bowl, mark them complete, and track your progress!

## 🚀 Live Demo

Your app is now published on GitHub Pages:
**https://ckdesai1127.github.io/tasker/**

## ✨ Features

- 📝 Add tasks to your bowl
- 🎲 Randomly pick tasks from the bowl
- ✓ Mark tasks as complete
- 📜 View completed task history
- 💾 Data persists in browser (localStorage)
- 📊 Auto-save completed tasks to GitHub Issues

## 🔐 GitHub Issues Integration (Optional)

To enable automatic GitHub Issues creation when you complete tasks:

1. Create a **Personal Access Token** on GitHub:
   - Go to GitHub Settings → Developer Settings → Personal access tokens
   - Click "Generate new token"
   - Select scopes: `repo` (full control)
   - Copy the token

2. In the app, open browser DevTools (F12) and run:
   ```javascript
   localStorage.setItem('github_token', 'YOUR_TOKEN_HERE')
   ```

3. Now when you complete tasks, they'll automatically create GitHub Issues labeled `task-completed`

## 📱 How to Use

1. **Add a task:** Type in the input field and click "Add"
2. **Pick from bowl:** Click "🎲 Pick Paper from Bowl" to randomly select a task
3. **Complete task:** Click "✓ Task Completed" to mark it done
4. **Redraw:** Click "🎲 Redraw / Put it Back" to pick a different task (up to 3 times)
5. **View history:** Scroll down to see all completed tasks

## 💾 Data Storage

- **Local Storage:** Tasks are saved in your browser (survives refreshes)
- **GitHub Issues:** Optional - completed tasks can auto-create issues in this repo

## 🛠️ Tech Stack

- Pure HTML/CSS/JavaScript
- No external dependencies
- Mobile-responsive design
- Works offline

## 📄 License

Feel free to use, modify, and share!

---

**Need help?** Check the [GitHub Issues](https://github.com/ckdesai1127/tasker/issues) for completed task logs.
