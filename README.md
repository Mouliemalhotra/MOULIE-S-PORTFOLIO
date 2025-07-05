# Moulie Malhotra - Portfolio

A modern, responsive portfolio website showcasing AI/ML engineering projects, data science work, and professional achievements.

## 🌟 Live Demo

Visit the live portfolio: [https://yourusername.github.io/moulieportfolio1](https://yourusername.github.io/moulieportfolio1)

## 🚀 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Optimized for all device sizes
- **Interactive Elements**: Mouse trail effects, floating animations, and hover interactions
- **Multilingual Greeting**: Rotating greetings in multiple languages
- **Project Showcase**: Detailed project cards with tech stacks and achievements
- **Hackathon Victories**: Highlighted competition wins and achievements
- **Certifications**: Professional credentials display
- **Contact Integration**: Direct links to email, phone, and social profiles

## 🛠️ Tech Stack

- **Framework**: Next.js 14
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **UI Components**: Radix UI + shadcn/ui
- **Icons**: Lucide React
- **Deployment**: GitHub Pages

## 📦 Local Development

1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/yourusername/moulieportfolio1.git
   cd moulieportfolio1
   \`\`\`

2. **Install dependencies:**
   \`\`\`bash
   npm install
   \`\`\`

3. **Run the development server:**
   \`\`\`bash
   npm run dev
   \`\`\`

4. **Open [http://localhost:3000](http://localhost:3000) in your browser.**

## 🚀 Deployment to GitHub Pages

This portfolio is configured for automatic GitHub Pages deployment:

### Initial Setup

1. **Create a new GitHub repository** named `moulieportfolio1`

2. **Update the repository name** in `next.config.js` and `package.json` if different

3. **Push your code:**
   \`\`\`bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio setup"
   git branch -M main
   git remote add origin https://github.com/yourusername/moulieportfolio1.git
   git push -u origin main
   \`\`\`

### Enable GitHub Pages

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select **GitHub Actions**
4. The workflow will automatically trigger on the next push

### Automatic Deployment

- Every push to the `main` branch triggers automatic deployment
- Build status can be monitored in the **Actions** tab
- Site will be available at: `https://yourusername.github.io/moulieportfolio1`

## 📁 Project Structure

\`\`\`
├── app/
│   ├── globals.css          # Global styles
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Main portfolio page
├── components/
│   ├── ui/                  # shadcn/ui components
│   ├── animated-background.tsx
│   ├── floating-elements.tsx
│   ├── mouse-trail.tsx
│   └── multilingual-greeting.tsx
├── .github/
│   └── workflows/
│       └── deploy.yml       # GitHub Actions workflow
├── next.config.js           # Next.js configuration
├── tailwind.config.ts       # Tailwind CSS configuration
└── package.json             # Dependencies and scripts
\`\`\`

## 🎨 Customization

### Personal Information
Update the following in `app/page.tsx`:
- Name and title
- Contact information
- Projects and achievements
- Skills and technologies
- Social media links

### Styling
- Modify colors in `tailwind.config.ts`
- Update animations in component files
- Customize layout in `app/globals.css`

### Content Sections
- **Projects**: Add/edit project details
- **Skills**: Update technical skills
- **Hackathons**: Include competition achievements
- **Certifications**: Add professional credentials

## 🔧 Configuration Files

### next.config.js
Configured for static export and GitHub Pages:
- `output: "export"` for static generation
- `basePath` and `assetPrefix` for GitHub Pages routing
- Image optimization disabled for static export

### GitHub Actions Workflow
Automated deployment pipeline:
- Builds Next.js application
- Exports static files
- Deploys to GitHub Pages
- Runs on every push to main branch

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Performance Features

- **Static Generation**: Pre-built pages for fast loading
- **Image Optimization**: Optimized images for web
- **Code Splitting**: Automatic code splitting by Next.js
- **CSS Optimization**: Tailwind CSS purging for minimal bundle size

## 📧 Contact

- **Email**: mouliemalhotra2004@gmail.com
- **LinkedIn**: [moulie-malhotra](https://www.linkedin.com/in/moulie-malhotra)
- **GitHub**: [Mouliemalhotra](https://github.com/Mouliemalhotra)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ using Next.js and deployed on GitHub Pages**
\`\`\`

```text file="LICENSE"
MIT License

Copyright (c) 2024 Moulie Malhotra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
