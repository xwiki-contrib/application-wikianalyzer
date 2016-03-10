# Wiki Analyzer 

Set of tools to analyze the contents of a wiki

* Project Lead: [Denis Gervalle](http://www.xwiki.org/xwiki/bin/view/XWiki/dgervalle) 
* [Documentation & Download](http://extensions.xwiki.org/xwiki/bin/view/Extension/Wiki+Analyzer) 
* [Issue Tracker](http://jira.xwiki.org/jira/browse/WANALYZER) 
* Communication: [Mailing List](http://dev.xwiki.org/xwiki/bin/view/Community/MailingLists), [IRC](http://dev.xwiki.org/xwiki/bin/view/Community/IRC) 
* [Development Practices](http://dev.xwiki.org/xwiki/bin/view/Community/DevelopmentPractices) (as much as you can !)
* Minimal XWiki version supported: XWiki 5.2.2
* License: LGPL 2.1
* Translations: N/A 
* Sonar Dashboard: N/A 
* Continuous Integration Status: N/A

## Available tools

### List Installed Extensions

This very basic tool provide in a quickly filterable table the list of all installed extensions with the follwing details:
 * Extension name
 * Extension ID
 * List of wikis where the extension is installed (namespaces)
 * List of pages installed by the extension
 
### All Document Status

Somehow similar to the Document index, this livetable contains 3 additional columns:
 * State of the document in comparison to your SVN (works only if the SVNApp is installed with a working profile)
 * State of the document in comparison to the original one in an extension (if the document is from an extension)
 * Name of the extension having installed this document if any
