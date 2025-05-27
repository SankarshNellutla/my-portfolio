# Sankarsh Nellutla Portfolio

[Live Site](https://sankarshnellutla.com/) | [LinkedIn](https://www.linkedin.com/in/sankarsh-nellutla/) | [Email](mailto:sankarshnellutla12@gmail.com)

## Overview

This repository contains the source files for my personal portfolio website. It is built with Quarto and deployed via Netlify. The site showcases my background, skills, projects, blog posts, and contact information.

## Table of Contents

1. [Features](#features)
2. [Technology Stack](#technology-stack)
3. [Repository Structure](#repository-structure)
4. [Getting Started](#getting-started)
5. [Deployment](#deployment)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Features

* Biographical section outlining education and professional journey
* Project showcase with descriptions, screenshots, and links to source code
* Technical blog powered by Quarto for writing articles on data engineering and analytics
* Contact form integrated with Netlify Forms for direct inquiries

## Technology Stack

* **Site Framework:** Quarto
* **Styling:** Custom CSS
* **Visualization:** Plotly, embedded charts
* **Hosting & CI/CD:** Netlify, GitHub Actions
* **Version Control:** Git, GitHub

## Repository Structure

```
.
├── about.qmd           # About page content
├── blog.qmd            # Blog index page
├── contact.qmd         # Contact form configuration
├── index.qmd           # Homepage content
├── projects.qmd        # Project showcase page
├── images/             # Assets: profile photo, project screenshots
├── styles.css          # Custom site-wide styles
└── netlify.toml        # Netlify deployment settings
```

## Getting Started

Follow these steps to run the site locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/SankarshNellutla/my-portfolio.git
   cd my-portfolio
   ```

2. **Install Quarto**
   If Quarto is not already installed, visit [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/) for installation instructions.

3. **Preview the site**

   ```bash
   quarto preview
   ```

   Open your browser at `http://localhost:4200` to view.

## Deployment

This site is automatically deployed to Netlify on every push to the `main` branch. Deployment settings are defined in the `netlify.toml` file.

## Contributing

Contributions are welcome. To suggest changes or improvements:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "Add YourFeature"`)
4. Push to your fork (`git push origin feature/YourFeature`)
5. Open a Pull Request detailing your changes

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have questions or feedback, please reach out:

* Email: [your.email@example.com](mailto:sankarshnellutla12@gmail.com)
* LinkedIn: [https://linkedin.com/in/SankarshNellutla](https://www.linkedin.com/in/sankarsh-nellutla/)
