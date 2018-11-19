# GitHub/ZenHub Reporting Tool (GitHubReporting)

Prerequisites:
* Python 3.x


## Overview
This tool will connect to an existing enterprise or public GitHub repository and export the issues along with any corresponding ZenHub issue details (ie pipeline) to a CSV file.


## Setup ##
- Make copy of getGitHubData.py_SAMPLE and rename to getGitHubData_<PROJECTNAME>.py
- Open getGitHubData_<PROJECTNAME>.py and make the appropriate updates to the Credentials section of the script.

__NOTE:__  This file will contain sensitive information that should not be pushed to GitHub, so it must start with getGitHubData_ to be ignored by .gitignore


## Execution
- Open a terminal window and change to the directory where the python script is located.
- Execute the following command.

```python3
python getGitHubData_<PROJECTNAME>.py
```

- A CSV output file will be created in the same directory as the script.
