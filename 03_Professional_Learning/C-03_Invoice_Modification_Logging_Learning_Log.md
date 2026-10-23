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

# Learning Log — C-03: Invoice Modification Logging

**Reference:** NIST SP 800-53 Rev. 5 — AU-3, Content of Audit Records

## 1. What I Learned

NIST SP 800-53 Rev. 5, control AU-3, addresses the information that audit records should contain to help establish what event occurred, when and where it occurred, its source and outcome, and the identities of individuals, subjects, or objects associated with the event.

In the invoice modification scenario, relevant information may include the invoice affected, the action performed, the date and time, the associated user or process, and whether the action succeeded or failed.

The user account associated with an event does not necessarily prove which individual performed the action, especially if the account may have been compromised.

## 2. Evidence I Would Request

I would request:

- An export of invoice modification logs for a defined review period.
- Relevant audit logging configuration documentation.
- A sample of modified invoices and their corresponding audit records, where available.
- Evidence of access restrictions and integrity protections applied to audit logs, where relevant.

Depending on the system, I would examine event descriptions, timestamps, user or process identifiers, event outcomes, and the invoices or fields affected.

## 3. Evidence Limitations

The available records may not show exactly which invoice fields changed or their previous and new values.

A user identifier does not necessarily establish the identity of the individual who performed the action. The records may also be incomplete, altered, or insufficient to demonstrate consistent operation over time.

Further testing and corroborating evidence may therefore be necessary before concluding that the control is effective.

## 4. Control Test Objective

**Objective:** To determine whether the invoice modifications examined are recorded with sufficient information to support investigation.

C-03 is treated as a detective control in this educational scenario. Logging can support investigation of invoice modifications, but it does not, by itself, prevent unauthorized changes.

## 5. Preliminary Evaluation Criteria

- **CR-01 — Event Identification:** The record indicates that an invoice modification occurred.
- **CR-02 — Date and Time:** The record contains a usable event timestamp.
- **CR-03 — Associated Identity:** The record identifies the associated user or process.
- **CR-04 — Affected Object:** The record identifies the invoice or affected object.
- **CR-05 — Event Outcome:** The record indicates whether the event succeeded or failed, where applicable.
- **CR-06 — Change Details:** The record provides details of the modification, including previous and new values where supported by the system and available in the evidence.

These are tailored criteria for this educational scenario. They should not be interpreted as a claim that every system must record every field in exactly the same way.

## 6. Sampling Approach

- **Population:** 100 hypothetical eligible invoice modification records.
- **Review Period:** September 1–30, 2026.
- **Planned Sample Size:** 10 records.
- **Selection Method:** Random selection without replacement.
- **Purpose:** To practice evaluating whether selected records contain sufficient information to support investigation.

The sample size is a practical choice for this educational exercise. It is not a statistically validated sample size and does not establish statistical representativeness.

The population's completeness should be corroborated where possible. If completeness cannot be verified, the limitation must be documented and the conclusions appropriately restricted.

## 7. Inclusion and Exclusion Rules

**Include:**
- Events related to invoice modifications during the defined review period.
- Successful and failed events, if both are available in the relevant records.

**Exclude:**
- Events unrelated to invoice modifications, such as unrelated login events.

Potential duplicates must be investigated before sampling to determine whether they represent duplicate records or distinct events.

The planned population of 100 records is hypothetical and assumes that the eligibility rules have been applied.

## 8. Evidence Traceability

For each evidence item, the workpaper should document:

- Evidence ID.
- Evidence description.
- Source system or location.
- Period covered.
- Evaluation criteria supported.
- Relevant limitations.

An extract containing 100 records does not, by itself, demonstrate that all invoice modifications during the period were recorded.

Where possible, the log population should be compared with an appropriate independent source, such as an invoice version history or transaction record. The reliability and completeness of that source must also be considered.

## 9. Exception Handling and Evaluation Results

Each criterion will be evaluated using one of the following statuses:

- **Pass:** Available evidence demonstrates that the criterion is met.
- **Fail:** Available evidence demonstrates that the criterion is not met.
- **Not Verifiable:** Available evidence is insufficient to determine whether the criterion is met.

Selected records with exceptions will remain in the sample. Exceptions will be documented and investigated where necessary; they will not be replaced simply because they do not meet a criterion.

An exception in one record does not automatically establish that the entire control is ineffective. Conclusions must consider the evidence, the nature and extent of the exception, and the limitations of the test.

## 10. Control Test Design Status

**Status:** Design completed; testing has not yet been performed.

The test objective, review period, planned population, sample size, random sampling method, evaluation criteria, evidence requirements, exception-handling approach, and population completeness procedure have been defined.

The exercise uses a hypothetical population of 100 eligible invoice modification records for September 1–30, 2026, with a planned random sample of 10 records selected without replacement.

The population's completeness must be corroborated where possible. Any limitations will be documented, and conclusions will be restricted to what the available evidence supports.

**Scope Note:** This is an educational simulation. No actual company records or control evidence have been examined.
