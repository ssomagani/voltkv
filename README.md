# voltkv

## Instructions to run

`voltdb init -f -C deployment.xml`
`voltdb start -B`

(optional) Update run.sh to set the poolsize in async-benchmark() to a larger count to increase memory utilization.
(optional) Update run.sh to set getputration to 1.0 for read-only workload

`./run.sh init`
`./run.sh client`
