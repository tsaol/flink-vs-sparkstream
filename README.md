# flink-vs-sparkstream

### Spark 
The computational model of Apache Spark is based on the micro-batch model,  and so it processes data in batch mode for all workloads
This is done with chunks of data called Resilient Distributed Datasets (RDDs)

It has higher latency as compared to Flink. If there is a requirement of low-latency responsiveness, now there is no longer the need to turn to technology like Apache Storm.


### Flink
The computational model of Apache Flink is the operator-based streaming model, and it processes streaming data in real-time. It uses streams for all workloads,

In Flink, batch processing is considered as a special case of stream processing.

There is no minimum data latency in the process. It comes with an optimizer that is independent of the actual programming interface.


when analyzing Flink Vs. Spark in terms of speed, Flink is better than Spark because of its underlying architecture.



