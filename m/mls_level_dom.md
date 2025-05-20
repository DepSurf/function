# Function: <code>mls_level_dom</code>

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
In security/selinux/ss/services.c (ffffffff81355160)
Location: security/selinux/ss/mls_types.h:35
Inline: True
Inline callers:
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
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
In security/selinux/ss/mls.c (ffffffff8135bd82)
Location: security/selinux/ss/mls_types.h:35
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
```
**Symbols:**

```
ffffffff81355160-ffffffff8135517d: mls_level_dom.part.5 (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff813904dd)
Location: security/selinux/ss/mls_types.h:35
Inline: True
Inline callers:
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
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff81392269)
Location: security/selinux/ss/mls_types.h:35
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff8138b0e0-ffffffff8138b0fd: mls_level_dom.part.5 (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff813a70fd)
Location: security/selinux/ss/mls_types.h:35
Inline: True
Inline callers:
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
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff813a8e99)
Location: security/selinux/ss/mls_types.h:35
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff813a1cf0-ffffffff813a1d0d: mls_level_dom.part.5 (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff813bdac7)
Location: security/selinux/ss/mls_types.h:35
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff813bf969)
Location: security/selinux/ss/mls_types.h:35
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff813e3c53)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff813e5b09)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff81414425)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814166d9)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff814309ba)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff81432c09)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff8145e32f)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff81460630)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff814780df)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff8147a3e0)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cd58c)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
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
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff814cf980)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814eac62)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
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
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff814eceb0)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f18c2)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
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
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff814f3c50)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8154bf80)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
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
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff8154e600)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff815e4e61)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff815e76e4)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
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
In security/selinux/ss/services.c (ffffffff816942a1)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff81696dc4)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
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
In security/selinux/ss/services.c (ffffffff816cc886)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
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
In security/selinux/ss/mls.c (ffffffff816cf2bc)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
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
In security/selinux/ss/services.c (ffffffff81703308)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (ffffffff8170b8dc)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
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
In security/selinux/ss/services.c (ffff800010568110)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffff80001056a98c)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (c071c420)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
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
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
```
In security/selinux/ss/mls.c (c071e574)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (c0000000006cb6dc)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (c0000000006ce570)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffe0003bdb4a)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffe0003bf8ac)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff814706bf)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814729c0)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff814610df)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814633e0)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff8146c75f)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff8146ea60)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
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
In security/selinux/ss/services.c (ffffffff81483f7e)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
```
```
In security/selinux/ss/mls.c (ffffffff814862d0)
Location: security/selinux/ss/mls_types.h:36
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
</details>
</li>
</ul>

## Differences
