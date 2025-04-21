# ADR-004: Monitoring and Logging
- Decision: Use CloudWatch Logs, Metrics, and Alarms + SNS for alerts
- Context: Observability is required for debugging, uptime, usage limits, and system health.
- Alternatives Considered: Datadog, Prometheus + Grafana.
- Justification: Fully AWS-native, minimal overhead, integrates with ECS and API Gateway.
- Consequences: Requires proper IAM roles and alarm tuning for noise reduction.
