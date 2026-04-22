---
sidebar_position: 13
sidebar_label: "AI Handbook & Policies"
---

# AI Handbook & Policies

The AI Handbook Generator drafts Canadian HR policies tailored to your company and the provinces your employees work in, then compiles them into a signed PDF employee handbook with full acknowledgement tracking. This module combines three things most Canadian SMBs buy separately: policy templates, handbook compilation, and employee e-signature capture.

> **[Screenshot: Policies list view with a mix of draft and published policies]**

---

## Overview

The module lives at **Handbook & Policies** in the left sidebar (indented under Compliance, admin-only). It is organized into two tabs:

| Tab | Purpose |
|-----|---------|
| **Policies** | Generate, edit, publish, and archive individual policies |
| **Handbook Archive** | Every compiled handbook version, with download + acknowledgement tracking |

A persistent banner at the top of the page reminds you of the legal posture: Hibiscus HR drafts with AI assistance, you certify the final content with counsel before publishing.

---

## How It Works

1. **You generate** a policy from a library of 15 Canadian templates (vacation, sick leave, parental leave, harassment, overtime, right-to-disconnect, termination, and more).
2. Hibiscus HR drafts the policy using Claude, grounded in the statutory minimums for the provinces your employees work in. No generic US template — every draft references the actual ESA rules for Ontario, BC, Quebec, Alberta, etc. where your staff are located.
3. **You edit** the draft in a split-pane editor (markdown source + rendered preview) until it reads the way your organization wants it to.
4. **You certify** with counsel before publishing. A required attestation step captures that your legal counsel has reviewed the policy.
5. **You compile** selected published policies into a single handbook PDF with cover page, table of contents, and employee acknowledgement signature page.
6. **Employees sign** by typing their name in the Employee Portal. IP, timestamp, and typed name are logged for the audit trail.

---

## Generating a New Policy

From the Policies tab, click **Generate Policy** (top right). A dialog opens with all 15 available policy types.

### The 15 Policy Types

| Category | Policy | What it covers |
|----------|--------|----------------|
| Time off | Vacation & Time Off | Annual entitlement, accrual, booking, carry-over, payout on termination |
| Time off | Sick Leave | Personal illness days, notification, medical certificates |
| Time off | Bereavement Leave | Family death, eligible relationships, documentation |
| Time off | Parental & Pregnancy Leave | Maternity, parental, adoption; EI vs QPIP handling |
| Time off | Statutory Holidays | Recognized holidays, pay treatment, working-the-holiday rules |
| Work rules | Overtime & Hours of Work | Daily/weekly thresholds, overtime rates, time-off-in-lieu |
| Work rules | Right to Disconnect | Ontario Bill 27-compliant disconnect policy |
| Work rules | Remote & Hybrid Work | Eligibility, equipment, hours, health & safety |
| Workplace | Harassment & Discrimination | Complaint process, investigation, retaliation protection |
| Workplace | Code of Conduct | Expected behaviour, conflicts of interest, resource use |
| Employment | Termination & Resignation | Notice periods, final pay, return of property |
| Employment | Performance Management | Reviews, goals, improvement process |
| Employment | Confidentiality & IP | Confidential information, IP ownership, NDA |
| Compliance | Privacy & Data Handling | Employee data, PIPEDA, monitoring, access rights |
| Compliance | Benefits Overview | Health, dental, group benefits, RRSP matching |

### Picking a Policy Type

Click a policy card to select it. If your organization already has a draft or published version of that policy type, you'll see an **"Existing"** badge — regenerating preserves the old version in history but replaces the active content with a new AI draft.

> **[Screenshot: Generate Policy modal showing the 15 policy cards]**

### What Hibiscus HR Uses to Draft

Behind the scenes, Hibiscus HR pre-fills:

- **Your company name** (from Settings → Company)
- **Your industry** (from Settings → Company)
- **Provinces your employees actually work in** (auto-detected from your Employees module — only provinces where you have active employees)
- **Your statutory minimums for each of those provinces** (Hibiscus HR keeps the 2026 ESA rules current for all 10 provinces plus federal)

Click **Generate**. Generation takes 15–30 seconds. The page navigates to the policy editor when the draft is ready.

---

## Editing a Policy

The policy editor opens as a full page with three view modes:

