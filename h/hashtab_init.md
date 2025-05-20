# Function: <code>hashtab_init</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hashtab_init(struct hashtab *h, u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 nel_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814bf680)
Location: security/selinux/ss/hashtab.c:32
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff814bf680-ffffffff814bf6e0: hashtab_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hashtab_init(struct hashtab *h, u32 nel_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814dcfc0)
Location: security/selinux/ss/hashtab.c:31
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff814dcfc0-ffffffff814dd030: hashtab_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hashtab_init(struct hashtab *h, u32 nel_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814e3930)
Location: security/selinux/ss/hashtab.c:31
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff814e3930-ffffffff814e39a0: hashtab_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hashtab_init(struct hashtab *h, u32 nel_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/hashtab.c (0)
Location: security/selinux/ss/hashtab.c:31
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff81cd42ff-ffffffff81cd431d: hashtab_init.cold (STB_LOCAL)
ffffffff8153cd20-ffffffff8153cdb8: hashtab_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hashtab_init(struct hashtab *h, u32 nel_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/hashtab.c (0)
Location: security/selinux/ss/hashtab.c:32
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff81e87289-ffffffff81e872a7: hashtab_init.cold (STB_LOCAL)
ffffffff815d4720-ffffffff815d47bb: hashtab_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hashtab_init(struct hashtab *h, u32 nel_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/hashtab.c (0)
Location: security/selinux/ss/hashtab.c:32
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff820739e5-ffffffff82073a03: hashtab_init.cold (STB_LOCAL)
ffffffff81682840-ffffffff816828db: hashtab_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hashtab_init(struct hashtab *h, u32 nel_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/hashtab.c (0)
Location: security/selinux/ss/hashtab.c:32
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff820f35b4-ffffffff820f35d2: hashtab_init.cold (STB_LOCAL)
ffffffff816ba9c0-ffffffff816baa5b: hashtab_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hashtab_init(struct hashtab *h, u32 nel_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/hashtab.c (0)
Location: security/selinux/ss/hashtab.c:32
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:filename_trans_read
  - security/selinux/ss/policydb.c:range_read
```
**Symbols:**

```
ffffffff821d0798-ffffffff821d07b6: hashtab_init.cold (STB_LOCAL)
ffffffff816f7450-ffffffff816f74ed: hashtab_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 (*hash_value)(struct hashtab *, const void *)</code>
</li>
<li>
<b>Param removed. </b>
<code>int (*keycmp)(struct hashtab *, const void *, const void *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, hash_value, keycmp, nel_hint</code> ➡️ <code>h, nel_hint</code>
</li>
</ul>
</details>
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
