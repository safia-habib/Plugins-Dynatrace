# Hystrix Plugin

**Metrics**

| Name | Description |
| --- | --- |
| **Success** | Execution Completed with no errors |
| **Failure** | Execution threw an exception |
| **Short_Cirtuted** | Cirtuit Breaker **OPEN** Execution not attempted |
| **Fallback_Success** | Fallback execution completed with no errors |
| **Fallback_Failure** | Fallback execution threw an exception |
| **Fallback_Rejected** | Fallback semaphore at capacity, fallback not attempted |
| **Fallback_Missing** | No Fallback implemented |
| **Threads Executed** | Thread pool has space, and allowed the command to run |
| **Threads Rejected** | Thread pool has no room, and rejected the command |


**This looks as follows on the Dashboard**
![](./HystrixCircuitBreaker.png)
