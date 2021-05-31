# medium-direktiv-github-actions

The repository contains a very simple workflow which classifies the language used in a tweet. The repository is used to explain the Direktiv GitHub actions which have been created to extend the Direktiv workflow synchromisation and runtime to GitHub actions.

## Action variables

The following GitHub action variables are used and defined:

- Data: 
```json
{
   "username" : "Twitter"
}
```
- Namespace: complex-workflow
- Server: demo.direktiv.io
- Sync: custom-plugins-gettwitter-idlang.yaml
- Token: ${{ secrets.DIREKTIV_TOKEN }}
- Workflow: complex-workflow/custom-plugins-gettwitter-idlang
