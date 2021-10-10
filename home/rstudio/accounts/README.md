Accounts Management
================
BioAtlas Sweden
9/26/2017

Go into the `accounts` directory after loggin in with the master user.

The master user (rstudio) should only be used for adding and removing
accounts etc such global actions….

1.  Remove the file `credentials.csv` - it is probably from the last run
    and you don’t need it
2.  You can remove `user_add.sh` and `user_del.sh` too if you don’t need
    them
3.  Then edit the `researchers.csv` file, take away any old data in
    there and add new records for all users you want to add to the
    system.
4.  Open the `setup-researcher-accounts.R` script and click “Source” to
    run the file. This automatically creates two shell script files for
    adding and deleting users: `user_add.sh` and `user_del.sh`
5.  Open the `user_add.sh` file and click the button “Run” to run the
    script and add the new user accounts.
6.  If you instead want to remove users - use the `user_del.sh` - but
    perhaps you should backup their data first?
7.  If you want to backup the generated credentials for any new
    accounts, copy and paste from `credentials.csv` into
    `credentials_history.csv`
8.  Send (individual) email or message to the new users with their
    logins and credentials
9.  Close any open windows and go back to the home directory
