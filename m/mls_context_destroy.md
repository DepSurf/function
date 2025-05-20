# Function: <code>mls_context_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8134ef7e)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff81351cda)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff81355a12)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:selinux_audit_rule_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81384f9e)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff81387cda)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff813902c4)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8139ba2e)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff8139e78a)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff813a6ee4)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff813b217e)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff813b4072)
Location: security/selinux/ss/context.h:105
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff813bd8f7)
Location: security/selinux/ss/context.h:105
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff813d82be)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff813da1c2)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff813e3a6d)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff814088f1)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff8140a5f7)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8141424c)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff81424c93)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81426a27)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff814307ac)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff81452883)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814541af)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8145e146)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff8146c623)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8146df4f)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81477ef6)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff814c0ca8)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814c5984)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff814cd378)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff814de768)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814e39d4)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff814eaae2)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff814e513b)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814ea394)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff814f1742)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff8153e808)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81543d45)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff8154bdd3)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff815d6202)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff815dc61e)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff815e4c0d)
Location: security/selinux/ss/context.h:138
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff816844d2)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8168b791)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff8169402d)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff816bc842)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff816c3b01)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff816cc57b)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff816f9372)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81700601)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff817088ce)
Location: security/selinux/ss/context.h:139
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffff80001055b4fc)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffff80001055d408)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffff800010567ecc)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (c070fcf0)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (c071194c)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (c071c278)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (c0000000006ba7bc)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (c0000000006bd034)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (c0000000006cb3f4)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffe0003b220e)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffe0003b3922)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffe0003bd922)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff81464c03)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8146652f)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff814704d6)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff81455633)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81456f5f)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81460ef6)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff81460ca3)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814625cf)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8146c576)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
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
In security/selinux/ss/sidtab.c (ffffffff814784a3)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81479dcf)
Location: security/selinux/ss/context.h:106
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81483df8)
Location: security/selinux/ss/context.h:106
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
```
</details>
</li>
</ul>

## Differences
