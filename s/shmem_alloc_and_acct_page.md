# Function: <code>shmem_alloc_and_acct_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct shmem_inode_info *info, struct shmem_sb_info *sbinfo, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bf350)
Location: mm/shmem.c:1413
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811bf350-ffffffff811bf4f7: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct shmem_inode_info *info, struct shmem_sb_info *sbinfo, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cf980)
Location: mm/shmem.c:1438
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811cf980-ffffffff811cfb25: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct shmem_inode_info *info, struct shmem_sb_info *sbinfo, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d8550)
Location: mm/shmem.c:1463
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811d8550-ffffffff811d8701: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811edba0)
Location: mm/shmem.c:1486
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811edba0-ffffffff811edd50: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120e480)
Location: mm/shmem.c:1505
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8120e480-ffffffff8120e63d: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812212b0)
Location: mm/shmem.c:1470
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff812212b0-ffffffff8122146d: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230ac0)
Location: mm/shmem.c:1497
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81230ac0-ffffffff81230c8f: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123ecf0)
Location: mm/shmem.c:1512
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8123ecf0-ffffffff8123eebf: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126c560)
Location: mm/shmem.c:1516
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8126c560-ffffffff8126c72f: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81276fb0)
Location: mm/shmem.c:1571
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81276fb0-ffffffff8127717d: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127c010)
Location: mm/shmem.c:1569
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8127c010-ffffffff8127c1dd: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812ba1c0)
Location: mm/shmem.c:1592
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff812ba1c0-ffffffff812ba38d: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
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
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d09f8)
Location: mm/shmem.c:1512
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffff8000102d09f8-ffff8000102d0bc0: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fc07c)
Location: mm/shmem.c:1512
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000390550)
Location: mm/shmem.c:1512
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
c000000000390550-c000000000390818: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001efdd8)
Location: mm/shmem.c:1512
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
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
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81237340)
Location: mm/shmem.c:1512
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81237340-ffffffff8123750f: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122a6a0)
Location: mm/shmem.c:1512
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8122a6a0-ffffffff8122a86f: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812350e0)
Location: mm/shmem.c:1512
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff812350e0-ffffffff812352af: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *shmem_alloc_and_acct_page(gfp_t gfp, struct inode *inode, long unsigned int index, bool huge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812458e0)
Location: mm/shmem.c:1512
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff812458e0-ffffffff81245aaf: shmem_alloc_and_acct_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct shmem_inode_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>struct shmem_sb_info *sbinfo</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp, info, sbinfo, index, huge</code> ➡️ <code>gfp, inode, index, huge</code>
</li>
</ul>
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
