# Function: <code>symtab_search</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *symtab_search(struct symtab *s, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814dd500)
Location: security/selinux/ss/symtab.c:51
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
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
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff814dd500-ffffffff814dd573: symtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *symtab_search(struct symtab *s, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814e3e70)
Location: security/selinux/ss/symtab.c:51
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
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff814e3e70-ffffffff814e3ee3: symtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *symtab_search(struct symtab *s, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff8153d290)
Location: security/selinux/ss/symtab.c:51
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
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff8153d290-ffffffff8153d303: symtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *symtab_search(struct symtab *s, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff815d4d40)
Location: security/selinux/ss/symtab.c:51
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
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff815d4d40-ffffffff815d4dbb: symtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *symtab_search(struct symtab *s, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81682f00)
Location: security/selinux/ss/symtab.c:51
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
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff81682f00-ffffffff81682f7b: symtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *symtab_search(struct symtab *s, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff816bb080)
Location: security/selinux/ss/symtab.c:51
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
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff816bb080-ffffffff816bb0fb: symtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *symtab_search(struct symtab *s, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff816f7a80)
Location: security/selinux/ss/symtab.c:51
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:string_to_av_perm
  - security/selinux/ss/policydb.c:string_to_av_perm
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff816f7a80-ffffffff816f7afb: symtab_search (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
