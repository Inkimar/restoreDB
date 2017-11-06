# restoreDB
testing to restore

run once, creates the db 'redmine'

retrieve the files from your redmine-instance .
copy the 'redmine'-directory with the *frm- and *ibd-files
copy the 'redmine'-directory to restoreDB/mysql-datadir/redmine

replace the 3 files (see https://dba.stackexchange.com/questions/16875/restore-table-from-frm-and-ibd-file)
ibdata1
ib_logfile0
ib_logfile1