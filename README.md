# Hackathon Submission Instructions

> **Submission deadline:** `<DATE, TIME, TIMEZONE>`
> **Access must remain active until:** `<DATE — at least 14 days after judging ends>`
> **Questions:** `<CONTACT EMAIL>` or open an issue in this repository.

## Overview

To be evaluated, your submission must give our judging panel access to the source
code demonstrating your use of AWS CDS services.

Choose **one** of the options below.

| Option | Use when | Effort |
|---|---|---|
| **A — Public repository** ✅ *Recommended* | Code can be shared openly | Lowest |
| **B — Private repository + judge access** | Code must stay confidential | Medium |
| **C — Signed archive** | Your GitHub org blocks external collaborators | Highest |

---

## Option A — Public repository (recommended)

Host your code in a **public** repository on **GitHub** or **GitLab**.

1. Push your final code to the public repository.
2. Note the **exact commit SHA** you want judged.
3. Submit via the form below.

No access grants are needed. This is the fastest and most reliable path, and it
means your repository benefits from free automated secret scanning.

---

## Option B — Private repository + judge access

### Step 1 — Prepare a private repository

Create a private repository containing **only** the code assets relevant to your
submission. Do not include unrelated proprietary code.

### Step 2 — Grant access to the judging account

Add our judging account as a collaborator:

**Repository → Settings → Collaborators → Manage access → Add people →
type `aws-cds-partner` → Add**

Judging account: **https://github.com/aws-cds-partner**

> ⚠️ **Invite by username (`aws-cds-partner`), not by email address.**
> Email-based invitations fail unless the address is verified on the account,
> and they behave differently for billing.

> ⚠️ **Invitations expire after 7 days.** We accept promptly, but if yours
> expires before we do, please re-send it.

### Step 3 — Do not revoke access until `<DATE>`

We re-verify access at the deadline and may need to re-check code during
judging and any dispute resolution. **Revoking access early may disqualify
your submission.**

### Step 4 — Submit

Complete the submission form below, including your declared commit SHA.

---

### Important: GitHub permissions on private repositories

Please be aware of a GitHub platform limitation:

> On repositories owned by a **personal account**, GitHub does **not** offer a
> read-only collaborator role. Any collaborator you add necessarily receives
> **write** access.

**Our written commitments to you:**

1. We will **never push, commit, force-push, merge, or delete** anything in your
   repository. Our access is used strictly to read and clone.
2. We evaluate **only the commit SHA you declare** in your submission. We record
   that SHA independently at the deadline, so your submission is verifiable and
   tamper-evident.
3. We will remove ourselves as a collaborator once judging concludes.

**If you require true read-only access**, host the repository in a **GitHub
organization** (free organizations support a full role matrix) and grant
`aws-cds-partner` the **Read** role instead. This is the preferred setup where
your policies allow it.

> 💡 **If your repository is owned by an organization on a paid GitHub plan**
> (Team or Enterprise), adding an external collaborator to a private repository
> **consumes a licensed seat on your organization's bill**. Please confirm this
> is acceptable before proceeding, or use Option A or C.

---

## Option C — Signed archive (fallback)

Use this **only** if your GitHub organization uses Enterprise Managed Users or
otherwise prohibits adding external collaborators — in which case Option B is
technically impossible for you.

1. Produce a complete archive that preserves history:
   
