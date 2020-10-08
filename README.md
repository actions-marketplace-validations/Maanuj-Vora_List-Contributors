
# List Contributors

A Github Action that will write out the contributors in a repository to a specified markdown file

---

## Action Status

![Contributing to the Contributors](https://github.com/Maanuj-Vora/List-Contributors/workflows/Contributing%20to%20the%20Contributors/badge.svg)

---

## Setting Up The Workflow Run

| Input Tag | Required | Default Value | Example |
|--|--|--|--|
| REPO_NAME | True | N/A | '${{github.repository}}' or Maanuj-Vora/List-Contributors |
| ACCESS_TOKEN | True | N/A | ${{secrets.GITHUB_TOKEN}} |
| CONTRIBUTOR | True | N/A | "### Contributors" |
| ENDCONTRIBUTOR | True | N/A | "---" |
| FILEPATH | False | '/README.md' | N/A |
| COLUMN_PER_ROW | False | '6' | N/A |
| IMG_WIDTH | False | '100' | N/A |
| FONT_SIZE | False | '14' | N/A | 
| COMMIT_MESSAGE | False | 'Contributed to Contributer' | N/A |


---

### Contributors
<html><table><tr><td align="center"><a href=https://github.com/apps/github-actions><img src=https://avatars2.githubusercontent.com/in/15368?v=4 width="50;" alt=apps/github-actions/><br /><sub style="font-size:14px"><b>apps/github-actions</b></sub></a></td><td align="center"><a href=https://github.com/Maanuj-Vora><img src=https://avatars1.githubusercontent.com/u/31610859?v=4 width="50;" alt=Maanuj Vora/><br /><sub style="font-size:14px"><b>Maanuj Vora</b></sub></a></td></tr></table></html>

---'
				FILEPATH: '/README.md'
				COLUMN_PER_ROW: '4'
				IMG_WIDTH: '50'
				FONT_SIZE: '14'
				COMMIT_MESSAGE: 'Contributed to Contributor List'
```
