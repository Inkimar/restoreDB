# restoreDB
testing to restore

run once, creates the db 'redmine'

1. retrieve the files from your redmine-instance .
2. copy the 'redmine'-directory with the *frm- and *ibd-files
3. copy the 'redmine'-directory to restoreDB/mysql-datadir/redmine

replace the 3 files (see https://dba.stackexchange.com/questions/16875/restore-table-from-frm-and-ibd-file)
1. ibdata1
2. ib_logfile0
3. ib_logfile1