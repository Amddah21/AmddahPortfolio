# Portfolio Website

A modern, responsive portfolio website built with Next.js, TypeScript, and Tailwind CSS. Features smooth animations, dark mode support, and a professional design.

## 🚀 Features

- **Modern Design**: Clean, professional layout with beautiful gradients and typography
- **Responsive**: Fully responsive design that works on all devices
- **Dark Mode**: Automatic dark mode support based on system preferences
- **Smooth Animations**: Beautiful animations powered by Framer Motion
- **Interactive Elements**: Hover effects, smooth transitions, and interactive components
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Featured projects with technology tags and links
- **Skills Section**: Animated progress bars showing skill levels
- **Social Links**: Integrated social media and contact links

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Fonts**: Geist Sans & Geist Mono
- **Icons**: Custom SVG icons

## 📁 Project Structure

```
portfolio/
├── src/
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   └── components/
│       ├── Header.tsx
│       ├── Footer.tsx
│       ├── HeroSection.tsx
│       ├── AboutSection.tsx
│       ├── ProjectsSection.tsx
│       ├── ContactSection.tsx
│       └── AnimatedSection.tsx
├── public/
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd portfolio
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🎨 Customization

### Personal Information

Update the following files with your personal information:

1. **Header.tsx**: Change "Your Name" to your actual name
2. **HeroSection.tsx**: Update name, title, and description
3. **AboutSection.tsx**: Modify the about text and skills
4. **ProjectsSection.tsx**: Replace with your actual projects
5. **ContactSection.tsx**: Update contact information and social links
6. **Footer.tsx**: Update social links and contact information

### Styling

The project uses Tailwind CSS for styling. You can customize:

- Colors in `globals.css`
- Component styles in individual component files
- Responsive breakpoints using Tailwind's responsive utilities

### Projects

To add your projects, edit the `projects` array in `ProjectsSection.tsx`:

```typescript
const projects = [
  {
    id: 1,
    title: 'Your Project Title',
    description: 'Project description...',
    image: '/path/to/image.jpg',
    technologies: ['React', 'Node.js', 'MongoDB'],
    liveUrl: 'https://your-project.com',
    githubUrl: 'https://github.com/yourusername/project',
    featured: true,
  },
  // Add more projects...
];
```

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:

- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

## 🌙 Dark Mode

Dark mode is automatically enabled based on the user's system preference. The design includes:

- Dark color schemes for all components
- Proper contrast ratios
- Smooth transitions between light and dark modes

## 🎭 Animations

The portfolio includes various animations:

- **Page Load**: Staggered animations for content sections
- **Scroll Animations**: Elements animate into view as you scroll
- **Hover Effects**: Interactive hover states for buttons and cards
- **Progress Bars**: Animated skill level indicators
- **Technology Tags**: Staggered appearance animations

## 📧 Contact Form

The contact form includes:

- Form validation
- Responsive design
- Success feedback
- Integration ready for backend services

To connect to a backend service, update the `handleSubmit` function in `ContactSection.tsx`.

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy with one click

### Other Platforms

The project can be deployed to any platform that supports Next.js:

- Netlify
- AWS Amplify
- Railway
- Heroku

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📞 Support

If you have any questions or need help customizing the portfolio, feel free to reach out!

---

**Happy Coding! 🎉**
