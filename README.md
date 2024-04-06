[![Run TODO to Issue](https://github.com/Robjects-Timers/.github/actions/workflows/todo-to-issue.yml/badge.svg?branch=main)](https://github.com/Robjects-Timers/.github/actions/workflows/todo-to-issue.yml)

# .github

# setup
steps:
  - name: checkout
    uses: actions/checkout@v2
  - name: rewriteReadme
    uses: seed-of-apricot/issue-list-readme@v1.1.0
    with:
      GITHUB_TOKEN: '${{ secrets.GITHUB_TOKEN }}'
      pattern: '<!-- issueTable -->' # suffixing "Demo" for this readme
      labels: 'good first issue'
      state: 'open'
# you need to add, commit and push here
# otherwise the changes will not be pushed back into master

<!-- hiiiii --!>
<!--  hi  -->
<!-- 
TODO: new issue, please work
label: 'bug'
-->


representing a different Version containing:

- instructions replicating the build
- links to hardware used
- tips and notes on building 
