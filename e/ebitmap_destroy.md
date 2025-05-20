# Function: <code>ebitmap_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8134d7c0)
Location: security/selinux/ss/ebitmap.c:324
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_read
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
```
**Symbols:**

```
ffffffff8134dd60-ffffffff8134dda3: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81383f9a)
Location: security/selinux/ss/ebitmap.c:324
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
```
**Symbols:**

```
ffffffff81383d70-ffffffff81383db3: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8139aa1a)
Location: security/selinux/ss/ebitmap.c:324
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:ocontext_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/policydb.c:constraint_expr_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
```
**Symbols:**

```
ffffffff8139a7f0-ffffffff8139a833: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813b0ca0)
Location: security/selinux/ss/ebitmap.c:326
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_cpy_high
```
**Symbols:**

```
ffffffff813b0ca0-ffffffff813b0ceb: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813d6d90)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
  - security/selinux/ss/mls.c:mls_context_cpy_high
```
**Symbols:**

```
ffffffff813d6d90-ffffffff813d6ddb: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814073c0)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_insert
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff814073c0-ffffffff8140740a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81422f10)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff81422f10-ffffffff81422f5a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81450af0)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff81450af0-ffffffff81450b3a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8146a8d0)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff8146a8d0-ffffffff8146a91a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814bf1ad)
Location: security/selinux/ss/ebitmap.c:346
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff814bef30-ffffffff814bef7a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814dcbcd)
Location: security/selinux/ss/ebitmap.c:346
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff814dc950-ffffffff814dc99a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814e350a)
Location: security/selinux/ss/ebitmap.c:346
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff814e3290-ffffffff814e32da: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8153c8d4)
Location: security/selinux/ss/ebitmap.c:346
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff8153c650-ffffffff8153c69a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff815d4267)
Location: security/selinux/ss/ebitmap.c:346
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff815d3fb0-ffffffff815d400a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8168231d)
Location: security/selinux/ss/ebitmap.c:347
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff81682080-ffffffff816820da: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816ba49d)
Location: security/selinux/ss/ebitmap.c:347
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff816ba200-ffffffff816ba25a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816f6f2d)
Location: security/selinux/ss/ebitmap.c:347
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff816f6c90-ffffffff816f6cea: ebitmap_destroy (STB_GLOBAL)
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
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffff8000105595c8)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffff8000105595c8-ffff800010559624: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c070dde0)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
c070dde0-c070de38: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c0000000006b7690)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
c0000000006b7690-c0000000006b7728: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffe0003b063e)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffe0003b063e-ffffffe0003b0692: ebitmap_destroy (STB_GLOBAL)
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
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81462eb0)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff81462eb0-ffffffff81462efa: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814538e0)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff814538e0-ffffffff8145392a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8145ef50)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff8145ef50-ffffffff8145ef9a: ebitmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81476760)
Location: security/selinux/ss/ebitmap.c:327
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_destroy_tree
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:sens_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:user_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/policydb.c:role_destroy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/services.c:string_to_context_struct
  - security/selinux/ss/mls.c:mls_import_netlbl_cat
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff81476760-ffffffff814767aa: ebitmap_destroy (STB_GLOBAL)
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
