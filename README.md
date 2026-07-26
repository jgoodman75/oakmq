# OakMQ

OakMQ is a lean, hardened message broker supporting OpenWire and STOMP.  OakMQ is not affiliated with Apache ActiveMQ.

NOTE: OakMQ is under development and is non-functional at this time. Use at your own risk.


## Project goals

### 1. Minimal footprint

Remove optional modules, protocols, examples, web consoles, and unused
dependencies.

### 2. OpenWire and STOMP support

Provide reliable interoperability for existing OpenWire and STOMP clients.

### 3. Secure by default

Require authentication, disable unsafe defaults, minimize exposed services,
and use modern TLS configuration.

### 4. Reduced attack surface

Include only the components necessary to operate the broker.

### 5. Compliance readiness

Support hardened deployments, Iron Bank submission requirements, STIG-aligned
configuration, and documented security controls.

### 6. Transparent dependencies

Maintain a complete software bill of materials (SBOM), dependency inventory,
license report, and vulnerability record.

### 7. Reproducible builds

Produce traceable artifacts from pinned source code and dependencies using a
repeatable build process.

### 8. Minimal container image

Publish a non-root OCI image containing only the runtime and required OakMQ
components.

### 9. Continuous security verification

Run static analysis, dependency scanning, container scanning, secret detection,
and automated tests in CI.

### 10. Reliable messaging

Preserve durable queues, topics, acknowledgements, transactions, persistence,
redelivery, and dead-letter handling.

### 11. Operational simplicity

Make configuration, deployment, monitoring, backup, and upgrades
straightforward.

### 12. Observable operation

Provide health checks, structured logs, metrics, and audit-relevant events
without requiring a web console.

### 13. Compatibility with existing clients

Avoid unnecessary protocol changes and clearly document compatibility with
supported Apache ActiveMQ client versions.

### 14. Predictable performance

Establish repeatable benchmarks for startup time, memory consumption, latency,
and throughput.

### 15. Responsible upstream maintenance

Track Apache ActiveMQ security fixes, preserve license and attribution
requirements, and contribute generally useful fixes upstream when practical.

### 16. Clear project identity

Operate as an independent Apache-licensed project without implying endorsement
by the Apache Software Foundation.

## Project identity

OakMQ is an independent project derived from Apache ActiveMQ. It is not
affiliated with or endorsed by the Apache Software Foundation.


