# Function: <code>shmem_alloc_hugepage</code>

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
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bced0)
Location: mm/shmem.c:1369
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff811bced0-ffffffff811bcfef: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cd5e0)
Location: mm/shmem.c:1394
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff811cd5e0-ffffffff811cd6ff: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d6680)
Location: mm/shmem.c:1419
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff811d6680-ffffffff811d679f: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ebba0)
Location: mm/shmem.c:1442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff811ebba0-ffffffff811ebcbf: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120d350)
Location: mm/shmem.c:1461
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8120d350-ffffffff8120d44c: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81221080)
Location: mm/shmem.c:1432
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff81221080-ffffffff81221167: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230850)
Location: mm/shmem.c:1459
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff81230850-ffffffff81230934: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123ea80)
Location: mm/shmem.c:1474
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8123ea80-ffffffff8123eb6a: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126baa0)
Location: mm/shmem.c:1479
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8126baa0-ffffffff8126bbcf: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812764f0)
Location: mm/shmem.c:1534
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff812764f0-ffffffff8127661f: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127b8c0)
Location: mm/shmem.c:1532
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8127b8c0-ffffffff8127b9e9: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812b9a30)
Location: mm/shmem.c:1555
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff812b9a30-ffffffff812b9b59: shmem_alloc_hugepage (STB_LOCAL)
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
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d0860)
Location: mm/shmem.c:1474
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffff8000102d0860-ffff8000102d0950: shmem_alloc_hugepage (STB_LOCAL)
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
In mm/shmem.c (0)
Location: mm/shmem.c:1474
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038e340)
Location: mm/shmem.c:1474
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
c00000000038e340-c00000000038e494: shmem_alloc_hugepage (STB_LOCAL)
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
In mm/shmem.c (0)
Location: mm/shmem.c:1474
Inline: True
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
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812370d0)
Location: mm/shmem.c:1474
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff812370d0-ffffffff812371ba: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122a130)
Location: mm/shmem.c:1474
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8122a130-ffffffff8122a21a: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81234e70)
Location: mm/shmem.c:1474
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff81234e70-ffffffff81234f5a: shmem_alloc_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *shmem_alloc_hugepage(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81245270)
Location: mm/shmem.c:1474
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff81245270-ffffffff8124535a: shmem_alloc_hugepage (STB_LOCAL)
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
