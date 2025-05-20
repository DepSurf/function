# Function: <code>hugetlb_fix_reserve_counts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode, bool restore_reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dc360)
Location: mm/hugetlb.c:568
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff811dc360-ffffffff811dc3b3: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode, bool restore_reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fa600)
Location: mm/hugetlb.c:570
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff811fa600-ffffffff811fa653: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120b040)
Location: mm/hugetlb.c:570
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8120b040-ffffffff8120b087: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812163c0)
Location: mm/hugetlb.c:572
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812163c0-ffffffff8121640c: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81231070)
Location: mm/hugetlb.c:573
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81231070-ffffffff812310bc: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81253f50)
Location: mm/hugetlb.c:572
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81253f50-ffffffff81253f9c: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81268330)
Location: mm/hugetlb.c:572
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81268330-ffffffff8126837c: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81283610)
Location: mm/hugetlb.c:574
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81283610-ffffffff8128365c: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812931b0)
Location: mm/hugetlb.c:575
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812931b0-ffffffff812931fc: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c6380)
Location: mm/hugetlb.c:714
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812c6380-ffffffff812c63cf: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d1f70)
Location: mm/hugetlb.c:744
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812d1f70-ffffffff812d1fbf: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:744
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81bdaa71-ffffffff81bdaa82: hugetlb_fix_reserve_counts.cold (STB_LOCAL)
ffffffff812d88c0-ffffffff812d8923: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:746
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81cbf632-ffffffff81cbf643: hugetlb_fix_reserve_counts.cold (STB_LOCAL)
ffffffff8131f5d0-ffffffff8131f633: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:763
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81e719bd-ffffffff81e719ce: hugetlb_fix_reserve_counts.cold (STB_LOCAL)
ffffffff8138c020-ffffffff8138c097: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814098e0)
Location: mm/hugetlb.c:907
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff814098e0-ffffffff8140995b: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143cf40)
Location: mm/hugetlb.c:901
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8143cf40-ffffffff8143cfbb: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814776f0)
Location: mm/hugetlb.c:934
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff814776f0-ffffffff8147776b: hugetlb_fix_reserve_counts (STB_GLOBAL)
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
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010330f28)
Location: mm/hugetlb.c:575
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffff800010330f28-ffff800010330f7c: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000409b40)
Location: mm/hugetlb.c:575
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
c000000000409b40-c000000000409bc4: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022e11e)
Location: mm/hugetlb.c:575
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffe00022e11e-ffffffe00022e166: hugetlb_fix_reserve_counts (STB_GLOBAL)
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
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b790)
Location: mm/hugetlb.c:575
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8128b790-ffffffff8128b7dc: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127d5c0)
Location: mm/hugetlb.c:575
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8127d5c0-ffffffff8127d60c: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812895a0)
Location: mm/hugetlb.c:575
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff812895a0-ffffffff812895ec: hugetlb_fix_reserve_counts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hugetlb_fix_reserve_counts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81299380)
Location: mm/hugetlb.c:575
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81299380-ffffffff812993cc: hugetlb_fix_reserve_counts (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool restore_reserve</code>
</li>
</ul>
</details>
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
