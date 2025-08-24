# SWE 363 - 251 In-Lab Participation

## Overview
Hands-on coding demonstrations and collaborative exercises during class time. 20 demos throughout the semester, each worth 0.5% of final grade.


## Requirements

- **Timing**: Complete during class time only (no late submissions)
- **Format**: Live coding with instructor and peers observing
- **Mandatory**: Class attendance, active engagement


## Technical Requirements

- Code editor (Cursor, VS Code, Sublime Text, etc.)
- Web browser with developer tools
- Git (latest version)
- Node.js for JavaScript development
- Terminal/Command Prompt access

## GitHub Instructions

### Repository Setup
1. **Fork the course repository** to your GitHub account
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/web_course-1.git
   cd web_course-1
   ```
3. **Add the original repository as upstream**:
   ```bash
   git remote add upstream https://github.com/ORIGINAL_OWNER/web_course-1.git
   ```

### Before Each Lab Session
1. **Update your local repository**:
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```
2. **Create a new branch** for your lab work:
   ```bash
   git checkout -b lab-session-[date]-[topic]
   ```

## How to Submit PRs

### During Lab Sessions
1. **Complete the assigned tasks** in your local branch
2. **Commit your changes** with descriptive messages:
   ```bash
   git add .
   git commit -m "Complete lab exercise: [brief description]"
   ```
3. **Push your branch** to your fork:
   ```bash
   git push origin lab-session-[date]-[topic]
   ```

### Creating Pull Requests
1. **Go to your GitHub fork** in a web browser
2. **Click "Compare & pull request"** for your pushed branch
3. **Fill in the PR template**:
   - **Title**: `Lab Session [Date] - [Topic]`
   - **Description**: Brief summary of what you completed
   - **Checklist**: Mark completed items
4. **Submit the PR** before the end of class

### PR Requirements
- **Timing**: Must be submitted during class time
- **Content**: Include all required files and changes
- **Quality**: Code should be functional and well-formatted
- **Documentation**: Add comments where appropriate

## Evaluation

### Grading Criteria (0.5% per demo)
- **Completion (40%)**: All required tasks completed
- **Code Quality (30%)**: Proper syntax, formatting, and structure
- **Participation (20%)**: Active engagement during lab session
- **Documentation (10%)**: Clear commit messages and comments

### Evaluation Timeline
- **Immediate**: Instructor reviews during lab session
- **Within 24 hours**: Feedback provided via GitHub comments
- **Weekly**: Grades updated in course management system

### Common Issues to Avoid
- **Late submissions**: No credit for PRs submitted after class
- **Incomplete work**: Partial completion results in reduced points
- **Poor commit messages**: Use descriptive, professional language
- **Missing files**: Ensure all required deliverables are included

## Support Resources

- Instructor office hours
- Teaching assistants during lab sessions
- Online documentation and tutorials
- Peer collaboration during lab time

## Getting the most out of it

- Review course materials and slides
- Arrive on time with necessary materials
- Ask questions when needed

## Conclusion
Active participation in lab sessions is crucial for mastering web development. Approach each session with enthusiasm and curiosity. The skills developed here will serve as the foundation for your future web development endeavors.