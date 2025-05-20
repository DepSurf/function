# Function: <code>mls_context_init</code>

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
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff81351cec)
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff81355a3b)
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/services.c:string_to_context_struct
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
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff81387cec)
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff813902ea)
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff8139e79c)
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff813a6f0a)
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff813b407d)
Location: security/selinux/ss/context.h:35
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff813bd91d)
Location: security/selinux/ss/context.h:35
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff813da1cd)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff813e3a93)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
In security/selinux/ss/sidtab.c (ffffffff814088ff)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff8140a605)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8141425a)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
In security/selinux/ss/sidtab.c (ffffffff81424ca1)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81426a35)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff814307ba)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
In security/selinux/ss/sidtab.c (ffffffff81452891)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814541be)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8145e154)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (ffffffff8146c631)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8146df5e)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81477f04)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (ffffffff814c0cb6)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814c5993)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff814cd386)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (ffffffff814de776)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814e39e3)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff814eaaf1)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (ffffffff814e5149)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814ea3a3)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff814f1751)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
In security/selinux/ss/sidtab.c (ffffffff8153e816)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81543d54)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff8154bde2)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
In security/selinux/ss/sidtab.c (ffffffff815d6210)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff815dc62c)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff815e4c1b)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
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
In security/selinux/ss/sidtab.c (ffffffff816844e0)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8168b79f)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff8169403b)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
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
In security/selinux/ss/sidtab.c (ffffffff816bc850)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff816c3b0f)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff816cc58a)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
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
In security/selinux/ss/sidtab.c (ffffffff816f9380)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8170060f)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff81708946)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
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
In security/selinux/ss/sidtab.c (ffff80001055b50c)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffff80001055d418)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffff800010567edc)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (c070fcfc)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (c0711958)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (c071c284)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (c0000000006ba7d4)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (c0000000006bd048)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (c0000000006cb408)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (ffffffe0003b222c)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffe0003b3942)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffe0003bd942)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
In security/selinux/ss/sidtab.c (ffffffff81464c11)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8146653e)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff814704e4)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (ffffffff81455641)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81456f6e)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81460f04)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (ffffffff81460cb1)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814625de)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8146c584)
Location: security/selinux/ss/context.h:36
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
In security/selinux/ss/sidtab.c (ffffffff814784b1)
Location: security/selinux/ss/context.h:36
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81479dde)
Location: security/selinux/ss/context.h:36
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81483e06)
Location: security/selinux/ss/context.h:36
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
