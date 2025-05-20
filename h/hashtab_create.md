# Function: <code>hashtab_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8134e340)
Location: security/selinux/ss/hashtab.c:12
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8134e340-ffffffff8134e3ec: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81384340)
Location: security/selinux/ss/hashtab.c:12
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81384340-ffffffff813843ec: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8139add0)
Location: security/selinux/ss/hashtab.c:12
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8139add0-ffffffff8139ae7c: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813b14d0)
Location: security/selinux/ss/hashtab.c:12
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813b14d0-ffffffff813b1575: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813d75c0)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813d75c0-ffffffff813d7665: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81407c30)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81407c30-ffffffff81407cd1: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81423780)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81423780-ffffffff81423821: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814512f0)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814512f0-ffffffff8145138e: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8146b0d0)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8146b0d0-ffffffff8146b16e: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffff800010559e20)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffff800010559e20-ffff800010559ecc: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (c070e6b0)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
c070e6b0-c070e770: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (c0000000006b8190)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
c0000000006b8190-c0000000006b8288: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffe0003b0f4e)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffe0003b0f4e-ffffffe0003b0ff8: hashtab_create (STB_GLOBAL)
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
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814636b0)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814636b0-ffffffff8146374e: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814540e0)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814540e0-ffffffff8145417e: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8145f750)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8145f750-ffffffff8145f7ee: hashtab_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hashtab *hashtab_create(u32 (*hash_value)(struct hashtab *, const void *), int (*keycmp)(struct hashtab *, const void *, const void *), u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81476f60)
Location: security/selinux/ss/hashtab.c:15
Inline: False
Direct callers:
  - security/selinux/ss/symtab.c:symtab_init
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81476f60-ffffffff81476ffe: hashtab_create (STB_GLOBAL)
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
