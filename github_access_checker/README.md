# GitHub Access Checker

This folder contains scripts related to checking access permissions on GitHub repositories. The main script, github_access_checker.sh, allows you to list users with read access to a specified GitHub repository. It utilizes the GitHub API for fetching repository collaborators and identifying users with read permissions.

## Usage

1. Ensure you have a GitHub personal access token with appropriate permissions.
2. Run the github_access_checker.sh script from your terminal, providing the GitHub username, repository owner, and repository name as arguments.
3. The script will authenticate with the provided token and list users with read access to the specified repository.

## Requirements

- Bash shell environment
- curl command-line tool
- jq command-line JSON processor

## Contributions

Contributions to this collection of GitHub access checking scripts are welcome! If you have any improvements or additional functionality to suggest, feel free to open a pull request.

## License

This collection of GitHub access checking scripts is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
