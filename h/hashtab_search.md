# Function: <code>hashtab_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8134e550)
Location: security/selinux/ss/hashtab.c:77
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff8134e550-ffffffff8134e5c1: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81384540)
Location: security/selinux/ss/hashtab.c:77
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81384540-ffffffff813845b1: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8139afd0)
Location: security/selinux/ss/hashtab.c:77
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff8139afd0-ffffffff8139b041: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813b16e0)
Location: security/selinux/ss/hashtab.c:77
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff813b16e0-ffffffff813b1751: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813d77c0)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff813d77c0-ffffffff813d7841: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81407e30)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81407e30-ffffffff81407eb1: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81423990)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81423990-ffffffff81423a11: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814514f0)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff814514f0-ffffffff81451571: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8146b2d0)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff8146b2d0-ffffffff8146b351: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814bf840)
Location: security/selinux/ss/hashtab.c:87
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_preserve_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff814bf840-ffffffff814bf8c3: hashtab_search (STB_GLOBAL)
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
In security/selinux/ss/symtab.c (ffffffff814dd505)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
```
```
In security/selinux/ss/policydb.c (ffffffff814e2a28)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_rangetr_search
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
In security/selinux/ss/symtab.c (ffffffff814e3e75)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
```
```
In security/selinux/ss/policydb.c (ffffffff814e93d8)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_rangetr_search
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
In security/selinux/ss/symtab.c (ffffffff8153d295)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
```
```
In security/selinux/ss/policydb.c (ffffffff81542d48)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_rangetr_search
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
In security/selinux/ss/symtab.c (ffffffff815d4d45)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
```
```
In security/selinux/ss/policydb.c (ffffffff815db7b7)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_rangetr_search
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
In security/selinux/ss/symtab.c (ffffffff81682f05)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
```
```
In security/selinux/ss/policydb.c (ffffffff8168a4d7)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_rangetr_search
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
In security/selinux/ss/symtab.c (ffffffff816bb085)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
```
```
In security/selinux/ss/policydb.c (ffffffff816c2896)
Location: security/selinux/ss/hashtab.h:96
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_rangetr_search
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
In security/selinux/ss/symtab.c (ffffffff816f7a85)
Location: security/selinux/ss/hashtab.h:97
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
```
```
In security/selinux/ss/policydb.c (ffffffff816ff40c)
Location: security/selinux/ss/hashtab.h:97
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_rangetr_search
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffff80001055a028)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffff80001055a028-ffff80001055a0d0: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (c070e8d8)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:string_to_av_perm
  - security/selinux/ss/policydb.c:string_to_av_perm
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
c070e8d8-c070e968: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (c0000000006b8490)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
c0000000006b8490-c0000000006b8590: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffe0003b1126)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffe0003b1126-ffffffe0003b11a2: hashtab_search (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814638b0)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff814638b0-ffffffff81463931: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814542e0)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff814542e0-ffffffff81454361: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8145f950)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff8145f950-ffffffff8145f9d1: hashtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *hashtab_search(struct hashtab *h, const void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81477160)
Location: security/selinux/ss/hashtab.c:80
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81477160-ffffffff814771e1: hashtab_search (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
