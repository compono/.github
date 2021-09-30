# Compono GitHub Templates
The templates defined in this project will provide a standard template for the following GitHub files across the organisation,

- Pull Requests

A list of supported file types can be found [here](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file#supported-file-types).

## Overriding templates
To override the template for a specific repository, you will need to define a new template file within the specific repository. There are three locations these files can be placed, they are,

- the root of the repository
- the .github folder
- the docs folder

So for `repository-abc` they can be placed,

- `repository-abc/PULL_REQUEST_TEMPLATE.md`
- `repository-abc/.github/PULL_REQUEST_TEMPLATE.md`
- `repository-abc/docs/PULL_REQUEST_TEMPLATE.md`

Within these locations, define the corresponding files

- `PULL_REQUEST_TEMPLATE.md`