# Function: <code>shmem_pseudo_vma_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bf15c)
Location: mm/shmem.c:1339
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
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
In mm/shmem.c (ffffffff811cf78c)
Location: mm/shmem.c:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
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
In mm/shmem.c (ffffffff811d65cc)
Location: mm/shmem.c:1389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
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
In mm/shmem.c (ffffffff811ebaec)
Location: mm/shmem.c:1412
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120d180)
Location: mm/shmem.c:1428
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff8120d180-ffffffff8120d1d8: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81220ee0)
Location: mm/shmem.c:1400
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff81220ee0-ffffffff81220f38: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230680)
Location: mm/shmem.c:1427
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff81230680-ffffffff81230705: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123e8a0)
Location: mm/shmem.c:1442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff8123e8a0-ffffffff8123e925: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126c095)
Location: mm/shmem.c:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81276ae5)
Location: mm/shmem.c:1502
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127bd1b)
Location: mm/shmem.c:1476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812b9e8b)
Location: mm/shmem.c:1499
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81315d90)
Location: mm/shmem.c:1464
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff81315d90-ffffffff81315dff: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138aa19)
Location: mm/shmem.c:1483
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_folio
Direct callers:
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff81389ec0-ffffffff81389f26: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bc0a0)
Location: mm/shmem.c:1495
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff813bc0a0-ffffffff813bc109: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
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
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d0650)
Location: mm/shmem.c:1442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffff8000102d0650-ffff8000102d06f0: shmem_pseudo_vma_init (STB_LOCAL)
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
In mm/shmem.c (c04fa8e8)
Location: mm/shmem.c:1442
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_swapin
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038e0f0)
Location: mm/shmem.c:1442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
c00000000038e0f0-c00000000038e188: shmem_pseudo_vma_init (STB_LOCAL)
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
In mm/shmem.c (ffffffe0001ecc28)
Location: mm/shmem.c:1442
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin
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
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81236ef0)
Location: mm/shmem.c:1442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff81236ef0-ffffffff81236f75: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81229f50)
Location: mm/shmem.c:1442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff81229f50-ffffffff81229fd5: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81234c90)
Location: mm/shmem.c:1442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff81234c90-ffffffff81234d15: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shmem_pseudo_vma_init(struct vm_area_struct *vma, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81245090)
Location: mm/shmem.c:1442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
**Symbols:**

```
ffffffff81245090-ffffffff81245115: shmem_pseudo_vma_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
