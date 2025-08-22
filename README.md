# gitTools

A collection of shell scripts to streamline common Git workflows.

## Tools

*   **gInit:** Initialize a new Git repository.
*   **gNew:** Create a new GitHub repository and push the current directory to it.
*   **gRelease:** Create a new GitHub release.
*   **gTag:** Create a new annotated tag.
*   **gUpdate:** Commit all changes and push them to the remote repository.

## Installation

1.  Clone this repository.
2.  Add the scripts to your `PATH`.

## Usage

```bash
gInit
gNew <repository-name>
gRelease <version> <title> <notes>
gTag <tag-name> <message>
gUpdate <commit-message>
```