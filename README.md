# docc2ghpages

Generates a DocC documentation, creates static HTML pages using docc2html, and deploys it to the gh-pagges branch

## Usage

<!-- start usage -->
```yaml
- uses: DoccZz/docc2html@v2
  with:
    # The name of the scheme that the documentation should be generated for passed to xcodebuild.
    scheme: ''

    # The personal access token (PAT) used to push to the gh-pages branch.
    #
    # Default: ${{ github.token }}
    token: ''
  
    # The destination the schme can be build for passed to xcodebuild.
    # 
    # Default: platform=macOS
    destination: ''
```
<!-- end usage -->

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE)