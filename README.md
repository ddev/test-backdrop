This is a test repository for DDEV automated testing.

* Update base contents of this repo with a downloaded Backdrop release zipfile
* `ddev config --auto` and `ddev launch` and do installation
* `ddev export-db --file=db.sql.gz` to get database dump
* `gunzip -k db.sql.gz && tar -czf db.sql.tar.gz db.sql` to create tarball of database
* `cd files && tar -czf ../files.tgz .` to create files tarball
* Create a release with the db.sql.gz, db.sql.tar.gz and files.tgz

