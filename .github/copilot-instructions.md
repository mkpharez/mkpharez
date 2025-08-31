# GitHub Profile Repository

This is a GitHub profile repository that displays on the mkpharez GitHub profile page. The repository contains profile information and serves as a personal introduction to visitors.

Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.

## Working Effectively

- **Repository Type**: GitHub profile repository (displays on https://github.com/mkpharez)
- **Primary Content**: README.md file that renders as profile display
- **No Build System**: This repository contains documentation only, no build steps required
- **No Dependencies**: No package.json, requirements.txt, or similar dependency files
- **No Tests**: No test suite exists as this is a profile repository

### Essential Commands
- Check repository status: `git --no-pager status` -- takes <1 second
- View file content: `cat README.md` -- takes <1 second  
- Check recent changes: `git --no-pager log --oneline -10` -- takes <1 second
- Count lines in README: `wc -l README.md` -- takes <1 second

### Making Changes to Profile
- Edit the README.md file directly using your text editor
- Changes to README.md will automatically appear on the GitHub profile page
- No build or deployment steps needed - changes are live once pushed to main branch

## Validation

### Pre-commit Validation
- **Always validate markdown syntax** before committing:
  - Check that markdown formatting is correct by reviewing the file visually
  - Ensure all emoji codes render properly (🔭, 🌱, etc.)
  - Verify that links are properly formatted if any are added
  - Confirm bullet points and formatting align correctly

### Manual Testing Scenarios
- **Profile Display Test**: After pushing changes, visit https://github.com/mkpharez to verify the README.md renders correctly on the profile page
- **Markdown Formatting Test**: Review all formatting including headers, bullet points, emphasis (bold/italic), and emoji
- **Content Accuracy Test**: Verify all personal information is accurate and professional

### Git Workflow Validation
- Always run `git --no-pager status` before making changes -- takes <1 second
- Always run `git --no-pager diff` to review changes before committing -- takes <1 second
- Check branch status with `git --no-pager branch -a` -- takes <1 second

## Common Tasks

### Repository Structure
```
ls -la [repo-root]
.
..
.git/
.github/
README.md
```

### README.md Content Overview
The README.md contains:
- Professional title and introduction
- Technology expertise (Android, Jetpack Compose, Kotlin Multiplatform)
- Placeholder sections for current projects and interests
- Contact information placeholders

### Typical Workflow
1. Edit README.md with desired changes
2. Run `git --no-pager status` to confirm changes -- takes <1 second
3. Run `git --no-pager diff README.md` to review changes -- takes <1 second  
4. Stage changes: `git add README.md` -- takes <1 second
5. Commit: `git commit -m "Update profile information"` -- takes <1 second
6. Push: `git push origin main` -- takes 1-3 seconds depending on network

### File Locations
- **Main content**: `/README.md` - Contains all profile information
- **Git configuration**: `/.git/` - Standard git metadata
- **GitHub configuration**: `/.github/` - Contains this instruction file

## Important Notes

### Content Guidelines
- Keep content professional as this displays publicly on GitHub profile
- Maintain consistent formatting with existing style
- Use emoji sparingly and appropriately for tech profiles
- Fill in placeholder sections (...) with actual content when updating

### Technical Limitations
- **No CI/CD**: No automated workflows for this repository type
- **No External API Access**: GitHub API may be blocked in development environment
- **No Build Artifacts**: No generated files or build outputs to manage
- **Simple Git Workflow**: Standard git commands work normally

### Future Development
If code projects are added to this repository:
- Add appropriate .gitignore file for the technology stack
- Set up build scripts and dependency management files
- Add testing infrastructure as appropriate for the project type
- Update these instructions with build/test/run commands

### Performance Expectations
- All git operations complete in under 1 second
- File operations (reading/writing README.md) complete instantly
- No long-running processes or builds in this repository
- Network operations (git push) typically take 1-3 seconds

## Troubleshooting

### Common Issues
- **Push failures**: Ensure you have proper permissions to the mkpharez/mkpharez repository
- **Markdown not rendering**: Check GitHub's markdown guide for syntax requirements
- **Profile not updating**: Changes may take a few minutes to appear on the GitHub profile page

### Emergency Procedures
- **Revert bad changes**: `git checkout README.md` -- takes <1 second
- **Check git history**: `git --no-pager log --oneline -10` -- takes <1 second
- **Force refresh profile**: Push any small change to trigger GitHub profile refresh