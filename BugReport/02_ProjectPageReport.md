
## Summary (Summarize the bug encountered concisely)

Typographical error identified on the button used to initiate the creation of a new blank project within GitLab. The button incorrectly displays the text "Create black project" instead of the intended "Create blank project." This may confuse users and detract from the professional appearance of the platform.

## Steps to reproduce     

Navigate to https://gitlab.com/projects/new#blank_project using any mainstream web browser.
Directly below the section header "New Project," observe the text on the large button intended for creating a new project.

## What is the current bug behavior?

The button intended for creating new blank projects mistakenly displays the label "Create black project." This mislabeling can cause confusion among users who are trying to start a new project.

## What is the expected correct behavior?

The button should display the label "Create blank project" to accurately describe the action it performs. This correct labeling will ensure users understand they are starting a new project without pre-filled templates or previous configurations.
     
## Relevant logs and/or screenshots

Screenshot of the typo on the button ![Image info](../Image/Bug_Project_create_blank.png) 
This image clearly shows the typo on the button text.

## Possible fixes

The text for the button label in the source code should be corrected from "black" to "blank." This is likely a simple typo in the HTML or rendering script for the page.

Locate the source file where the button label text is specified (likely within a template or component file for the project creation page).
Correct the spelling from "black" to "blank."
Review the change in a development environment to ensure no other instances of the typo exist.
Commit the fix to the repository followed by pushing to the production environment after passing quality assurance tests.

## Whom do you report/ Assign To/ Tags

Report To: UI/UX Development Team
Assign To: Frontend Lead Developer
Tags: UI, typo, low-priority

## Priority

Low - The typographical error does not affect the functionality of the GitLab platform but should be corrected promptly to maintain the credibility and usability of the user interface. Immediate action is recommended despite the low operational impact because such errors can negatively affect user perception.
