# Custom Spark Version(s)

Allow to adjust the limit on bucket counts with the [included patch](0001-Configurable-bucket-count-limit.patch) against v2.3.2-rc2. Built it with:

    ./dev/make-distribution.sh --name rc2-patched --pip --tgz -Phadoop-2.7 -Phive -Phive-thriftserver

See also [apache/spark#21087](https://github.com/apache/spark/pull/21087).
