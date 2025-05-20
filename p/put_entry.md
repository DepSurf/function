# Function: <code>put_entry</code>

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
In security/selinux/ss/ebitmap.c (ffffffff8134e179)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff813500cd)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write
```
```
In security/selinux/ss/policydb.c (ffffffff813509a7)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
```
```
In security/selinux/ss/conditional.c (ffffffff8135ab9d)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
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
In security/selinux/ss/ebitmap.c (ffffffff813842b5)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff813861e5)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8138a8d7)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81391568)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff8139ad45)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff8139cc75)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff813a14e7)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff813a8198)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int put_entry(const void *buf, size_t bytes, int num, struct policy_file *fp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813b1447)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff813b33b8)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
```
```
In security/selinux/ss/policydb.c (ffffffff813b7c37)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
```
```
In security/selinux/ss/conditional.c (ffffffff813beb5b)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
**Symbols:**

```
ffffffff813b3740-ffffffff813b376f: put_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int put_entry(const void *buf, size_t bytes, int num, struct policy_file *fp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813d7537)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff813d9508)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
```
```
In security/selinux/ss/policydb.c (ffffffff813ddda7)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
```
```
In security/selinux/ss/conditional.c (ffffffff813e4cfb)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
**Symbols:**

```
ffffffff813d9890-ffffffff813d98bf: put_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81407b4d)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff814099a8)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8140d6b8)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
```
```
In security/selinux/ss/conditional.c (ffffffff81415987)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
**Symbols:**

```
ffffffff81409f00-ffffffff81409f35: put_entry.isra.2 (STB_LOCAL)
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
In security/selinux/ss/ebitmap.c (ffffffff8142369d)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff81425ce8)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8142aa5a)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81431f47)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff814511cb)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff8145370b)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8145848a)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff8145f977)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff8146afab)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff8146d4ab)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8147222a)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81479727)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff814bf461)
Location: security/selinux/ss/policydb.h:360
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff814c1c9b)
Location: security/selinux/ss/policydb.h:360
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
```
```
In security/selinux/ss/policydb.c (ffffffff814c741c)
Location: security/selinux/ss/policydb.h:360
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff814ced1b)
Location: security/selinux/ss/policydb.h:360
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_node
  - security/selinux/ss/conditional.c:cond_write_node
  - security/selinux/ss/conditional.c:cond_write_node
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff814dce81)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff814df8cb)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
```
```
In security/selinux/ss/policydb.c (ffffffff814e54bc)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff814ec15b)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_node
  - security/selinux/ss/conditional.c:cond_write_node
  - security/selinux/ss/conditional.c:cond_write_node
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff814e37fd)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff814e61db)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
```
```
In security/selinux/ss/policydb.c (ffffffff814ebe09)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff814f2c9b)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff8153cbeb)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff8153fa6b)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
```
```
In security/selinux/ss/policydb.c (ffffffff81545be2)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff8154d62b)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int put_entry(const void *buf, size_t bytes, int num, struct policy_file *fp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff815d45b2)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff815d784d)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff815de35a)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
```
In security/selinux/ss/conditional.c (ffffffff815e6660)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
**Symbols:**

```
ffffffff815d8040-ffffffff815d8088: put_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int put_entry(const void *buf, size_t bytes, int num, struct policy_file *fp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816826cf)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff81685dcd)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8168cf67)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81695cb0)
Location: security/selinux/ss/policydb.h:369
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
Direct callers:
  - security/selinux/ss/conditional.c:cond_write_bool
```
**Symbols:**

```
ffffffff81684990-ffffffff81684a8f: put_entry (STB_LOCAL)
ffffffff81686760-ffffffff816867a8: put_entry (STB_LOCAL)
ffffffff81694d30-ffffffff81694d78: put_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int put_entry(const void *buf, size_t bytes, int num, struct policy_file *fp);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816b9460)
Location: security/selinux/ss/policydb.h:369
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff816bcd00)
Location: security/selinux/ss/policydb.h:369
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff816bead0)
Location: security/selinux/ss/policydb.h:369
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff816cd250)
Location: security/selinux/ss/policydb.h:369
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
**Symbols:**

```
ffffffff816b9460-ffffffff816b955f: put_entry (STB_LOCAL)
ffffffff816bcd00-ffffffff816bcdff: put_entry (STB_LOCAL)
ffffffff816bead0-ffffffff816beb18: put_entry (STB_LOCAL)
ffffffff816cd250-ffffffff816cd298: put_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
int put_entry(const void *buf, size_t bytes, size_t num, struct policy_file *fp);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816f5f20)
Location: security/selinux/ss/policydb.h:369
Inline: False
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff816f9800)
Location: security/selinux/ss/policydb.h:369
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff816fb2f0)
Location: security/selinux/ss/policydb.h:369
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:role_trans_write_one
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81709830)
Location: security/selinux/ss/policydb.h:369
Inline: False
Direct callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
**Symbols:**

```
ffffffff816f5f20-ffffffff816f5fe8: put_entry (STB_LOCAL)
ffffffff816f9800-ffffffff816f98c8: put_entry (STB_LOCAL)
ffffffff816fb2f0-ffffffff816fb34e: put_entry (STB_LOCAL)
ffffffff81709830-ffffffff81709881: put_entry (STB_LOCAL)
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
In security/selinux/ss/ebitmap.c (ffff800010559d40)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffff80001055c6dc)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffff8000105617e4)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffff800010569c24)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (c070e5d8)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (c0710eb4)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
```
```
In security/selinux/ss/policydb.c (c07162a4)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:write_cons_helper
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
```
```
In security/selinux/ss/conditional.c (c071d8ac)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (c0000000006b8070)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (c0000000006bbe64)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (c0000000006c2cdc)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (c0000000006cd214)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffe0003b0e16)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffe0003b33bc)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffe0003b851a)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/policydb.c:mls_write_level
```
```
In security/selinux/ss/conditional.c (ffffffe0003bec8c)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff8146358b)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff81465a8b)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8146a80a)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81471d07)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff81453fbb)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff814564bb)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8145b23a)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81462727)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff8145f62b)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff81461b2b)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff814668aa)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff8146dda7)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
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
In security/selinux/ss/ebitmap.c (ffffffff81476e3b)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/avtab.c (ffffffff8147932b)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
  - security/selinux/ss/avtab.c:avtab_write_item
```
```
In security/selinux/ss/policydb.c (ffffffff8147e08a)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:filename_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:type_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:role_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:perm_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:cat_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:sens_write
  - security/selinux/ss/policydb.c:mls_write_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81485617)
Location: security/selinux/ss/policydb.h:355
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_list
  - security/selinux/ss/conditional.c:cond_write_bool
  - security/selinux/ss/conditional.c:cond_write_bool
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int num</code> ➡️ <code>size_t num</code>
</li>
</ul>
</details>
</li>
</ul>
