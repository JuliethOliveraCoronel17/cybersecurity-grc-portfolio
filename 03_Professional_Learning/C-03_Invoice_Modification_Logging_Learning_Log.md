# Learning Log — C-03: Invoice Modification Logging

**Reference:** NIST SP 800-53 Rev. 5 — AU-3, Content of Audit Records

### 1. What I learned

AU-3 explains that audit records should contain information that helps establish what event occurred, when and where it occurred, its source and outcome, and the identities of individuals, subjects, or objects associated with the event.

In the invoice modification scenario, relevant information includes the invoice affected, the action performed, the date and time, the associated user or process, and whether the action succeeded or failed.

The user account associated with an event does not necessarily prove which individual performed the action, especially if the account may have been compromised.

### 2. Evidence I would request

I would request an export of invoice modification logs for a defined review period, relevant logging configuration documentation, and a sample of modified invoices with their corresponding audit records.

Depending on the system, I would examine event descriptions, timestamps, user or process identifiers, event outcomes, and the invoice or fields affected. I would also seek evidence of how access to logs is restricted and how their integrity is protected.

### 3. Evidence limitations

The available records may not show exactly which invoice fields changed or their previous and new values. A user identifier does not necessarily establish the identity of the person who performed the action. The records may also be incomplete, altered, or insufficient to demonstrate consistent operation over time.

Further testing and corroborating evidence may therefore be necessary before concluding that the control is effective.

**Scope note:** This is a learning exercise based on a hypothetical scenario. No actual company system or audit evidence has been examined.

### 4. Sampling Approach — Planned Test

### Sampling Approach — C-03 Invoice Modification Logging

- **Population:** 100 hypothetical invoice modification records.
- **Sample size:** 10 records.
- **Selection method:** Random selection.
- **Purpose:** To practice assessing whether selected invoice modification records contain sufficient information to support investigation.
- **Rationale:** Ten records provide a manageable sample for an educational exercise and allow the reviewer to practice applying the defined test criteria.
- **Limitation:** This is a non-statistical educational exercise. The sample size does not establish statistical representativeness or support a conclusion that all records, or the control as a whole, are effective.

**Scope note:** The population and records are fictitious. No actual company records have been examined. Additionally, this is an educational simulation, and the test has not been performed yet.
