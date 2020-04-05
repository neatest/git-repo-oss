# Pull Request

<!---
IMPORTANT: Please do not create a Pull Request without first creating an issue and
reading our contributing guidelines on the following URL:
{%- if cookiecutter.vcs == "github" -%}
https://github.com/{{ cookiecutter.vcs_path }}/blob/master/docs/CONTRIBUTING.md
{%- elif cookiecutter.vcs == "gitlab" -%}
https://{{ cookiecutter.vcs_gitlab_url }}/{{ cookiecutter.vcs_path }}/-/blob/master/docs/CONTRIBUTING.md
{%- elif cookiecutter.vcs == "bitbucket" -%}
https://{{ cookiecutter.vcs_bitbucket_url }}/{{ cookiecutter.vcs_path }}/src/master/docs/CONTRIBUTING.md
{%- elif cookiecutter.vcs == "gogs" -%}
https://{{ cookiecutter.vcs_gogs_url }}/{{ cookiecutter.vcs_path }}/src/master/docs/CONTRIBUTING.md
{%- elif cookiecutter.vcs == "gitea" -%}
https://{{ cookiecutter.vcs_gitea_url }}/{{ cookiecutter.vcs_path }}/src/branch/master/docs/CONTRIBUTING.md
{% endif %}

You can skip this if you're fixing a typo.
--->

## Related Issue

<!---
This project only accepts pull requests related to open issues
If suggesting a new feature or change, please discuss it in an issue first
If fixing a bug, there should be an issue describing it with steps to reproduce
Please link to the issue here
-->


## Motivation and Context

<!---
Explain the context and why you're making that change.  What is the
problem you're trying to solve? In some cases there is not a problem
and this can be thought of being the motivation for your change.
--->


## Solution

<!---
Describe the modifications you've done.
What will change as a result of your pull request?
--->


## How Has This Been Tested?

<!---
Please describe in detail how you tested your changes.
Include details of your testing environment, and the tests you ran to
see how your change affects other areas of the code, etc.
If this change has an impact on UX, include screenshots or a video.
--->


## Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to change)

## Checklist
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] My code follows the code style of this project.
- [ ] My change requires a change to the documentation.
- [ ] I have updated the documentation accordingly.
- [ ] I have read the **CONTRIBUTING** document.
- [ ] I have added tests to cover my changes.
- [ ] All new and existing tests passed.
