# Contributing to Universal AI × Supply Chain Management

Thank you for your interest in contributing to the UAI × SCM project! This document provides guidelines for contributing to our educational AI modules.

## 🎯 Project Mission

Our goal is to create high-quality, accessible educational content that demonstrates practical AI applications in supply chain management for the global learning community.

## 🤝 How to Contribute

### Types of Contributions

1. **Content Improvements**
   - Enhance existing notebook explanations
   - Add new examples or use cases
   - Improve code documentation
   - Fix typos or formatting issues

2. **New Modules**
   - Propose new AI × Supply Chain applications
   - Create additional horizontal (foundation) modules
   - Develop specialized vertical (application) modules

3. **Technical Enhancements**
   - Optimize code performance
   - Add error handling
   - Improve user interfaces
   - Enhance visualization

4. **Documentation**
   - Update README files
   - Create tutorial guides
   - Add API documentation
   - Improve setup instructions

## 📋 Contribution Process

### 1. Before You Start

- Check existing [issues](https://github.com/your-org/uai-scm/issues) and [discussions](https://github.com/your-org/uai-scm/discussions)
- For major changes, create an issue first to discuss your proposal
- Ensure your contribution aligns with our educational objectives

### 2. Setting Up Development Environment

```bash
# Fork the repository on GitHub
# Clone your fork
git clone https://github.com/your-username/uai-scm.git
cd uai-scm

# Create a new branch for your contribution
git checkout -b feature/your-feature-name

# Set up development environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
pip install -r requirements-dev.txt
```

### 3. Making Changes

#### For Notebook Contributions:
- Ensure all cells run without errors
- Include clear explanations and comments
- Add learning objectives at the beginning
- Include practical examples relevant to supply chain management
- Test with different API providers when applicable

#### For Code Contributions:
- Follow PEP 8 style guidelines
- Add docstrings to functions and classes
- Include type hints where appropriate
- Write unit tests for new functionality

### 4. Testing Your Changes

```bash
# Run notebook tests
jupyter nbconvert --execute --to notebook --inplace *.ipynb

# Run unit tests (if applicable)
pytest tests/

# Check code style
flake8 .
black --check .
```

### 5. Submitting Your Contribution

```bash
# Commit your changes
git add .
git commit -m "feat: add new supply chain optimization example"

# Push to your fork
git push origin feature/your-feature-name

# Create a Pull Request on GitHub
```

## 📝 Content Guidelines

### Educational Standards

1. **Clarity**: Explanations should be accessible to learners with basic Python knowledge
2. **Progression**: Build concepts incrementally from simple to complex
3. **Practical Focus**: Include real-world supply chain scenarios
4. **Interactive Elements**: Use widgets and visualizations where helpful
5. **Error Handling**: Provide graceful error handling and helpful error messages

### Code Quality

1. **Readability**: Code should be self-documenting with clear variable names
2. **Modularity**: Break complex operations into reusable functions
3. **Performance**: Optimize for educational clarity first, performance second
4. **Security**: Never hardcode API keys or sensitive information
5. **Compatibility**: Ensure compatibility with Python 3.8+

### Documentation Standards

1. **Markdown Formatting**: Use consistent heading levels and formatting
2. **Code Examples**: Include working code snippets with expected outputs
3. **Prerequisites**: Clearly state required knowledge and setup steps
4. **Learning Outcomes**: Define what learners will achieve
5. **References**: Cite relevant academic papers or industry sources

## 🏷️ Issue and PR Guidelines

### Issue Templates

When creating issues, please use our templates:

- **Bug Report**: For reporting errors or unexpected behavior
- **Feature Request**: For proposing new functionality
- **Content Improvement**: For suggesting educational enhancements
- **Question**: For asking questions about the project

### Pull Request Guidelines

1. **Title**: Use conventional commit format (feat:, fix:, docs:, etc.)
2. **Description**: Clearly explain what changes you made and why
3. **Testing**: Describe how you tested your changes
4. **Screenshots**: Include screenshots for UI changes
5. **Breaking Changes**: Clearly mark any breaking changes

### Review Process

1. All PRs require review from at least one maintainer
2. Educational content requires review from subject matter experts
3. Code changes require testing and style compliance
4. Large changes may require discussion in issues first

## 🎓 Educational Content Standards

### Module Structure

Each notebook should follow this structure:

1. **Title and Overview**
   - Clear module title
   - Brief description of learning objectives
   - Prerequisites and setup requirements

2. **Introduction**
   - Context and motivation
   - Real-world applications
   - Connection to supply chain management

3. **Core Content**
   - Step-by-step explanations
   - Code examples with outputs
   - Interactive elements where appropriate

4. **Practical Applications**
   - Supply chain use cases
   - Hands-on exercises
   - Extension opportunities

5. **Conclusion and Next Steps**
   - Summary of key concepts
   - Suggested follow-up modules
   - Additional resources

### API Key Management

- Always use environment variables for API keys
- Provide fallback options for users without API access
- Include clear setup instructions for obtaining keys
- Never commit actual API keys to the repository

## 🚀 Release Process

### Version Numbering

We use semantic versioning (MAJOR.MINOR.PATCH):

- **MAJOR**: Breaking changes to module structure
- **MINOR**: New modules or significant feature additions
- **PATCH**: Bug fixes and minor improvements

### Release Checklist

- [ ] All notebooks execute without errors
- [ ] Documentation is updated
- [ ] Requirements are current
- [ ] Examples work with latest API versions
- [ ] Educational objectives are met

## 📞 Getting Help

- **Questions**: Use [GitHub Discussions](https://github.com/your-org/uai-scm/discussions)
- **Bugs**: Create an [issue](https://github.com/your-org/uai-scm/issues)
- **Chat**: Join our community Slack (link in main README)
- **Email**: Contact maintainers at uai-scm@mit.edu

## 🏆 Recognition

Contributors will be recognized in:

- Repository contributors list
- Module acknowledgments
- Annual contributor highlights
- MIT Open Learning community features

## 📄 License

By contributing, you agree that your contributions will be licensed under the same MIT License that covers the project.

---

Thank you for helping make AI education more accessible to the global community! 🌍
