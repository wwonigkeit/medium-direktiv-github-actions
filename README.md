# medium-direktiv-github-actions

The repository contains a very simple workflow which classifies the language used in a tweet. 

The repository is used to explain the Direktiv GitHub actions which have been created to extend the Direktiv workflow synchromisation and runtime to GitHub actions.

The repository is used and discussed in the Direktiv blog article: 

https://medium.com/@wilhelm-wonigkeit/direktiv-github-actions-available-in-marketplace-595dd51e1f72

## Action variables

The following GitHub action variables are used and defined:

`Data:
{
   "username" : "Twitter"
}
Namespace: complex-workflow
Server: demo.direktiv.io
Sync: custom-plugins-gettwitter-idlang.yaml
Token: ${{ secrets.DIREKTIV_TOKEN }}
Workflow: complex-workflow/custom-plugins-gettwitter-idlang`
