# IssueOps

 This repository uses **IssueOps** to manage GitHub organization, team, and repository configurations through GitHub Issues.

## How It Works

 This repository leverages GitHub Actions workflows to process requests submitted via issues. When an issue is created with one of the provided templates, a corresponding workflow is triggered to validate and execute the requested action.

 ## IssueOps Requests
 The following requests can be made and will be carried out via the IssueOps process.
 
 ### Repository Management Requests
- [Add a repository to an organization](docs/add-repo-to-org.md)
- [Archive a repository](docs/archive-repo.md)
- [Delete a repository](docs/delete-repo.md)
- [Rename a repository](docs/rename-repo.md)
- [Set repository template status](docs/set-repo-template-status.md)
- [Unarchive a repository](docs/unarchive-repo.md)

### Team Management Requests
- [Add a member to a team](docs/add-member-to-team.md)
- [Add a team to a repository](docs/add-team-to-repo.md)
- [Add a team to an organization](docs/add-team-to-org.md)
- [Remove member from a team](docs/remove-member-from-team.md)
- [Update member in a team](docs/update-member-in-team.md)


## IssueOps Commands

For a detailed list of commands that can be used in issue comments to manage the IssueOps process (e.g., `.validate`, `.submit`, `.approve`, `.deny`), refer to the [IssueOps Commands README](docs/issueops-commands.md).
