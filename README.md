# pouchdb-attachments-sync-test

> PouchDB Sync Test for attachments

Current PouchDB downloads all attachments from all revisions when replicating
from a remote repository, instead of smartly check what attachments already
exist locally. The related issue is [#2674](https://github.com/pouchdb/pouchdb/issues/2674).

See http://gr2m.github.io/pouchdb-attachments-sync-test for instructions and
test case.
