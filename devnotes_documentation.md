 DevNotes - Developer Blog Platform

A modern, responsive, developer-focused blogging and technical notes platform built with HTML5, Tailwind CSS, and FontAwesome icons. Designed with a sleek Dark Mode aesthetic inspired by modern IDEs and developer tools.

 Project Structure

devnotes/
├── index.html        # Home Page (Blog feed & featured content)
├── dashboard.html    # User Dashboard (Analytics & post management)
├── create-blog.html  # Create / Edit Blog Post Editor
├── login.html        # User Login & Authentication Page
└── register.html     # Developer Registration & Onboarding 

 Navigation Routing

All 5 pages share the same navigation bar:

1. Home → `index.html`
  Featured articles, technical tags, and community posts.

2. Dashboard** → `dashboard.html`
  Overview of user stats, published posts, drafts, and actions.

3. Create_Blog → `create-blog.html`
  Page to write a new technical article.

4. Login → `login.html`
  Sign in form for existing users.

5. Register → `register.html`
  Account registration form for new users.



Features

1. Dark Theme Palette: Custom developer-friendly dark theme (`#0D1117` background, `#161B22` cards, `#58A6FF` accent blue).
2. Responsive Mobile Menu: Slide-down navigation drawer for mobile and tablet devices.
3. Interactive Forms: Form submission handlers and client-side password matching logic included via JS.
4. Developer UI Elements: Code/Terminal style typography powered by Google Fonts (`JetBrains Mono` and `Inter`).


 Tech Stack & CDN Dependencies

1. HTML5: Semantic markup structure.
2. Tailwind CSS: Responsive layout & utility styling via CDN (`https://cdn.tailwindcss.com`).
3. FontAwesome 6.4: Icon library for developer symbols and UI actions (`https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`).
7. Google Fonts:** `Inter` for body text and `JetBrains Mono` for code/navigation elements.

---

 How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/mominaweb-design/Devnotes_blog.git
   ```
2. Open the project folder:

   ```bash
   cd Devnotes_blog
   ```
3. Open `index.html` in any browser (Chrome, Firefox, Edge, Safari).

4. Or use a local server such as **Live Server** in VS Code:

   ```bash
   npx live-server .
   ```

 Author

 Momina 

1. GitHub: [@mominaweb-design](https://github.com/mominaweb-design)
