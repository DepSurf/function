# Function: <code>mls_level_eq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81350e3c)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff81355140)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff8135b83b)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_sid_to_context
```
**Symbols:**

```
ffffffff81355140-ffffffff8135515b: mls_level_eq.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81386e9c)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff81390501)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff813919eb)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff8138b0c0-ffffffff8138b0db: mls_level_eq.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139d94c)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff813a7121)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff813a861b)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff813a1cd0-ffffffff813a1ceb: mls_level_eq.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b439c)
Location: security/selinux/ss/mls_types.h:29
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff813bdb9c)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff813bf33b)
Location: security/selinux/ss/mls_types.h:29
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813da4ec)
Location: security/selinux/ss/mls_types.h:30
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff813e3d2b)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff813e54f5)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8140a8ad)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff81414583)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814160c5)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81426d1d)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff81430a70)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff81432895)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814545ee)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff8145e400)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814602df)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146e38e)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff814781b0)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff8147a08f)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff814cd65d)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814cf668)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff814c7de0-ffffffff814c7dfb: mls_level_eq.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff814eac84)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814ecb9c)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff814e5c00-ffffffff814e5c1b: mls_level_eq.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff814f18e4)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814f3936)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff814ec4d0-ffffffff814ec4eb: mls_level_eq.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff8154bfa2)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff8154e2ba)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff81546120-ffffffff8154613b: mls_level_eq.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815d9f53)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff815e4e84)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff815e7056)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816869f3)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff816942c4)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff816966cc)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816bf5b3)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff816cc7f6)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff816cebc7)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fbdf3)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff81703285)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff8170b1e7)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055da5c)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffff800010568238)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffff80001056a554)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0711e00)
Location: security/selinux/ss/mls_types.h:30
Inline: True
```
```
In security/selinux/ss/services.c (c071c630)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (c071e198)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006bd734)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (c0000000006cb95c)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (c0000000006cdf60)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b412c)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffe0003bda92)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffe0003bf52a)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146696e)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff81470790)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff8147266f)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8145739e)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff814611b0)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff8146308f)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81462a0e)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff8146c830)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff8146e70f)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8147a20e)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/services.c (ffffffff8148404f)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff81485f7f)
Location: security/selinux/ss/mls_types.h:30
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
</ul>

## Differences
