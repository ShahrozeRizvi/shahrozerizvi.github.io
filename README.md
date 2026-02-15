# shahrozerizvi.github.io

Personal portfolio of Shahroze Rizvi — Product Evangelist, Automation Architect, AI Builder & Vibe Coder.

## 🚀 Setup (One Time)

1. Create a GitHub repo named exactly: `shahrozerizvi.github.io`
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. Your site will be live at: `https://shahrozerizvi.github.io`

## ➕ Adding a New Project

Open `index.html` and find the `const projects = [...]` array (around line 380).

Add a new object to the array:

```js
{
  name: "Your Project Name",
  category: "automation",   // automation | ai | product | vibe
  desc: "What it does and why it matters. Keep it 2-3 sentences.",
  impact: [
    { value: "7hrs", label: "Saved/week" },
    { value: "100%", label: "Automated" }
  ],
  tags: ["Make.com", "Slack", "Whatever tools you used"],
  github: "https://github.com/shahrozerizvi/your-repo",  // or null
  live: "https://your-live-link.com"  // or null
}
```

Save the file, push to GitHub, and it appears instantly on your site.

## 🎨 Customising

- **Accent color**: Change `--accent: #00f5c4;` in the `:root` CSS block
- **Bio**: Search for `Product evangelist by day` and update the text
- **Experience**: Find the `<!-- EXPERIENCE -->` section and edit directly
- **Social links**: Find the `.socials` section in the sidebar HTML

## 📁 Structure

```
shahrozerizvi.github.io/
└── index.html   ← Everything lives here. One file, easy to manage.
```
