# Function: <code>filenametr_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813502a0)
Location: security/selinux/ss/policydb.c:207
Inline: False
```
**Symbols:**

```
ffffffff813502a0-ffffffff813502f8: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813862e0)
Location: security/selinux/ss/policydb.c:207
Inline: False
```
**Symbols:**

```
ffffffff813862e0-ffffffff81386336: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139cd70)
Location: security/selinux/ss/policydb.c:207
Inline: False
```
**Symbols:**

```
ffffffff8139cd70-ffffffff8139cdc6: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b34c0)
Location: security/selinux/ss/policydb.c:216
Inline: False
```
**Symbols:**

```
ffffffff813b34c0-ffffffff813b3516: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813d9610)
Location: security/selinux/ss/policydb.c:216
Inline: False
```
**Symbols:**

```
ffffffff813d9610-ffffffff813d9666: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81409bc0)
Location: security/selinux/ss/policydb.c:216
Inline: False
```
**Symbols:**

```
ffffffff81409bc0-ffffffff81409c1a: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81425eb0)
Location: security/selinux/ss/policydb.c:216
Inline: False
```
**Symbols:**

```
ffffffff81425eb0-ffffffff81425f0a: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814538f0)
Location: security/selinux/ss/policydb.c:213
Inline: False
```
**Symbols:**

```
ffffffff814538f0-ffffffff8145394a: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146d690)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
ffffffff8146d690-ffffffff8146d6ea: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c1e80)
Location: security/selinux/ss/policydb.c:414
Inline: False
```
**Symbols:**

```
ffffffff814c1e80-ffffffff814c1ee8: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 filenametr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e2485)
Location: security/selinux/ss/policydb.c:414
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff814df930-ffffffff814df985: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 filenametr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e867a)
Location: security/selinux/ss/policydb.c:414
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff814e6240-ffffffff814e628b: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 filenametr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81541fba)
Location: security/selinux/ss/policydb.c:414
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff8153fad0-ffffffff8153fb1b: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 filenametr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815d9d9a)
Location: security/selinux/ss/policydb.c:409
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff815d78e0-ffffffff815d7937: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 filenametr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168886f)
Location: security/selinux/ss/policydb.c:409
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff81685e70-ffffffff81685ec7: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 filenametr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c1fd2)
Location: security/selinux/ss/policydb.c:409
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff816be1e0-ffffffff816be237: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 filenametr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fadd0)
Location: security/selinux/ss/policydb.c:409
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
```
**Symbols:**

```
ffffffff816fadd0-ffffffff816fae0a: filenametr_hash (STB_LOCAL)
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
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055c760)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
ffff80001055c760-ffff80001055c7e4: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0710f2c)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
c0710f2c-c0710f90: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006bbf60)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
c0000000006bbf60-c0000000006bbfe0: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b344c)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
ffffffe0003b344c-ffffffe0003b34ca: filenametr_hash (STB_LOCAL)
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
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81465c70)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
ffffffff81465c70-ffffffff81465cca: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814566a0)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
ffffffff814566a0-ffffffff814566fa: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81461d10)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
ffffffff81461d10-ffffffff81461d6a: filenametr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 filenametr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81479510)
Location: security/selinux/ss/policydb.c:402
Inline: False
```
**Symbols:**

```
ffffffff81479510-ffffffff8147956a: filenametr_hash (STB_LOCAL)
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
