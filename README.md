# hebrew-developers
Software jargon in the language of the Hebrew man

## About

This repository contains Hebrew translations for software industry terms and concepts. The goal is to provide a comprehensive dictionary that helps Hebrew-speaking developers communicate effectively in their native language.

## Dictionary Structure

All translations are stored in `dictionary.yaml`. Each entry follows this structure:

```yaml
- phrase: "english term"
  hebrew_translations:
    - "תרגום עברי 1"
    - "תרגום עברי 2"
  description: "Detailed description of the term"
  date_submitted: "YYYY-MM-DD"
  submitted_by: "github_username"
  hashtags:
    - "category1"
    - "category2"
```

### Fields

- **phrase**: The English term or phrase (required)
- **hebrew_translations**: A list of one or more Hebrew translations (required)
- **description**: A clear explanation of what the term means (required)
- **date_submitted**: Date when the entry was added in YYYY-MM-DD format (required)
- **submitted_by**: GitHub username of the contributor (required)
- **hashtags**: Optional tags for categorizing entries (e.g., "devops", "testing", "git")

## Contributing

We welcome contributions! To add a new translation:

1. Fork this repository
2. Add your entry to `dictionary.yaml` following the structure above
3. Ensure your YAML syntax is valid
4. Submit a pull request

### Guidelines

- Provide accurate and commonly-used Hebrew translations
- Include a clear description in English
- Add relevant hashtags to help categorize entries
- Multiple translations for the same term are encouraged
- Use proper YAML formatting and indentation

## Example Entry

```yaml
- phrase: "production environment"
  hebrew_translations:
    - "סביבת ייצור"
  description: "A production environment is the live environment where the application or system is available to end-users."
  date_submitted: "2025-11-17"
  submitted_by: "blade"
  hashtags:
    - "deployment"
    - "infrastructure"
```

## License

See LICENSE file for details.
