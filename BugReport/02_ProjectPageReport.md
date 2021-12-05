
## Summary (Summarize the bug encountered concisely)

    When going to the create new project page on GitLab (https://gitlab.com/projects/new), there is a typo: The page states "Create black project" instead of "Create blank project". 

## Steps to reproduce

    1. Log int to GitLab on https://gitlab.com/users/sign_in
    2. Navigate to the create new project page on https://gitlab.com/projects/new
	3. There are four options, of which the top left option contains a typo. It states "Create black project" instead of "Create blank project"

## Example Project

     Example project with images: https://gitlab.com/oskhii/bug_report/-/issues

## What is the current bug behavior?

    The create new project website on GitLab https://gitlab.com/projects/new contains a typo and states "Create black project" instead of "Create blank project". The website still works correctly, despite the typo. 

## What is the expected correct behavior?

    The website (https://gitlab.com/projects/new)is expected to state "Create blank project" instead of "Create black project".
     
## Relevant logs and/or screenshots

    Screenshots provided on GitLab project: https://gitlab.com/oskhii/bug_report/-/issues

## Possible fixes

      Edit the code of the website (https://gitlab.com/projects/new) to state "Create blank project" instead of the current "Create black project"
