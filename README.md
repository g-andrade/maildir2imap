# New location

[https://github.com/g-andrade/misc](https://github.com/g-andrade/misc)

# maildir2imap
Upload maildir-style directories to IMAP; `maildir2imap` will:

1. Fetch all local message IDs from the specified directories
2. Fetch all remote message IDs (up to 1.0e9 entries) from the IMAP folder
3. ..and based on these try and upload all messages that are missing (from the IMAP folder)

It's partially based on a [2009 blog post](http://scott.yang.id.au/2009/01/migrate-emails-maildir-gmail.html) by Scott Yang and its attached script.
