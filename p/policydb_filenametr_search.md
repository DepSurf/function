# Function: <code>policydb_filenametr_search</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct filename_trans_datum *policydb_filenametr_search(struct policydb *p, struct filename_trans_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e2a28)
Location: security/selinux/ss/policydb.c:452
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff814e3690-ffffffff814e3768: policydb_filenametr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct filename_trans_datum *policydb_filenametr_search(struct policydb *p, struct filename_trans_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e93d8)
Location: security/selinux/ss/policydb.c:452
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff814ea050-ffffffff814ea126: policydb_filenametr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct filename_trans_datum *policydb_filenametr_search(struct policydb *p, struct filename_trans_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81542d48)
Location: security/selinux/ss/policydb.c:452
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff815439c0-ffffffff81543a96: policydb_filenametr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct filename_trans_datum *policydb_filenametr_search(struct policydb *p, struct filename_trans_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815db7b7)
Location: security/selinux/ss/policydb.c:447
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
```
**Symbols:**

```
ffffffff815dc240-ffffffff815dc33a: policydb_filenametr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct filename_trans_datum *policydb_filenametr_search(struct policydb *p, struct filename_trans_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168a4d7)
Location: security/selinux/ss/policydb.c:447
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
```
**Symbols:**

```
ffffffff8168ad20-ffffffff8168ae1a: policydb_filenametr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct filename_trans_datum *policydb_filenametr_search(struct policydb *p, struct filename_trans_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c2896)
Location: security/selinux/ss/policydb.c:447
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
```
**Symbols:**

```
ffffffff816c3090-ffffffff816c318a: policydb_filenametr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct filename_trans_datum *policydb_filenametr_search(struct policydb *p, struct filename_trans_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816ff40c)
Location: security/selinux/ss/policydb.c:440
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
```
**Symbols:**

```
ffffffff816ffb70-ffffffff816ffc19: policydb_filenametr_search (STB_GLOBAL)
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
