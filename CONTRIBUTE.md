# How to contribute

## Quick guide
1. Fork the repository.
2. Export your live template to an XML file.
3. Put the file in your forked repository.
  * Mind the directory structure.
4. Commit & push to your forked repository.
  * Adhere to the committing guide below.
5. Do a pull request.

## Live template XML file naming guide
* Use CamelCase.
* The name should reflect the action realized by the template

Examples:
`AddTestMethod.xml`
`InsertLogger.xml`

## Committing guide
#### Rule #1: one live template per commit
Every file will therefore described separately by its commit message.

#### Rule #2: Basic description of the commit can only contain the description of the live template itself.
No additional words, stories, just a simple explanation.
If you feel the need to add anything else, [use extended description](http://stackoverflow.com/questions/9562304/github-commit-with-extended-message).

#### Rule #3: When committing an updated file, the commit message should still be its description (updated if needed). 
If you feel the need to add anything beyond it, again - use extended description.

*Not adhering to any of these rules will result in rejecting the pull request.*

Example of a meaningful commit descriptions for `AddTestMethod.xml`:
* Basic description: "Adds a JUnit test method skeleton"
* Extended description: "Adds a JUnit test method skeleton, complete with 'should' name prefix and 'arrange-act-assert' comments for clear section division'

## Q&A:
#### Where can I see or discuss any remarks on my pull request, reasons for not merging or rejecting?
It's simple: any thoughts, discussions and remarks will be held as a discussion under that pull request here on GitHub.

#### How to export my live template?
* In your IDE, go to `Settings... -> Live Templates`
* Select the name of your template and "copy" the template (CTRL+C or RMB -> Copy)
  * Do NOT just copy the contents of "Template text"; they won't be accepted
* Save the contents of your clipboard as an XML file. Remember to add a meaningful name for it.

#### Where to put the XML file in the repiository structure?
Based on the template's category or "theme", try to find a directory in the existing dicectory structure. 
The directories contain readme files
If you feel your contribution does not fit into that structure,you are free add your own directory - but on two conditions:
* you *must* add a README.md filewith a short description of the intended directory contents
* you have to keep it tidy and as self-explanatory as it can be


