# synthetic-checkstyle-error-dataset

Repo structure:

* Readme.md
* dataset/protocol1/
  * &lt;project name>
    * &lt;numerical identifier> (each folder contains a single JSON and a single Java file containing a single error)
      * metadata.json
        * error_type
        * error_line
        * injection_operator
      * &lt;FileName.java> (the file with the single checkstyle error)
      * &lt;FileName-orig.java> (the original file without the error)
