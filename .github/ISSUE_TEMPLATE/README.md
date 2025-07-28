# Issue Templates for Teachers

This directory contains GitHub issue templates designed to help teachers and school staff submit well-defined change requests for the High School Activities Management System.

## Available Templates

### 🐛 Bug Report (`bug-report.yml`)
Use this template to report technical problems, errors, or unexpected behavior in the system.
- **When to use**: System crashes, error messages, features not working as expected
- **Information collected**: Problem description, steps to reproduce, impact assessment, urgency level
- **Target assignee**: `@copilot` for automated resolution

### 🎯 New Activity Request (`new-activity.yml`)
Request to add a new extracurricular activity to the system.
- **When to use**: Adding new clubs, sports teams, academic programs, or other activities
- **Information collected**: Activity details, schedule, capacity, supervisor, location, requirements
- **Target assignee**: `@copilot` for implementation
- **Validation**: Ensures all required details are provided for accurate setup

### ✏️ Modify Existing Activity (`modify-activity.yml`)
Request changes to existing activities (schedule, capacity, description, etc.).
- **When to use**: Updating activity times, changing locations, adjusting capacity, modifying descriptions
- **Information collected**: Current details, requested changes, reasons, impact on students
- **Target assignee**: `@copilot` for implementation
- **Features**: Dropdown selection of existing activities, change tracking

### 💡 Feature Request (`feature-request.yml`)
Request new functionality or enhancements to the system.
- **When to use**: Need new capabilities like email notifications, reporting features, UI improvements
- **Information collected**: Problem statement, proposed solution, user stories, acceptance criteria
- **Target assignee**: `@copilot` for development
- **Structure**: Follows software development best practices with clear acceptance criteria

### 🎨 UI/UX Improvement (`ui-ux-improvement.yml`)
Request improvements to user interface or user experience.
- **When to use**: Making the system easier to use, more accessible, or visually better
- **Information collected**: Current issues, proposed improvements, user impact, success criteria
- **Target assignee**: `@copilot` for implementation
- **Focus**: Accessibility, mobile responsiveness, usability improvements

### 👥 Student Management Request (`student-management.yml`)
Help with student registrations, rosters, or student-related issues.
- **When to use**: Student registration problems, roster management, account issues
- **Information collected**: Student details, specific issues, current status, urgency
- **Target assignee**: `@copilot` for resolution
- **Security**: Includes permission checks and authorization requirements

### 🆘 Technical Help & Support (`technical-help.yml`)
Get help using the system or ask technical questions.
- **When to use**: Login problems, how-to questions, training needs, system navigation
- **Information collected**: User role, experience level, specific questions, preferred help format
- **Target assignee**: `@copilot` for assistance
- **Approach**: Educational and supportive, not just problem-solving

## Template Design Principles

### For Non-Technical Users
- **Simple Language**: Avoids technical jargon, uses plain English
- **Clear Instructions**: Each field has examples and guidance
- **Logical Flow**: Information requested in natural order
- **Validation**: Required fields ensure complete information
- **Categories**: Dropdown menus reduce typing and standardize responses

### For Copilot Agent Effectiveness
- **Structured Information**: Consistent format makes parsing easier
- **Complete Context**: All necessary details provided upfront
- **Clear Acceptance Criteria**: Specific, measurable outcomes defined
- **Priority Indicators**: Urgency and impact clearly specified
- **Action-Oriented**: Templates focus on what needs to be done

### Quality Assurance
- **Required Fields**: Critical information cannot be omitted
- **Checklists**: Pre-submission validation prevents incomplete requests
- **Examples**: Concrete examples guide proper completion
- **Categorization**: Proper labeling for issue tracking and assignment

## Usage Guidelines

### For Teachers
1. **Choose the Right Template**: Select the template that best matches your need
2. **Be Specific**: Provide detailed information rather than general descriptions
3. **Include Context**: Explain why the change is needed and who it affects
4. **Check Examples**: Use the placeholder text as guidance for your responses
5. **Complete Checklists**: Ensure all validation items are checked before submitting

### For System Administrators
- Templates automatically assign issues to `@copilot` for processing
- Labels are pre-configured for proper categorization and filtering
- Contact links in `config.yml` can be updated with actual school contact information
- Templates can be customized by modifying the `.yml` files in this directory

## Configuration

The `config.yml` file controls the issue template selection interface:
- **Blank Issues Disabled**: Forces use of templates for better structure
- **Contact Links**: Provides alternative channels for non-template needs
- **Documentation Links**: Directs users to additional resources

## Benefits

### For Teachers
- **Reduced Frustration**: Clear guidance on what information to provide
- **Faster Resolution**: Complete information leads to quicker solutions
- **No Technical Knowledge Required**: Templates handle the technical details
- **Consistent Communication**: Standardized format improves clarity

### For the System
- **Better Issue Quality**: Structured information improves processing
- **Automated Assignment**: Issues go directly to appropriate handlers
- **Tracking and Analytics**: Consistent labeling enables better reporting
- **Reduced Back-and-Forth**: Complete initial information reduces clarification needs

## Maintenance

Templates should be reviewed and updated periodically based on:
- Common issues and requests received
- User feedback on template effectiveness  
- Changes to the underlying system
- New features or capabilities added
- School policy or process changes

When modifying templates, ensure:
- Required fields capture essential information
- Examples remain current and relevant
- Labels and assignees are accurate
- Validation checklists are comprehensive
- Language remains non-technical and clear