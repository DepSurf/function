# Function: <code>__hashtab_insert</code>

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
int __hashtab_insert(struct hashtab *h, struct hashtab_node **dst, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814dd030)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_insert
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff814dd030-ffffffff814dd089: __hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __hashtab_insert(struct hashtab *h, struct hashtab_node **dst, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814e39a0)
Location: security/selinux/ss/hashtab.c:42
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_insert
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff814e39a0-ffffffff814e39f9: __hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __hashtab_insert(struct hashtab *h, struct hashtab_node **dst, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8153cdc0)
Location: security/selinux/ss/hashtab.c:49
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_insert
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff8153cdc0-ffffffff8153ce19: __hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __hashtab_insert(struct hashtab *h, struct hashtab_node **dst, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff815d47c0)
Location: security/selinux/ss/hashtab.c:50
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_insert
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff815d47c0-ffffffff815d4825: __hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __hashtab_insert(struct hashtab *h, struct hashtab_node **dst, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff816828f0)
Location: security/selinux/ss/hashtab.c:50
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_insert
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff816828f0-ffffffff81682955: __hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __hashtab_insert(struct hashtab *h, struct hashtab_node **dst, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff816baa70)
Location: security/selinux/ss/hashtab.c:50
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_insert
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff816baa70-ffffffff816baad5: __hashtab_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __hashtab_insert(struct hashtab *h, struct hashtab_node **dst, void *key, void *datum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff816f7500)
Location: security/selinux/ss/hashtab.c:50
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_insert
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff816f7500-ffffffff816f7565: __hashtab_insert (STB_GLOBAL)
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
