# Vijay Amirisetty - Profile Website

A professional profile website built with Hugo static site generator, showcasing experience, skills, and achievements in technology leadership and machine learning.

## About

This website serves as a comprehensive professional portfolio for Vijay Amirisetty, a Senior Technology and Machine Learning leader with 16+ years of experience across e-Commerce, Supply Chain, Transportation, Big Data, and Social Networking platforms.

## Website Structure

### Main Sections
- **Home**: Overview and introduction
- **About**: Detailed professional background and philosophy
- **Experience**: Career highlights and industry impact
- **Skills**: Technical expertise and leadership capabilities
- **Projects**: Notable achievements and project portfolio
- **Contact**: Professional networking and collaboration opportunities

### Features
- Responsive design using Hugo's Ananke theme
- SEO-optimized content
- Professional navigation menu
- Social media integration
- Fast loading static site

## Technology Stack

- **Static Site Generator**: Hugo
- **Theme**: Ananke
- **Deployment**: GitHub Pages
- **Content**: Markdown files
- **Configuration**: TOML

## Local Development

### Prerequisites
- Hugo (extended version recommended)
- Git

### Setup
1. Clone the repository
2. Navigate to the website directory:
   ```bash
   cd website
   ```

3. Start the development server:
   ```bash
   hugo server --buildDrafts
   ```

4. Visit `http://localhost:1313` to view the site

### Building for Production
```bash
cd website
hugo --minify
```

## Content Management

All content is written in Markdown and stored in the `website/content/` directory:

- `_index.md` - Homepage content
- `about.md` - About page
- `experience.md` - Professional experience
- `skills.md` - Technical skills and capabilities
- `projects.md` - Project portfolio
- `contact.md` - Contact information
- `posts/` - Blog posts and articles

## Deployment

The site is configured for deployment to GitHub Pages at `https://amirivija.github.io/`

### Automated Deployment
The repository includes GitHub Actions workflow for automatic deployment when changes are pushed to the main branch.

## Customization

### Theme Configuration
The site uses the Ananke theme with customizations in `hugo.toml`:
- Navigation menu structure
- Social media links
- SEO optimization
- Author information

### Adding Content
To add new pages or posts:
1. Create new Markdown files in the appropriate directory
2. Include proper front matter with title, description, and date
3. Write content using Markdown syntax

## Professional Profile Highlights

### Leadership Experience
- 16+ years in technology leadership roles
- Cross-functional team management and development
- Strategic technology planning and execution

### Technical Expertise
- Machine Learning and AI architecture
- Scalable platform development
- Cloud technologies and DevOps
- Big Data and analytics systems

### Industry Impact
- E-commerce platform optimization
- Supply chain and logistics solutions
- Transportation technology innovation
- Social networking and content platforms

## Contact & Collaboration

For professional opportunities, speaking engagements, or consulting inquiries, please use the contact information provided on the website.

---

*Built with passion for technology and commitment to excellence.*
