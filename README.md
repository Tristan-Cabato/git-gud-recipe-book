# 🍳 Git Gud Recipe Book

A collaborative Git workshop where teams practice forking, branching, and pull requests by adding recipes to a shared cookbook.

## Quick Start

1. **Fork** this repository to your team's GitHub account
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/git-gud-recipe-book.git
   cd git-gud-recipe-book
   ```
3. **Create a branch** for your team:
   ```bash
   git checkout -b team-YOUR-TEAM-NAME
   ```

## Add Your Recipes

Each team member adds **one recipe**:

1. **Copy** `recipes/sample.html` and rename it to `recipes/your-recipe-name.html`
2. **Edit** your recipe file with your own content
3. **Add** a recipe image to the `images/` folder
4. **Update** `index.html` to link your recipe in the `<ul class="recipe-list">` section:
   ```html
   <li><a href="recipes/your-recipe-name.html">🥧 Your Recipe Name</a></li>
   ```

## Submit Your Work

```bash
git add .
git commit -m "Add team recipes"
git push origin team-YOUR-TEAM-NAME
```

Then create a **Pull Request** on GitHub from your branch.

## Merge Conflicts = Learning!

When multiple teams edit `index.html`, you'll get merge conflicts. Ask your instructor for help resolving them!

## Project Structure

```
├── index.html          # Add your recipe links here
├── styles.css          # Styling (don't edit)
├── recipes/            # Your recipe HTML files go here
├── images/             # Your recipe images go here
└── CONTRIBUTORS.html   # Add your team after PR is merged
```

**Questions?** Ask your instructor! 🙋‍♀️🙋‍♂️