# LLM4BL-datasets

## Datasets

The datasets contains bug localization data from three open source projects: AspectJ, Tomcat, ZXing.

| Project | Bug reports  | Source Code Repositories                 |
| ------- | ------------ | ---------------------------------------- |
| AspectJ | aspectj.json | https://github.com/eclipse-aspectj/aspectj.git |
| Tomcat  | tomcat.json  | https://github.com/apache/tomcat.git     |
| ZXing   | ZXing.json   | https://github.com/zxing/zxing.git       |

### Obtaining Source Code

To obtain the source code for a project, you can use the `git clone` command followed by the repository URL. This command creates a local copy of the repository on your machine, including all its files, branches, and commit history.

```
git clone <Repository_URL>
```

Replace `<Repository_URL>` with the actual URL of the repository you wish to clone.



### Bug Reports

Each bug report is documented in a JSON file, which provides a structured format for the information related to the defect. The JSON file typically includes the following key components:

- **Summary**: A brief overview of the bug, summarizing the issue.
- **Description**: A detailed explanation of the bug.
- **diff**: A list of files that were modified to fix the bug.