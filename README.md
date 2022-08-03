## transfer_terra_nextstrain
Transfers the results of Broad Institutes [SarsCov2_Nextstrain WDL](https://dockstore.org/workflows/github.com/broadinstitute/viral-pipelines/sarscov2_nextstrain:v2.1.33.9) to your chosen google bucket.

In the "out_dir" put the name of the bucket that you want your files to transfer to with double quotes
Example: "gs://diana_sandbox/nextstrain_20210401"

The complete google bucket path to where you would like your files transferred should be set in the Terra input section as String in double quotes.

This workflow utilizes the publicly available docker image theiagen/utility:1.0
