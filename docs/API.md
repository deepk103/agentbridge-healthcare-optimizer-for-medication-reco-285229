# API Documentation

## Endpoints
### Case Intake
- **Description**: Collect, validate and normalize device telemetry from EHR; attach a runId and timestamp for traceability.
- **Type**: Processing

### Plan
- **Description**: Execute plan phase for the ReAct pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Act
- **Description**: Execute act phase for the ReAct pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Plan Drafting
- **Description**: Plan Drafting across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Risk Scoring
- **Description**: Risk Scoring across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Intervention
- **Description**: Intervention across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Outcome Measurement
- **Description**: Assemble final payload with status, artifacts, KPIs and audit trail; store to CDI; return response JSON for the client.
- **Type**: Processing
