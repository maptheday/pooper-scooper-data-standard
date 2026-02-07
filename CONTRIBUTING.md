# Contributing to CODS

Thank you for your interest in contributing to the Client Onboarding Data Standard! This document provides guidelines for contributing.

## Ways to Contribute

### 1. Report Issues
- Bug reports in implementations
- Specification ambiguities
- Documentation errors
- Security vulnerabilities (see [SECURITY.md](SECURITY.md))

### 2. Suggest Improvements
- New features for future versions
- Additional validation rules
- Enhanced data fields
- Integration examples

### 3. Improve Documentation
- Fix typos or unclear explanations
- Add examples and use cases
- Translate documentation
- Create tutorials or guides

### 4. Submit Code
- Validation tools
- Example implementations
- Integration libraries
- Testing utilities

### 5. Share Your Implementation
- List your CODS-compatible software
- Provide case studies
- Share migration experiences

## Getting Started

1. **Check existing issues** - Someone may already be working on it
2. **Open an issue first** - Discuss significant changes before coding
3. **Fork the repository** - Make changes in your own copy
4. **Create a branch** - Use descriptive names like `feature/webhook-spec` or `fix/validation-bug`
5. **Make your changes** - Follow our style guide
6. **Test thoroughly** - Ensure examples validate
7. **Submit a pull request** - Describe what and why

## Pull Request Process

### Before Submitting

- [ ] Code follows our style guide
- [ ] Documentation is updated
- [ ] Examples are validated
- [ ] CHANGELOG.md is updated (for spec changes)
- [ ] All tests pass

### PR Description Should Include

- **What** changed
- **Why** it changed
- **How** it was tested
- **Breaking changes** (if any)
- **Related issues** (use #issue-number)

### Review Process

1. Maintainers review within 1 week
2. Feedback addressed by contributor
3. Approved PRs merged to main branch
4. Released in next version

## Specification Changes

### Proposing Spec Changes

Major specification changes require an RFC (Request for Comments):

1. Open an issue with `[RFC]` prefix
2. Describe the problem
3. Propose a solution
4. Discuss alternatives
5. Gather community feedback
6. Revise based on input
7. Final approval by working group

### Version Implications

- **Patch** (1.0.1): Typos, clarifications, non-functional changes
- **Minor** (1.1.0): New optional fields, backward-compatible additions
- **Major** (2.0.0): Breaking changes, required field changes, removed features

## Style Guide

### JSON Schema

- Use 2-space indentation
- Keep field names lowercase with underscores (snake_case)
- Include descriptions for all fields
- Provide examples

### Documentation

- Use clear, simple language
- Include code examples
- Link to related sections
- Keep line length under 100 characters

### Code Examples

- Must be valid, working code
- Include comments for clarity
- Use realistic, relevant examples
- Test before committing

## Testing

### Validation Tests

Run the validator against test data:

```bash
npm test
```

### Example Validation

All examples must pass validation:

```bash
npm run validate-examples
```

### Creating Test Cases

1. Add JSON file to `/tests/fixtures/`
2. Update test suite
3. Document expected behavior

## Community Guidelines

### Code of Conduct

- Be respectful and inclusive
- Welcome newcomers
- Focus on what's best for the community
- Show empathy toward others

### Communication

- **Issues** - Bug reports, feature requests
- **Discussions** - Questions, ideas, general chat
- **Pull Requests** - Code and documentation changes
- **Email** - Private concerns (hello@maptheday.com)

### Working Group

The working group makes final decisions on:
- Specification changes
- Version releases
- Governance policies

**Current Members:**
- Map The Day (maintainer)
- [Open for nominations]

**How to Join:**
- Active contribution for 3+ months
- Nomination by existing member
- Consensus approval

## Release Process

1. **Proposal** - RFC for major changes
2. **Discussion** - Community feedback period (2-4 weeks)
3. **Draft** - Create draft specification
4. **Testing** - Reference implementation and test suite
5. **Release Candidate** - RC version for testing (2 weeks)
6. **Final Release** - Official version published
7. **Announcement** - Blog post, email list, social media

## Recognition

Contributors are recognized in:
- CHANGELOG.md for each release
- README.md contributors section
- Release notes

## Questions?

- **Documentation questions** - Open a discussion
- **Bug reports** - Open an issue
- **Feature ideas** - Open an issue or discussion
- **Implementation help** - Join our monthly call or email us
- **Private concerns** - Email hello@maptheday.com

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

Thank you for helping make CODS better! 🎉
