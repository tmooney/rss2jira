rss2jira
========

This is a Python script that polls RSS feeds, monitors for certain keywords,
and then creates a JIRA issue if those keywords are found.  We use ``rss2jira``
to help ensure we are answering questions about our software on community
sites such as Biostar and SEQanswers.

See ``rss2jira/rss2jira.conf.example`` for an example configuration.

There is also an example Puppet module and manifest on the ``puppet`` branch.
