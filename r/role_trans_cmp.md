# Function: <code>role_trans_cmp</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int role_trans_cmp(struct hashtab *h, const void *k1, const void *k2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c23c0)
Location: security/selinux/ss/policydb.c:481
Inline: True
```
**Symbols:**

```
ffffffff814c23c0-ffffffff814c23df: role_trans_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int role_trans_cmp(const void *k1, const void *k2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e3846)
Location: security/selinux/ss/policydb.c:502
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff814dff00-ffffffff814dff1f: role_trans_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int role_trans_cmp(const void *k1, const void *k2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814ea1fe)
Location: security/selinux/ss/policydb.c:502
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff814e6780-ffffffff814e679f: role_trans_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int role_trans_cmp(const void *k1, const void *k2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81543b6e)
Location: security/selinux/ss/policydb.c:502
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff81540010-ffffffff8154002f: role_trans_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int role_trans_cmp(const void *k1, const void *k2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815dc430)
Location: security/selinux/ss/policydb.c:497
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff815d80c0-ffffffff815d80e7: role_trans_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int role_trans_cmp(const void *k1, const void *k2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168af30)
Location: security/selinux/ss/policydb.c:497
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff81686b00-ffffffff81686b27: role_trans_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int role_trans_cmp(const void *k1, const void *k2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c32a0)
Location: security/selinux/ss/policydb.c:497
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff816bf8d0-ffffffff816bf8f7: role_trans_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int role_trans_cmp(const void *k1, const void *k2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816ffd33)
Location: security/selinux/ss/policydb.c:490
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_roletr_search
  - security/selinux/ss/policydb.c:policydb_roletr_search
```
**Symbols:**

```
ffffffff816fc110-ffffffff816fc137: role_trans_cmp (STB_LOCAL)
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
<code>h, k1, k2</code> ➡️ <code>k1, k2</code>
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
