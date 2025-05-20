# Function: <code>shmem_alloc_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a6780)
Location: mm/shmem.c:927
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811a6780-ffffffff811a6832: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bf150)
Location: mm/shmem.c:1400
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff811bf150-ffffffff811bf202: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cf780)
Location: mm/shmem.c:1425
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff811cf780-ffffffff811cf832: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d65c0)
Location: mm/shmem.c:1450
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff811d65c0-ffffffff811d6672: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ebae0)
Location: mm/shmem.c:1473
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff811ebae0-ffffffff811ebb92: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120d2c0)
Location: mm/shmem.c:1492
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8120d2c0-ffffffff8120d34d: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81220ff0)
Location: mm/shmem.c:1457
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff81220ff0-ffffffff8122107d: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812307c0)
Location: mm/shmem.c:1484
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff812307c0-ffffffff8123084e: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123e9e0)
Location: mm/shmem.c:1499
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8123e9e0-ffffffff8123ea71: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126c060)
Location: mm/shmem.c:1503
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8126c060-ffffffff8126c129: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81276ab0)
Location: mm/shmem.c:1558
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff81276ab0-ffffffff81276b79: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127bce0)
Location: mm/shmem.c:1556
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8127bce0-ffffffff8127bdac: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812b9e50)
Location: mm/shmem.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff812b9e50-ffffffff812b9f1c: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131cadb)
Location: mm/shmem.c:1554
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
```
</details>
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
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d07a8)
Location: mm/shmem.c:1499
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffff8000102d07a8-ffff8000102d0860: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa8b4)
Location: mm/shmem.c:1499
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
c04fa8b4-c04fa91c: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038e270)
Location: mm/shmem.c:1499
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
c00000000038e270-c00000000038e338: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffe0001ed7be)
Location: mm/shmem.c:1499
Inline: True
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
ffffffe0001ed7be-ffffffe0001ed7f6: shmem_alloc_page.isra.0 (STB_LOCAL)
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
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81237030)
Location: mm/shmem.c:1499
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff81237030-ffffffff812370c1: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122a090)
Location: mm/shmem.c:1499
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff8122a090-ffffffff8122a121: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81234dd0)
Location: mm/shmem.c:1499
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff81234dd0-ffffffff81234e61: shmem_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *shmem_alloc_page(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812451d0)
Location: mm/shmem.c:1499
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
**Symbols:**

```
ffffffff812451d0-ffffffff81245261: shmem_alloc_page (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
