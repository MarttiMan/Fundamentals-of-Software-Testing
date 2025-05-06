
## Summary (Summarize the bug encountered concisely)

    A typo is present on the "Create new blank project" page. Instead of displaying "Create blank project", the text incorrectly shows "Create black project". This may cause confusion for users.

## Steps to reproduce     

    Go to: https://gitlab.com/projects/new#blank_project
    Observe the text on the button or heading where it should say "Create blank project"
    Note the incorrect text "Create black project"

## What is the current bug behavior?

    The UI displays "Create black project" instead of the correct wording.

## What is the expected correct behavior?

    The text should correctly read "Create blank project", as per standard GitLab terminology.
     
## Relevant logs and/or screenshots

    \Image\Bug_Project_create_blank.png

## Possible fixes

    Check the front-end file or string resource where the text label is defined for the "blank project" button. Look for possible typo in the word "blank".

## Whom do you report/ Assign To/ Tags

    /label ~bug ~reproduced ~needs-investigation  
    /cc @project-manager  
    /assign @qa-tester

## Priority

    Minor – This is a low-severity bug (visual typo), but it may cause confusion to end users and should be corrected.
