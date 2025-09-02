# CursorRules

> 📝 **Note:** A comprehensive collection of rules and configurations for Cursor IDE to enhance AI-assisted development experience.

## Description

CursorRules is a curated collection of configuration files and rules designed to optimize the AI-assisted development experience in Cursor IDE. This project provides structured guidelines for code quality, documentation standards, and development best practices that can be applied across various programming languages and project types.

## Features

* **Code Quality Guidelines** - Comprehensive rules for maintaining high code standards
* **Documentation Standards** - Markdown formatting and documentation best practices
* **Language-Specific Rules** - Tailored guidelines for Go, Python, and other languages
* **Git Workflow Rules** - Best practices for version control and collaboration
* **Mentoring Guidelines** - Structured approach for code review and mentoring
* **General Development Standards** - Universal principles like SOLID, DRY, YAGNI, KISS

## Installation

### Prerequisites

* [Cursor IDE](https://cursor.sh/) installed on your system
* Git for version control

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RozhkoDmytro/CursorRules.git
   cd CursorRules
   ```

2. **Copy rules to your Cursor configuration:**
   ```bash
   cp -r .cursor/rules ~/.cursor/rules
   ```

3. **Restart Cursor IDE** to apply the new rules

### Alternative Setup

You can also manually copy specific rule files to your Cursor configuration directory based on your needs:

```bash
# Copy specific rule categories
cp .cursor/rules/general.mdc ~/.cursor/rules/
cp .cursor/rules/code-quality.mdc ~/.cursor/rules/
cp .cursor/rules/Doc/ ~/.cursor/rules/
```

## Usage

### Applying Rules

Once installed, the rules will automatically apply to your development workflow in Cursor IDE. The AI assistant will follow these guidelines when:

* Generating code suggestions
* Reviewing existing code
* Creating documentation
* Providing feedback and recommendations

### Customization

You can customize the rules by editing the `.mdc` files in your Cursor rules directory:

```bash
# Edit specific rules
nano ~/.cursor/rules/general.mdc
nano ~/.cursor/rules/code-quality.mdc
```

### Rule Categories

| Category | Description | File |
|:---|:---|:---:|
| General | Core development standards | `general.mdc` |
| Code Quality | Quality assurance guidelines | `code-quality.mdc` |
| Go Language | Go-specific best practices | `general-go.mdc` |
| Documentation | Markdown and doc standards | `Doc/markdown.mdc` |
| Git Workflow | Version control guidelines | `git/` |
| Mentoring | Code review practices | `mentoring/` |

## Contributing

We welcome contributions to improve CursorRules! Here's how you can help:

### Reporting Issues

* Use the [GitHub Issues](https://github.com/RozhkoDmytro/CursorRules/issues) page
* Provide detailed descriptions of problems or suggestions
* Include examples when possible

### Suggesting Enhancements

* Create feature requests with clear use cases
* Explain the benefits of proposed changes
* Consider backward compatibility

### Submitting Changes

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Make your changes following existing patterns
4. Test your changes in Cursor IDE
5. Submit a pull request with clear description

### Development Guidelines

* Follow existing code formatting and structure
* Add comments for complex rule logic
* Test rules in actual development scenarios
* Maintain consistency with existing rule patterns

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Copyright (c) 2025 Dmytro Rozhko**

## Contact

* **GitHub:** [@RozhkoDmytro](https://github.com/RozhkoDmytro)
* **LinkedIn:** [Dmytro Rozhko](https://linkedin.com/in/dmytro-rozhko)
* **Location:** Kyiv, Ukraine 🇺🇦

### Support

For questions, suggestions, or support:
* Open an [issue](https://github.com/RozhkoDmytro/CursorRules/issues) on GitHub
* Reach out via LinkedIn for professional inquiries

---

> 💡 **Tip:** These rules are designed to work with Cursor IDE's AI features. For best results, ensure you're using the latest version of Cursor IDE.

