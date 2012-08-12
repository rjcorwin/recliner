
# About
This is the Recline + CouchDB Data Fetch Example wrapped up in a couchapp plus a little glue code so you don't have to set the database by hand (it can be inferred by the database this design doc is deployed to). The default view is the _all_docs view unless you set that by hand in attachments/app.js  

See https://github.com/okfn/recline/pull/204

# Install

To deploy this design document to a CouchDB, you'll need the node.js couchapp utility.  See http://couchapp.org for more details.

When deployed, your app will be at http://yourURL/yourDB/_design/recliner/index.html

