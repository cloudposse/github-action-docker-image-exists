<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| image\_name | Image name (excluding registry). Defaults to {{$organization/$repository}}. |  | false |
| login | Docker login |  | false |
| organization | Organization | N/A | true |
| password | Docker password |  | false |
| registry | Docker registry | N/A | true |
| repository | Repository | N/A | true |
| tag | Tag | N/A | true |


## Outputs

| Name | Description |
|------|-------------|
| image | Docker image name |
| tag | Docker image tag |
<!-- markdownlint-restore -->
