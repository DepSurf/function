# Function: <code>sb_end_pagefault</code>

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
In mm/filemap.c (ffffffff8118dc2c)
Location: include/linux/fs.h:1419
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/dax.c (ffffffff8125db57)
Location: include/linux/fs.h:1419
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_fault
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_fault
```
```
In fs/ext4/file.c (ffffffff81291d06)
Location: include/linux/fs.h:1419
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
```
```
In fs/ext4/inode.c (ffffffff8129f41a)
Location: include/linux/fs.h:1419
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
In mm/filemap.c (ffffffff811a05db)
Location: include/linux/fs.h:1496
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812bf213)
Location: include/linux/fs.h:1496
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
```
```
In fs/ext4/inode.c (ffffffff812cd97a)
Location: include/linux/fs.h:1496
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
In mm/filemap.c (ffffffff811b015b)
Location: include/linux/fs.h:1462
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812d4833)
Location: include/linux/fs.h:1462
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_pfn_mkwrite
  - fs/ext4/file.c:ext4_dax_pmd_fault
  - fs/ext4/file.c:ext4_dax_fault
```
```
In fs/ext4/inode.c (ffffffff812e374a)
Location: include/linux/fs.h:1462
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
In mm/filemap.c (ffffffff811b740f)
Location: include/linux/fs.h:1478
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812f1232)
Location: include/linux/fs.h:1478
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813078fc)
Location: include/linux/fs.h:1478
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
In mm/filemap.c (ffffffff811cb51f)
Location: include/linux/fs.h:1507
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81315e06)
Location: include/linux/fs.h:1507
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8132c54c)
Location: include/linux/fs.h:1507
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
In mm/filemap.c (ffffffff811ec670)
Location: include/linux/fs.h:1518
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81343a23)
Location: include/linux/fs.h:1518
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8135ad86)
Location: include/linux/fs.h:1518
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
In mm/filemap.c (ffffffff811fd980)
Location: include/linux/fs.h:1573
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8135bb63)
Location: include/linux/fs.h:1573
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81373046)
Location: include/linux/fs.h:1573
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
In mm/filemap.c (ffffffff812149f0)
Location: include/linux/fs.h:1589
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81384b7e)
Location: include/linux/fs.h:1589
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8139c47a)
Location: include/linux/fs.h:1589
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
In mm/filemap.c (ffffffff81222220)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8139d5fe)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813b4f8a)
Location: include/linux/fs.h:1615
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
In mm/filemap.c (ffffffff8124fc60)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff813e8d05)
Location: include/linux/fs.h:1639
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814002fd)
Location: include/linux/fs.h:1639
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
In mm/filemap.c (ffffffff8125ac2c)
Location: include/linux/fs.h:1626
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff813fc211)
Location: include/linux/fs.h:1626
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814129b6)
Location: include/linux/fs.h:1626
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8149c5fb)
Location: include/linux/fs.h:1626
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
In mm/filemap.c (ffffffff8125f687)
Location: include/linux/fs.h:1795
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81402656)
Location: include/linux/fs.h:1795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81418e16)
Location: include/linux/fs.h:1795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff814a262b)
Location: include/linux/fs.h:1795
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
In mm/filemap.c (ffffffff8129bdfc)
Location: include/linux/fs.h:1845
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81454d1c)
Location: include/linux/fs.h:1845
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8146c04a)
Location: include/linux/fs.h:1845
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff814fa6d6)
Location: include/linux/fs.h:1845
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
In mm/filemap.c (ffffffff812f1ba1)
Location: include/linux/fs.h:1736
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff814d2502)
Location: include/linux/fs.h:1736
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814ec014)
Location: include/linux/fs.h:1736
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8158ac11)
Location: include/linux/fs.h:1736
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
In mm/filemap.c (ffffffff8135cc97)
Location: include/linux/fs.h:1851
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8156b053)
Location: include/linux/fs.h:1851
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81585d7e)
Location: include/linux/fs.h:1851
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8163136e)
Location: include/linux/fs.h:1851
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
In mm/filemap.c (ffffffff8138ecc5)
Location: include/linux/fs.h:1531
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff815a2f0c)
Location: include/linux/fs.h:1531
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815bc639)
Location: include/linux/fs.h:1531
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff816695a4)
Location: include/linux/fs.h:1531
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
In mm/filemap.c (ffffffff813b80b2)
Location: include/linux/fs.h:1739
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff815dbc2c)
Location: include/linux/fs.h:1739
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815f5419)
Location: include/linux/fs.h:1739
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff816a38a4)
Location: include/linux/fs.h:1739
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
In mm/filemap.c (ffff8000102afa74)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffff800010470af0)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffff80001048972c)
Location: include/linux/fs.h:1615
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
In mm/filemap.c (c04dc988)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/inode.c (c064bc90)
Location: include/linux/fs.h:1615
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
In mm/filemap.c (c000000000364c1c)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (c0000000005910f0)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (c0000000005b06ec)
Location: include/linux/fs.h:1615
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
In mm/filemap.c (ffffffe0001d5ba2)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffe0002fce62)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffe000310e40)
Location: include/linux/fs.h:1615
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
In mm/filemap.c (ffffffff8121a870)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff81395bde)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813ad56a)
Location: include/linux/fs.h:1615
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
In mm/filemap.c (ffffffff8120da80)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8138666e)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8139dffa)
Location: include/linux/fs.h:1615
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
In mm/filemap.c (ffffffff81218610)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff8139353e)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813aadca)
Location: include/linux/fs.h:1615
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
In mm/filemap.c (ffffffff812276ab)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff813a75ce)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff813bf715)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
</ul>

## Differences
