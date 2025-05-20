# Function: <code>context_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8134ef7e)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff81351ccc)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff813559f0)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:selinux_audit_rule_init
```
**Symbols:**

```
ffffffff813559f0-ffffffff81355a64: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81384f9e)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff81387ccc)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff8139029f)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
```
**Symbols:**

```
ffffffff8138b710-ffffffff8138b784: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8139ba2e)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff8139e77c)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
```
```
In security/selinux/ss/services.c (ffffffff813a6ebf)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
```
**Symbols:**

```
ffffffff813a2320-ffffffff813a2394: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813b217e)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff813b4063)
Location: security/selinux/ss/context.h:141
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff813bd8db)
Location: security/selinux/ss/context.h:141
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
```
**Symbols:**

```
ffffffff813b8cb0-ffffffff813b8d1e: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813d82be)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff813da1b3)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff813e3a51)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
```
**Symbols:**

```
ffffffff813dee20-ffffffff813dee8e: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814088da)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
```
```
In security/selinux/ss/policydb.c (ffffffff8140a5b5)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8141421f)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
```
**Symbols:**

```
ffffffff8140f370-ffffffff8140f3de: context_destroy (STB_LOCAL)
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
In security/selinux/ss/sidtab.c (ffffffff81424c63)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814269e5)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81430793)
Location: security/selinux/ss/context.h:142
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
In security/selinux/ss/sidtab.c (ffffffff81452853)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81454165)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8145e12d)
Location: security/selinux/ss/context.h:142
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
In security/selinux/ss/sidtab.c (ffffffff8146c5f3)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8146df05)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81477edd)
Location: security/selinux/ss/context.h:142
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
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814c0c78)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814c594e)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
```
```
In security/selinux/ss/services.c (ffffffff814cd35f)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff814c2280-ffffffff814c22ee: context_destroy (STB_LOCAL)
ffffffff814c7d20-ffffffff814c7d8e: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814de738)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814e399e)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
```
```
In security/selinux/ss/services.c (ffffffff814eaaaf)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff814dfce0-ffffffff814dfd4e: context_destroy (STB_LOCAL)
ffffffff814e5970-ffffffff814e59de: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814e510b)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814ea35e)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
```
```
In security/selinux/ss/services.c (ffffffff814f170f)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff814e68a0-ffffffff814e690e: context_destroy (STB_LOCAL)
ffffffff814ec930-ffffffff814ec99e: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8153e7d4)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81543d0f)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
```
```
In security/selinux/ss/services.c (ffffffff8154bda0)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff81540130-ffffffff8154019e: context_destroy (STB_LOCAL)
ffffffff81546930-ffffffff8154699e: context_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff815d61d4)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff815dc5f0)
Location: security/selinux/ss/context.h:174
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
```
```
In security/selinux/ss/services.c (ffffffff815e4be0)
Location: security/selinux/ss/context.h:174
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
Direct callers:
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff815d8150-ffffffff815d81c8: context_destroy (STB_LOCAL)
ffffffff815df000-ffffffff815df078: context_destroy (STB_LOCAL)
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
In security/selinux/ss/sidtab.c (ffffffff816844a4)
Location: security/selinux/ss/context.h:175
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff8168b768)
Location: security/selinux/ss/context.h:175
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff81694000)
Location: security/selinux/ss/context.h:175
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
In security/selinux/ss/sidtab.c (ffffffff816bc814)
Location: security/selinux/ss/context.h:177
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff816c3ad8)
Location: security/selinux/ss/context.h:177
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff816cc54a)
Location: security/selinux/ss/context.h:177
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
In security/selinux/ss/sidtab.c (ffffffff816f9344)
Location: security/selinux/ss/context.h:177
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff817005d8)
Location: security/selinux/ss/context.h:177
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
```
In security/selinux/ss/services.c (ffffffff817088ab)
Location: security/selinux/ss/context.h:177
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
In security/selinux/ss/sidtab.c (ffff80001055b4e4)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffff80001055d3ec)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffff800010567eb4)
Location: security/selinux/ss/context.h:142
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
In security/selinux/ss/sidtab.c (c070fcd0)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (c0711920)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (c071c254)
Location: security/selinux/ss/context.h:142
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
In security/selinux/ss/sidtab.c (c0000000006ba798)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (c0000000006bd008)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (c0000000006cb3d0)
Location: security/selinux/ss/context.h:142
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
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void context_destroy(struct context *c);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffe0003b21f8)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffe0003b3904)
Location: security/selinux/ss/context.h:142
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:context_read_and_validate
```
```
In security/selinux/ss/services.c (ffffffe0003bd90e)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
```
**Symbols:**

```
ffffffe0003b3904-ffffffe0003b395e: context_destroy (STB_LOCAL)
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
In security/selinux/ss/sidtab.c (ffffffff81464bd3)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff814664e5)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff814704bd)
Location: security/selinux/ss/context.h:142
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
In security/selinux/ss/sidtab.c (ffffffff81455603)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81456f15)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81460edd)
Location: security/selinux/ss/context.h:142
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
In security/selinux/ss/sidtab.c (ffffffff81460c73)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81462585)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff8146c55d)
Location: security/selinux/ss/context.h:142
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
In security/selinux/ss/sidtab.c (ffffffff81478473)
Location: security/selinux/ss/context.h:142
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/policydb.c (ffffffff81479d85)
Location: security/selinux/ss/context.h:142
Inline: True
```
```
In security/selinux/ss/services.c (ffffffff81483dcb)
Location: security/selinux/ss/context.h:142
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
