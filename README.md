# GitHub Action to create a Repository

This action can be used to create a user or organization repository from your workflows.

## Usage

```yaml
uses: lokalise/create-repository-action@v1
with:
  name: 'repository-name'
  org: 'org-name'
  access-token: 'accessTokenWithRepoOrOrgAdminScope'
```
