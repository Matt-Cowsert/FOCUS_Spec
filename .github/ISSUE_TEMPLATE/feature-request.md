### 🧠 Problem Statement
Describe the problem, issue, or opportunity this feature addresses. Include practitioner quotes or real-world examples if available.

```
[Write your problem statement here.]
```

---

### 🧪 Use Case (Required)
Provide a specific, real-world scenario. Use this format:

**Practitioner Profile**: [e.g., FinOps Analyst at 500-person SaaS company]  
**Current Challenge**: [What specific problem do they face today?]  
**Desired Workflow**: As a [role], I want to [specific behavior], so that [measurable outcome].  
**Success Criteria**: [How will the practitioner know this feature works?]

**Example Scenario**: Provide a concrete example with sample data/values if possible.

---

### 🚀 Adoption Impact (Required)
Which category best describes this feature's impact on FOCUS adoption?

- [ ] **Adoption Blocker** – Organizations cannot adopt FOCUS without this feature
- [ ] **Adoption Accelerator** – This feature would help organizations start using FOCUS
- [ ] **Practitioner Enhancement** – Improves experience for existing FOCUS users  
- [ ] **Technical Improvement** – Internal specification refinement

**Justification**: Explain why this categorization applies (1-2 sentences)

---

### 🎯 Implementation Scope
- [ ] **MVP Only** – Minimum viable implementation to solve the core problem
- [ ] **MVP + Extensions** – Core feature with optional enhancements  
- [ ] **North Star** – Comprehensive solution (may be implemented in phases)

**MVP Definition**: Describe the minimum implementation that would provide value
**North Star Vision**: Describe the ideal complete solution

---

### 💼 Business Value Assessment
**Cost Savings Potential**: [e.g., "Could help practitioners identify 10-15% waste reduction"]  
**Time Savings**: [e.g., "Eliminates 2-4 hours of weekly manual data normalization"]  
**Risk Reduction**: [e.g., "Reduces billing reconciliation errors by providing standardized invoice data"]  
**Organizational Scale**: [e.g., "Most valuable for enterprises with >$1M cloud spend"]  

**Adoption Enablement**: How many organizations would this help start using FOCUS? [Estimate with reasoning]

---

### 🏗️ Provider Implementation Readiness
Check all that apply and provide evidence of providers that currently support this:

**Current Provider Support**:
- [ ] AWS supports this ✓ [link to documentation]
- [ ] Azure supports this ✓ [link to documentation]  
- [ ] GCP supports this ✓ [link to documentation]
- [ ] Other providers: [list]

**Implementation Complexity**:
- [ ] **Existing Data** – Providers already expose this data
- [ ] **Data Transformation** – Requires processing existing provider data
- [ ] **New Data Collection** – Providers would need to collect new metrics
- [ ] **Provider Changes** – Requires provider system modifications

---

### 🔧 FOCUS Supported Features Alignment
Which existing or new [FOCUS Supported Features](https://focus.finops.org/focus-specification/#supported-features) does this request enable or enhance?

**Existing Features Enhanced**:
- [ ] Cost and Usage Attribution
- [ ] Charge Categorization  
- [ ] Effective Cost
- [ ] [Other - specify]

**New Features Enabled**:
- [ ] [Describe new supported feature this would enable]

**Feature Description**: [1-2 sentences describing how this request advances FinOps capabilities]

---

### 📨 Type of Request
How would you categorize this request? Select the option that best describes the novelty or source of the idea.

- [ ] Refinement of an existing FOCUS attribute
- [ ] Addition of a provider-supported field not yet in FOCUS
- [ ] Net-new concept (not currently supported by providers or FOCUS)
- [ ] Supporting Content (e.g., appendices, use cases)

---

### 🏛️ Organizations Requesting This Feature
List one or more organizations who have requested or explicitly supported this request (including your own, if applicable).

```
[e.g., BigCloud Inc, Acme Corp]
```

---

### 🌐 FinOps Scope Alignment (Optional)
Does this request align with one or more of the following [FinOps Scopes](https://www.finops.org/framework/scopes/)?

- [ ] Public Cloud – e.g., AWS, Azure, GCP, OCI
- [ ] Software-as-a-Service (SaaS) – e.g., Salesforce, Snowflake
- [ ] Data Center – on-prem compute and infrastructure
- [ ] Licensing – subscription or usage-based licensing models *(under development)*
- [ ] AI – cost and usage for AI models and platforms *(under development)*
- [ ] Custom – internal tooling, specialized infra *(under development)*

---

### 📊 Impacted Parties
Which roles or systems would be directly affected by this request? (Check all that apply)

- [ ] FinOps Practitioner – end users who analyze or act on the data
- [ ] FOCUS Data Generator – providers generating output aligned to the spec
- [ ] Vendor Supporting FOCUS – vendors or tools ingesting the spec or using the spec language in their UI
- [ ] Other (please explain in comments)

---

### 🌫️ Level of Ambiguity
How clearly defined is the request? Rate from 1 to 5:
- 1 = very well-defined, low complexity
- 3 = moderately scoped, some ambiguity
- 5 = vague, high complexity or conceptual

```
[e.g., 2]
```

---

### 📂 Other Supporting Documentation
Include links to data samples, relevant PRs, GitHub discussions, or implementation references.

> 🔐 **Reminder:** Please ensure any linked documents are accessible to maintainers and collaborators. If access is restricted, your request may be delayed.

```
[Paste links here.]
```

---

### 🛠️ Proposed Solution / Approach
Share initial ideas, constraints, and feasibility considerations.

```
[Your proposal goes here.]
```

---

### 💬 Community Support (Add Your Voice)
If your organization supports this request or has a similar use case:

- Add a **comment** below including:
  - Your **organization**
  - A **brief explanation** of why this is important to you (e.g., use case, urgency)
- FOCUS Staff & Maintainers will aggregate supporting orgs over time.

---

## Other Process Improvements

### Pre-Review Checklist
Add a checklist for maintainers during issue triage. Example:
- [ ] Problem Statement is specific and measurable.
- [ ] Use case includes a concrete example scenario.
- [ ] Adoption Impact is clearly categorized.
- [ ] Provider readiness is documented.
- [ ] Business Value is quantified.

### Issue Labels Enhancement
Based on issues filed in v1.4:
- `adoption-blocker`, `adoption-accelerator`, `practitioner-enhancement`
- `mvp-ready`, `needs-scoping`, `north-start`
- `provider-ready`, `needs-provider-work`, `data-gap`

### Common Mistakes 
> ❌ **Avoid**: Vague problem statements like "improve cost visibility"
> ✅ **Better**: "Practitioners cannot reconcile cloud bills with FOCUS data because invoice identifiers are missing"
