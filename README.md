# Clarify - A Toolkit for the Frontend Workflow

Please keep in mind, that this is an alpha version. This affects several things
like missing authentication, security checks or sometimes architectural stuff.
DB Queries are not optimized all the time, etc.

This version is not intended to be used in production!

Learn more about Clarify in the following blog post (Text: German, Video: General)
http://blog.namics.com/2012/03/clarify-ein-toolkit-fur-den-frontend-workflow.html

# Requirements

* PHP 5.2+
* MySQL 5

# Installation

1. Create a database (e.g. "clarify") and configure its name in /application/config-private.php (create the file initially)
2. Run /application/db/create-tables.sql against the newly created database.
3. Open up the application in your browser and have fun