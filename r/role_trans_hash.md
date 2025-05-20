# Function: <code>role_trans_hash</code>

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
u32 role_trans_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c1f20)
Location: security/selinux/ss/policydb.c:473
Inline: False
```
**Symbols:**

```
ffffffff814c1f20-ffffffff814c1f41: role_trans_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 role_trans_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e3808)
Location: security/selinux/ss/policydb.c:495
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff814df9b0-ffffffff814df9c9: role_trans_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 role_trans_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814ea1c3)
Location: security/selinux/ss/policydb.c:495
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff814e62b0-ffffffff814e62c9: role_trans_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 role_trans_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81543b33)
Location: security/selinux/ss/policydb.c:495
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff8153fb40-ffffffff8153fb59: role_trans_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 role_trans_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815dc3f3)
Location: security/selinux/ss/policydb.c:490
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff815d7970-ffffffff815d7991: role_trans_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 role_trans_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168aef3)
Location: security/selinux/ss/policydb.c:490
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff81685f20-ffffffff81685f41: role_trans_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 role_trans_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c3263)
Location: security/selinux/ss/policydb.c:490
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff816be290-ffffffff816be2b1: role_trans_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 role_trans_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fc380)
Location: security/selinux/ss/policydb.c:483
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff816fc380-ffffffff816fc3f2: role_trans_hash (STB_LOCAL)
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
<code>struct hashtab *h</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, k</code> ➡️ <code>k</code>
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
