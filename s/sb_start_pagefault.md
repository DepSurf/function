# Function: <code>sb_start_pagefault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118dbc6)
Location: include/linux/fs.h:1484
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/dax.c (ffffffff8125db21)
Location: include/linux/fs.h:1484
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_fault
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_fault
```
```
In fs/ext4/file.c (ffffffff81291c7c)
Location: include/linux/fs.h:1484
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
```
```
In fs/ext4/inode.c (ffffffff8129f1e6)
Location: include/linux/fs.h:1484
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a0566)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812bf1a6)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
```
```
In fs/ext4/inode.c (ffffffff812cd896)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b00e6)
Location: include/linux/fs.h:1527
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812d47c6)
Location: include/linux/fs.h:1527
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
```
```
In fs/ext4/inode.c (ffffffff812e3666)
Location: include/linux/fs.h:1527
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b7396)
Location: include/linux/fs.h:1543
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812f1188)
Location: include/linux/fs.h:1543
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81307856)
Location: include/linux/fs.h:1543
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cb4a6)
Location: include/linux/fs.h:1572
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81315d3b)
Location: include/linux/fs.h:1572
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8132c4a6)
Location: include/linux/fs.h:1572
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec61d)
Location: include/linux/fs.h:1583
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81343943)
Location: include/linux/fs.h:1583
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8135aaf7)
Location: include/linux/fs.h:1583
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fd92d)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8135ba83)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81372db7)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121499d)
Location: include/linux/fs.h:1654
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81384aad)
Location: include/linux/fs.h:1654
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8139c207)
Location: include/linux/fs.h:1654
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812221cd)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8139d52d)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813b4d17)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124fc0d)
Location: include/linux/fs.h:1704
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff813e8c2d)
Location: include/linux/fs.h:1704
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814001b7)
Location: include/linux/fs.h:1704
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125abc0)
Location: include/linux/fs.h:1691
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff813fc12b)
Location: include/linux/fs.h:1691
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8141293c)
Location: include/linux/fs.h:1691
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8149c5dc)
Location: include/linux/fs.h:1691
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125f620)
Location: include/linux/fs.h:1860
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8140256d)
Location: include/linux/fs.h:1860
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81418d9c)
Location: include/linux/fs.h:1860
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff814a260c)
Location: include/linux/fs.h:1860
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129bd90)
Location: include/linux/fs.h:1910
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81454c34)
Location: include/linux/fs.h:1910
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8146bfcc)
Location: include/linux/fs.h:1910
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff814fa6b7)
Location: include/linux/fs.h:1910
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f1b21)
Location: include/linux/fs.h:1801
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff814d2406)
Location: include/linux/fs.h:1801
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814ebf80)
Location: include/linux/fs.h:1801
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8158abd9)
Location: include/linux/fs.h:1801
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135cbdb)
Location: include/linux/fs.h:1916
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8156af53)
Location: include/linux/fs.h:1916
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81585ced)
Location: include/linux/fs.h:1916
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff81631336)
Location: include/linux/fs.h:1916
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138ec0e)
Location: include/linux/fs.h:1596
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff815a2e09)
Location: include/linux/fs.h:1596
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815bc5a4)
Location: include/linux/fs.h:1596
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8166956c)
Location: include/linux/fs.h:1596
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b7ffe)
Location: include/linux/fs.h:1804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff815dbb29)
Location: include/linux/fs.h:1804
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815f5384)
Location: include/linux/fs.h:1804
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff816a386c)
Location: include/linux/fs.h:1804
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102afa14)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffff800010470a30)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffff8000104894c8)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dc910)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/inode.c (c064b988)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000364ba4)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (c000000000591018)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (c0000000005b04c8)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d5b38)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffe0002fcd9e)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffe000310ca8)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121a81d)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81395b0d)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813ad2f7)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120da2d)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8138659d)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8139dd87)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812185bd)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8139346d)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813aab57)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122765d)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff813a74fd)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813bf4a7)
Location: include/linux/fs.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
</ul>

## Differences
