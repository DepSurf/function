# Function: <code>next_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8128517e)
Location: fs/proc/proc_sysctl.c:377
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff8134ddc4)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff8134fa49)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read
```
```
In security/selinux/ss/policydb.c (ffffffff81350631)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff8135aa96)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b2356)
Location: fs/proc/proc_sysctl.c:377
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff81383dd1)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff81385fd9)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8138941c)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff81391212)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c7b78)
Location: fs/proc/proc_sysctl.c:377
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff8139a851)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff8139ca69)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8139fedc)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffff813a7e42)
Location: security/selinux/ss/policydb.h:337
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d507f)
Location: fs/proc/proc_sysctl.c:408
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff813b0f34)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff813b31a9)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff813b66bd)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff813be806)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff813b3710-ffffffff813b373f: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f98b6)
Location: fs/proc/proc_sysctl.c:409
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff813d7024)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff813d92f9)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff813dc81d)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff813e49a6)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff813d9860-ffffffff813d988f: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81326fc2)
Location: fs/proc/proc_sysctl.c:409
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff81407674)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff814097e5)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8140ccc7)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff81415655)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81409ec0-ffffffff81409ef9: next_entry.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133e192)
Location: fs/proc/proc_sysctl.c:409
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff814231c4)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff81425b25)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8142999b)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff81431c15)
Location: security/selinux/ss/policydb.h:348
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff814261b0-ffffffff814261e9: next_entry.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8136608c)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff81450d74)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff81453555)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8145766c)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff8145f685)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81453ce0-ffffffff81453d19: next_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137e31c)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff8146ab54)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff8146d2f5)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8147140c)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff81479435)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff8146da80-ffffffff8146dab9: next_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c8a06)
Location: fs/proc/proc_sysctl.c:382
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff814befb4)
Location: security/selinux/ss/policydb.h:349
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff814c1ae5)
Location: security/selinux/ss/policydb.h:349
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff814c674e)
Location: security/selinux/ss/policydb.h:349
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff814ceb35)
Location: security/selinux/ss/policydb.h:349
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_node
  - security/selinux/ss/conditional.c:cond_read_node
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff814c2370-ffffffff814c239f: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813da9f6)
Location: fs/proc/proc_sysctl.c:383
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff814dc9d4)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff814df722)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff814e4786)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff814ebf75)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_node
  - security/selinux/ss/conditional.c:cond_read_node
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff814dfeb0-ffffffff814dfedf: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e1608)
Location: fs/proc/proc_sysctl.c:378
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff814e3314)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff814e6022)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff814eb152)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff814f2985)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff814e6730-ffffffff814e675f: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814330f9)
Location: fs/proc/proc_sysctl.c:378
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff8153c6d4)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff8153f882)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff81544b9a)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff8154d395)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff8153ffc0-ffffffff8153ffef: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814acea9)
Location: fs/proc/proc_sysctl.c:403
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff815d4057)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff815d75d2)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff815dd58f)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff815e6385)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff815d7ff0-ffffffff815d8033: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815432f9)
Location: fs/proc/proc_sysctl.c:396
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff81682137)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff81685b34)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8168c290)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff816959c5)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81686700-ffffffff81686743: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157b74c)
Location: fs/proc/proc_sysctl.c:390
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff816ba2b7)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff816bde94)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff816c4600)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff816cded5)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff816bea70-ffffffff816beab3: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b3ffc)
Location: fs/proc/proc_sysctl.c:392
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff816f6d47)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff816fa744)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff81701155)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff8170a4f5)
Location: security/selinux/ss/policydb.h:358
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff816fb290-ffffffff816fb2d3: next_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044b890)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffff80001055989c)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffff80001055c480)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffff800010560bac)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffff8000105698c8)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffff80001055cc78-ffff80001055cce0: next_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void next_entry(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c06100cc)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (c070e0ac)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (c0710c0c)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (c0715454)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (c071d510)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
c0711350-c07113a0: next_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000562958)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (c0000000006b7a64)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (c0000000006bbb74)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (c0000000006c1d74)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (c0000000006ccda8)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
c0000000006bc6a0-c0000000006bc728: next_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e0bb0)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffe0003b08c6)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffe0003b3170)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffe0003b740a)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:context_read_and_validate
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
```
```
In security/selinux/ss/conditional.c (ffffffe0003be8fe)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813768fc)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff81463134)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff814658d5)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff814699ec)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff81471a15)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81466060-ffffffff81466099: next_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813673cc)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff81453b64)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff81456305)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8145a41c)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff81462435)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81456a90-ffffffff81456ac9: next_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813743cc)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff8145f1d4)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff81461975)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff81465a8c)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff8146dab5)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81462100-ffffffff81462139: next_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81387dcc)
Location: fs/proc/proc_sysctl.c:414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In security/selinux/ss/ebitmap.c (ffffffff814769e4)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/avtab.c (ffffffff81479175)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
  - security/selinux/ss/avtab.c:avtab_read_item
```
```
In security/selinux/ss/policydb.c (ffffffff8147d26c)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:mls_read_level
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:str_read
  - security/selinux/ss/policydb.c:mls_read_range_helper
  - security/selinux/ss/policydb.c:mls_read_range_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/conditional.c (ffffffff81485325)
Location: security/selinux/ss/policydb.h:344
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_list
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_bool
  - security/selinux/ss/conditional.c:cond_read_bool
```
**Symbols:**

```
ffffffff81479900-ffffffff81479939: next_entry.isra.0 (STB_LOCAL)
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
</ul>
