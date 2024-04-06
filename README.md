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



representing a different Version containing:

- instructions replicating the build
- links to hardware used
- tips and notes on building 
