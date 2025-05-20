# Function: <code>shmem_unuse_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ab668)
Location: mm/shmem.c:644
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c3f21)
Location: mm/shmem.c:1061
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d3f6f)
Location: mm/shmem.c:1086
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dc72c)
Location: mm/shmem.c:1111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f25dd)
Location: mm/shmem.c:1134
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81213ab3)
Location: mm/shmem.c:1154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812269eb)
Location: mm/shmem.c:1126
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81235d80)
Location: mm/shmem.c:1193
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff81235d80-ffffffff8123627b: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81243fc0)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff81243fc0-ffffffff812444bb: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126de70)
Location: mm/shmem.c:1212
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff8126de70-ffffffff8126e3d6: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127c070)
Location: mm/shmem.c:1266
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff8127c070-ffffffff8127c5e2: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81281230)
Location: mm/shmem.c:1240
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff81281230-ffffffff812817b1: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bc830)
Location: mm/shmem.c:1251
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff812bc830-ffffffff812bcdc8: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81318980)
Location: mm/shmem.c:1234
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff81318980-ffffffff81318d09: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138c840)
Location: mm/shmem.c:1252
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff8138c840-ffffffff8138cbc9: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813beef0)
Location: mm/shmem.c:1267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff813beef0-ffffffff813bf2df: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e9f40)
Location: mm/shmem.c:1345
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff813e9f40-ffffffff813ea32f: shmem_unuse_inode (STB_LOCAL)
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
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d6240)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffff8000102d6240-ffff8000102d661c: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fe4a8)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
c04fe4a8-c04fe894: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000396410)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
c000000000396410-c000000000396938: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f1af6)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffe0001f1af6-ffffffe0001f1dee: shmem_unuse_inode (STB_LOCAL)
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
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123c610)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff8123c610-ffffffff8123cb0b: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122f610)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff8122f610-ffffffff8122fb0b: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123a3b0)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff8123a3b0-ffffffff8123a8ab: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_unuse_inode(struct inode *inode, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81249aa0)
Location: mm/shmem.c:1208
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unuse
```
**Symbols:**

```
ffffffff81249aa0-ffffffff81249fa5: shmem_unuse_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool frontswap</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *fs_pages_to_unuse</code>
</li>
</ul>
</details>
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
