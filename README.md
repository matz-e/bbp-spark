# Custom Spark Version(s)

Remove the limit on bucket counts with the [included patch](0001-Remove-bucket-count-limit.patch), built it with:

    ./dev/make-distribution.sh --name master-spark --pip --tgz -Phadoop-2.7 -Phive -Phive-thriftserver

For Spark 2.3.0, see apache/spark#21087.
