# The coolest animal on AWS Data Pipeline

It's a simple app to demonstrate how Clojure can be ran on AWS Data Pipeline.

You can run it locally with `lein run`, ensuring that `INPUT1_STAGING_DIR`
environment variable points to a folder containing `animals.txt` with some
animal names in separate lines, and `OUTPUT1_STAGING_DIR` points to a writable
directory.

To run it on Data Pipeline, use an AMI of a machine with Java and Leiningen
installed.
