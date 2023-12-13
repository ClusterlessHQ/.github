# ClusterlessHQ

```text
                                       ┌ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┐                                
                                        Project A                                               
                                       │      _                │                                
                                             ╱ ╲      .─────.             ┌ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ 
┌ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┐     ╔══╬═══▶▕   ▏═══▶(|||||||)═╬═════╗     Project C           │
 Ingress Project                    ║        ╲ ╱      `─────'        ║    │    _                
│                             │     ║  │      ▔                │     ║        ╱ ╲      .─────. │
   ════▶╔ ═ ═ ╗                     ║      Workload                  ╚════╬═▶▕   ▏═══▶(|||||||) 
│          _                  │     ║  └ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┘              ╲ ╱      `─────' │
        ║ ╱#╲ ║      .─────.        ║                                     │    ▔                
│  ════▶ ▕###▏ ════▶(|||||||)═╬═════╣                                          ▲               │
        ║ ╲#╱ ║      `─────'        ║                                     └ ─ ─║─ ─ ─ ─ ─ ─ ─ ─ 
│          ▔         Dataset  │     ║                                          ║                
   ════▶╚ ═ ═ ╝                     ║  ┌ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ╬ ─ ─ ─          
│      Boundary               │     ║         _                     _          ║      │         
 ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─      ║  │     ╱ ╲      .─────.      ╱ ╲      .─────.             
                                    ╚══════▶▕   ▏═══▶(|||||||)═══▶▕   ▏═══▶(|||||||)  │         
                                       │     ╲ ╱      `─────'      ╲ ╱      `─────'             
                                              ▔                     ▔                 │         
                                       │Project B                                               
                                        ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┘
```
## Event Driven Data Processing

Clusterless is a tool for deploying decentralized, scalable, and secure data-processing workloads for continuously
arriving data, across clouds.

By leveraging native pay-as-you-go primitives, no runtimes or dedicated services need to be managed.

Zero data arriving means zero costs (other than storage for historical data).

Draft documentation can be found here: https://docs.clusterless.io/

- [CLI usage](https://docs.clusterless.io/reference/1.0-wip/index.html#commands)
- [Project components](https://docs.clusterless.io/reference/1.0-wip/index.html#components)
- [Project file format](https://docs.clusterless.io/reference/1.0-wip/index.html#models)

For example scenarios, see

- [How To](https://docs.clusterless.io/guide/1.0-wip/howtos/index.html) - step-by-step guides
- [clusterless-aws-example](https://github.com/ClusterlessHQ/clusterless-aws-examples) - simple examples to start with
- [aws-s3-log-pipeline](https://github.com/ClusterlessHQ/aws-s3-log-pipeline) - end-to-end sample pipeline for
  processing AWS S3 access logs
