# Introduction #
This is a collection of tips showing examples of log (commit messages) that will get automatically turned into issue links.

# Details #
First of all, you need to review and customize the relevant variables in svnspam.conf
Here they are listed alongside the example text strings that will trigger translation.

  * $bugzillaURL ... [bug 1234](https://code.google.com/p/svnspam/issues/detail?id=234)
  * $jiraURL ... project-1234
  * $rtURL ... rt#1234
  * $wikiURL ... [[link](wiki.md)]

It is also worth noting that, if you have ViewSVN or svnweb or trac or redmine setup, you can automically link to those also, based on the revision # of the commit.