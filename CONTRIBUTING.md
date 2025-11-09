# Contributing to LaTeX Guide

Thank you for your interest in contributing to this LaTeX documentation! This guide will help you get started.

## Getting Started

### Prerequisites

- Ruby 3.3.5 or higher
- Bundler
- Git

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/resnikal71202/LaTeX.git
   cd LaTeX
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run the site locally**
   ```bash
   bundle exec jekyll serve
   ```
   The site will be available at `http://localhost:4000/LaTeX`

4. **Make your changes**
   - Edit markdown files in the appropriate directories
   - Preview your changes locally
   - Ensure all links work correctly

## Making Contributions

### Workflow

1. **Fork the repository** on GitHub
2. **Create a new branch** for your changes
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** following our guidelines
4. **Test your changes** locally
5. **Commit your changes** with clear, descriptive messages
   ```bash
   git commit -m "Add: description of your changes"
   ```
6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request** on GitHub

### Pull Request Guidelines

- Fill out the pull request template completely
- Ensure all CI checks pass
- Keep changes focused and atomic
- Write clear commit messages
- Update documentation as needed
- Add screenshots for UI changes

### Code Style

- Use Markdown for all documentation
- Follow existing file structure
- Use ATX-style headers (`#` instead of `===`)
- Keep lines reasonably short for readability
- Use consistent formatting

### Commit Message Format

Use clear, descriptive commit messages:
- `Add: new content or features`
- `Fix: bug fixes or corrections`
- `Update: changes to existing content`
- `Docs: documentation changes`
- `Chore: maintenance tasks`

## Reporting Issues

- Use the appropriate issue template
- Provide clear, detailed descriptions
- Include steps to reproduce (for bugs)
- Add screenshots when helpful

## Questions?

If you have questions, please:
- Check existing documentation
- Search existing issues
- Open a new issue with the "question" label

## Code of Conduct

- Be respectful and inclusive
- Welcome newcomers
- Focus on constructive feedback
- Help maintain a positive community

Thank you for contributing!
