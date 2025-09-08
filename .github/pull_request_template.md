# Pull Request Description

## 📋 Summary
Provide a clear and concise summary of the changes made. Include:
- What was changed and why
- Which issue(s) this PR addresses
- Any breaking changes or migration steps required

**Fixes:** #(issue-number)  
**Type:** [Feature/Bugfix/Hotfix/Refactor/Documentation]


## 🧪 Testing

### Quality Gates
- [ ] SonarQube quality gates passed
- [ ] No new code smells or security vulnerabilities
- [ ] Mobile responsiveness tested (if frontend changes)
- [ ] Accessibility guidelines followed (WCAG 2.1 AA)

## 🏗️ AEM Component Development

### Component Structure
- [ ] Component follows naming conventions (use `phoenix`, not `phx`)
- [ ] Component policy configuration committed
- [ ] `data-component` attribute added to component markup
- [ ] Component class added via `htmlTag` file
- [ ] Edit configuration supports refresh after edit/add/delete operations

### OOTB Integration (if applicable)
- [ ] OOTB HTL/HTML integrated with Storybook
- [ ] Dialog, design dialog and Authoring functionality verified

### Content & Configuration
- [ ] All OSGi configurations included in codebase
- [ ] No hardcoded values or environment-specific settings

## 🔒 Security & Performance

### Security
- [ ] No sensitive data exposed in logs or responses
- [ ] No secrets, passwords, or API keys committed

## 📚 Documentation

- [ ] Code comments added for complex logic
- [ ] Component documentation updated in TDS
