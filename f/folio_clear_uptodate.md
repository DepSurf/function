# Function: <code>folio_clear_uptodate</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81489f03)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff814e1514)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff8135bcec)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In fs/iomap/buffered-io.c (ffffffff8151d5c1)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff81579d61)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6a7f)
Location: include/linux/page-flags.h:758
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In fs/iomap/buffered-io.c (ffffffff81555860)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff815b18f1)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff815db0cf)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/hugetlbfs/inode.c (ffffffff8162eb3d)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/memory-failure.c (ffffffff814c516a)
Location: include/linux/page-flags.h:773
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inode.c (ffffffff815ea958)
Location: include/linux/page-flags.h:773
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff81667ff1)
Location: include/linux/page-flags.h:773
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