| View | What it shows |
|------|---------------|
| **Edit** | Markdown source only (full width) |
| **Split** | Markdown source (left) + rendered preview (right) — default |
| **Preview** | Rendered preview only (full width) |

Toggle at the top right of the editor.

> **[Screenshot: Policy editor in Split view — markdown on left, formatted preview on right]**

### Making Edits

Click anywhere in the markdown source pane and type. The preview updates live. Save your changes with the **Save** button (top right). A "Saved" confirmation appears when your edits are committed.

Every save adds the previous version to version history. You cannot lose prior content — it is always recoverable.

### Editing a Published Policy Reverts It to Draft

**Important:** if you edit a policy that is currently published, saving the change automatically flips it back to draft status. This is deliberate. The certification you issued applied to the previous content, not the edited version. To make the edited policy live again, you need to click **Certify & Publish** a second time to re-certify.

You'll see a toast: *"Saved. Policy moved back to draft — re-certify to re-publish."*

### Regenerating from Scratch

The **Regenerate** button (top right) discards the current draft and generates a fresh AI draft. The current content is preserved in version history — you can always recover it. Regeneration is useful if you've made heavy edits and want to start fresh, or if your staff composition has changed (e.g., you added a Quebec employee after drafting with only Ontario employees).

---

## Publishing a Policy (Certification Workflow)

Publishing makes a policy available in the Employee Portal and eligible for inclusion in a compiled handbook. **Before a policy can be published, your organization certifies that it has been reviewed by legal counsel.**

### The Certification Modal

Click **Certify & Publish** (top right, visible on draft policies). A modal appears with:

1. **A warning banner** — publishing makes the content your organization's official policy
2. **The certification statement** — you attest that qualified Canadian employment counsel has reviewed the policy
3. **Optional counsel name and firm fields** — capturing your counsel's identity significantly strengthens the audit trail if the certification is ever challenged. Firm names appear on compiled handbook PDFs.
4. **Certify & Publish button** — disabled until you've checked the certification box

> **[Screenshot: Certify & Publish modal with the certification statement, counsel fields, and action buttons]**

### What Gets Recorded

When you click Certify & Publish, Hibiscus HR captures:

- **The user who certified** (from their login)
- **Timestamp of certification**
- **Counsel name** (if provided)
- **Counsel firm** (if provided)
- **The exact policy content at the moment of certification** (preserved in the version history + handbook snapshots)

A green banner then appears at the top of the policy: *"Customer-certified for publication. Counsel: [Firm]. Certified [timestamp]."*

### Unpublishing

If you need to retract a published policy, click **Unpublish**. This removes it from the Employee Portal and excludes it from new handbook compilations. Certification fields are retained in version history — they are not erased, they are simply no longer the "current" certification.

---

## Compiling a Handbook

The **Compile Handbook** button (top right on the Policies tab) assembles selected published policies into a single PDF.

### Compile Dialog

Click Compile Handbook. A dialog lists all your currently published policies, all checked by default.

> **[Screenshot: Compile Handbook dialog with checkboxes next to each published policy]**

