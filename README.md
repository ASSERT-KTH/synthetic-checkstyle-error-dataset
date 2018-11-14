# synthetic-checkstyle-error-dataset

Repo structure:

* Readme.md
* dataset/
  * dataset/&lt;project name>
  * folder dataset/&lt;project name>/&lt;numerical identifier>
    * each folder contains a single JSON and a single Java file containing a single error 
    * dataset/&lt;project name>/&lt;numerical identifier>/metadata.json
      * error_type
      * error_line
      * injection_operator
    * dataset/&lt;project name>/&lt;numerical identifier>/&lt;FileName.java> (the file with the single checkstyle error)
    * dataset/&lt;project name>/&lt;numerical identifier>/&lt;FileName-orig.java> (the original file without the error)
