# My 3D Portfolio Website

A visually stunning 3D portfolio website showcasing projects, skills, education, and experience. Built to create an engaging and interactive platform for personal branding.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Live Demo](#live-demo)
- [Contributing](#contributing)
- [License](#license)

## Features

- **3D Graphics**: Immersive 3D models and animations.
- **Responsive Design**: Fully optimized for all screen sizes.
- **Interactive Sections**: Hover effects and animations to enhance user experience.
- **Themed Sections**:
  - Projects
  - Skills
  - Education
  - Experience
- **Smooth Navigation**: Intuitive and fluid page transitions.

## Technologies Used

### Frontend
- React.js
- Three.js (for 3D rendering)
- CSS3 & TailwindCSS

### Other Tools
- GLTF (for 3D models)
- Framer Motion (for animations)
- React Three Fiber

## Directory Structure

```plaintext
Balaji-Sai-charan-My-3d-portfolio/
├── public/
│   ├── manifest.json
│   ├── index.html
│   ├── robots.txt
│   └── planet/
│       ├── license.txt
│       ├── scene.bin
│       ├── scene.gltf
│       └── textures/
├── package.json
├── README.md
└── src/
    ├── index.css
    ├── components/
    │   ├── cards/
    │   │   ├── ProjectCard.jsx
    │   │   ├── ExperienceCard.jsx
    │   │   └── EducationCard.jsx
    │   ├── canvas/
    │   │   ├── Earth.jsx
    │   │   └── Stars.jsx
    │   ├── sections/
    │   │   ├── Contact.jsx
    │   │   ├── Experience.jsx
    │   │   ├── Education.jsx
    │   │   ├── Projects.jsx
    │   │   ├── Footer.jsx
    │   │   ├── Hero.jsx
    │   │   └── Skills.jsx
    │   ├── Navbar.jsx
    │   └── HeroBgAnimation/
    │       ├── HeroBgAnimationStyle.js
    │       └── index.js
    ├── App.js
    ├── images/
    ├── data/
    │   └── constants.js
    ├── index.js
    └── utils/
        ├── Themes.js
        └── motion.js
```

## Getting Started

### Prerequisites

- Node.js (v16+)
- npm or Yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Balaji-Sai-charan/Portfolio.git
   cd Portfolio
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open the application:
   Navigate to `http://localhost:3000` in your browser.

## Live Demo

Check out the live version of the portfolio: [https://balajisaicharanportfolio.netlify.app/](https://balajisaicharanportfolio.netlify.app/)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch: `git checkout -b my-feature`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin my-feature`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Developed by **Balaji Sai Charan**.