- **Selection** — uncheck any policies you want to exclude from this compilation (e.g., if you're preparing a role-specific handbook subset)
- **Order** — policies are compiled in the display order shown; drag-and-drop reordering is on the roadmap
- **Compile & Download** — kicks off the compile

### What the Handbook PDF Contains

1. **Cover page** — your company name, "Employee Handbook", version number, date, and (if counsel was identified on any included policy) a line like *"Reviewed by [Firm name]"*
2. **Table of contents** — every included policy, in order
3. **The policy sections** — each policy rendered with a section header, title, and full content
4. **Acknowledgement signature page** — text for employees to sign + date, plus space for printed name and employee ID

The PDF downloads to your computer. A record of the compilation is simultaneously archived in the Handbook Archive tab.

---

## Handbook Archive

The **Handbook Archive** tab shows every compiled handbook version your organization has created.

> **[Screenshot: Handbook Archive with several compiled versions listed]**

Each row shows:

| Field | Description |
|-------|-------------|
| Version | Auto-incremented per compilation (v1, v2, v3…) |
| Title | Usually "Employee Handbook" unless you renamed it |
| Policies included | Count of policies in that specific version |
| Signed count | Number of employees who have acknowledged that exact version |
| Compiled | Timestamp of compilation |
| Download | Re-render the PDF from the current policy content |

### Click the Icon to Expand Acknowledgements

Each row with at least one acknowledgement is expandable. Click the archive icon to see the full list of employees who have signed that specific handbook version, with their typed e-signature name, IP address, and timestamp.

This is your audit trail. If a termination or human-rights dispute ever turns on "did the employee acknowledge this policy," the record is here.

### Re-downloading

The Download button on any archive row re-renders the PDF from the current published policy content. Note: if the underlying policy has been edited since that version was compiled, the re-downloaded PDF will reflect the updated content, not the historical version. The version_history on each policy preserves the exact content at compile time for legal reconstruction if needed.

---

## Employee Acknowledgement

Employees access their handbook via the Employee Portal.

### Employee View

When an employee visits **Employee Portal → Handbook**, they see:

- The current compiled handbook, fully readable inline
- A top banner indicating whether they have acknowledged the current version
- If not yet acknowledged: a typed-name signature form at the bottom
- If already acknowledged: a green confirmation with the date they signed

> **[Screenshot: Employee Portal Handbook page with the signature form at the bottom]**

### Signing Process

1. Employee reads the handbook content (all policies rendered inline in sequence)
2. Types their full legal name in the signature field at the bottom (pre-filled with their display name — they can edit)
3. Clicks **I Acknowledge**
4. Submission is stamped with their IP address, browser user agent, and timestamp
5. Employee sees: *"Signed as [name] on [timestamp]."*

The employee cannot sign the same version twice — subsequent attempts return "Already on file — thank you."

---

## Viewing Acknowledgements (Admin)

Admins can view all acknowledgements for any handbook version from the **Handbook Archive** tab.

1. Navigate to Handbook & Policies → Handbook Archive
2. Click the archive icon on any row showing a "signed" count
3. See the full list of employees who signed, with typed name, IP, and timestamp

If an employee's name doesn't match their profile name, the audit shows *"signed as [typed name]"* so you can see exactly what they typed.

---

## Legal Framework

Hibiscus HR's AI Handbook Generator operates on a **customer-certification model**, which means:

- **Hibiscus HR provides** AI-drafted templates grounded in current Canadian ESA rules
- **You certify** (via the in-product certification step) that you have reviewed the policy with qualified Canadian employment counsel before publishing
- **Final legal responsibility** for published content rests with your organization

This is industry-standard for legal and HR SaaS. The certification step + counsel identification creates a legally-defensible audit trail. The EULA explicitly details this allocation.

### When to Actually Involve a Lawyer

Not every policy needs the same level of review. Our recommendation:

- **Always review with counsel:** Harassment & Discrimination, Termination & Resignation, Parental Leave (especially Quebec), Remote & Hybrid Work
- **Spot-check:** Overtime, Privacy & Data Handling, Confidentiality & IP
- **Standard template review:** Vacation, Sick Leave, Bereavement, Stat Holidays

Hibiscus HR keeps the statutory references current (ESA revisions are reviewed annually in December for each calendar year). You review with counsel the voice, structure, and specifics relevant to your business.

---

## Tips & Best Practices

- **Regenerate when your workforce changes provinces.** If you hire your first employee in a new province, open affected policies and click Regenerate so the new province's rules are incorporated.
- **Keep handbook versions aligned with material changes.** When you revise more than a handful of policies, compile a new handbook version so employees see the fresh bundle and the acknowledgement is tied to the updated content.
- **Use firm-name counsel fields.** Filling in your reviewing firm's name materially strengthens the certification trail. A blank counsel field still counts as a certification, but an identified firm is harder to challenge.
- **Re-compile annually.** Canadian ESA rules change. Around January each year, spot-check your published policies, regenerate where statutory details have shifted, and compile a new handbook version.
- **Don't mass-unpublish during business hours.** If a policy needs retraction, do it off-hours so employees don't get a mid-day gap in the handbook they're trying to reference.

---

## Related Docs

- [Employee Portal](./employee-portal.md) — employee-side handbook viewing + acknowledgement
- [Compliance](./compliance.md) — how policies interact with the Compliance module's audit dashboard
- [Settings](./settings.md) — Company details that pre-fill policy drafts
