# Performance tests for RPC system
Design considerations - Sync vs Async, Connection pooling vs Not
### Objective: Evaluate performance for Thrift calls at high throughputs
*  Throughput expected: Average case->30k rpm/machine; Worse case->100k rpm/machine
Approaches:
1. Sync call
  * With Pool
  * Without Pool
1. Async call
  *  With Pool
  *  Without Pool
