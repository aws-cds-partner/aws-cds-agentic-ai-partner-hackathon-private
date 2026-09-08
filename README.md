# Hackathon Submission Instructions

## Overview

To be evaluated, your submission must give our judging panel access to the source
code demonstrating your use of AWS CDS services.

Choose **one** of the options below.

| Option | Use when | Effort |
|---|---|---|
| **A — Public repository** ✅ *Recommended* | Code can be shared openly | Lowest |
| **B — Private repository + judge access** | Code must stay confidential | Medium |

---

## Option A — Public repository (recommended)

Host your code in a **public** repository on **GitHub** or **GitLab**.

1. Push your final code to the public repository.
2. Share the repo url directly in devpost

No access grants are needed. This is the fastest path.

---

## Option B — Private repository + judge access

### Step 1 — Prepare a private repository

Create a private repository containing **only** the code assets relevant to your
submission. Do not include unrelated proprietary code such videos or office documents.

### Step 2 — Grant access to the judging account

Add our judging account as a collaborator:

**Repository → Settings → Collaborators → Manage access → Add people →
type `aws-cds-partner` → Add**

Judging account: **aws-cds-partner**


> ⚠️ **Invitations expire after 7 days.** We accept promptly, but if yours
> expires before we do, please re-send it.

### Step 3 — Do not revoke access until 11/13/26

We  may need to re-check code during judging. **Revoking access early may impact your submission.**

### Step 4 — Submit

Submit formally in Devpost and provide the invitation link from Step 2.

---

### Important: GitHub permissions on private repositories

Please be aware of a GitHub platform limitation:

> On repositories owned by a **personal account**, GitHub does **not** offer a
> read-only collaborator role.

**Our written commitments to you:**

1. We will **never push, commit, force-push, merge, or delete** anything in your
   repository. Our access is used strictly to read and clone.
2. We evaluate the main branch in your submission, latest commit. 
3. We will remove ourselves as a collaborator once judging concludes.

---

## Security requirements (mandatory)
Responsibility for keeping credentials out of your repository rests with you.

Do not commit any credentials. Specifically:

❌ No AWS access keys, secret access keys, or session tokens
❌ No API keys, tokens, private keys, .pem files, or .env files
✅ Use IAM roles, OIDC, or short-lived credentials
✅ Provide a .env.example with placeholder values instead

Before submitting, scan your repository:

# Free and works locally on private repositories
https://github.com/awslabs/git-secrets
