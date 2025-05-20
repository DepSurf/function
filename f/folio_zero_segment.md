# Function: <code>folio_zero_segment</code>

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
In mm/secretmem.c (ffffffff813e388f)
Location: include/linux/highmem.h:423
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In fs/buffer.c (ffffffff81446c9a)
Location: include/linux/highmem.h:423
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
```
```
In fs/iomap/buffered-io.c (ffffffff8148a5c6)
Location: include/linux/highmem.h:423
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
```
In fs/hugetlbfs/inode.c (ffffffff81554e7b)
Location: include/linux/highmem.h:423
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
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
In mm/secretmem.c (ffffffff8146b26b)
Location: include/linux/highmem.h:438
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In fs/mpage.c (ffffffff814d9d27)
Location: include/linux/highmem.h:438
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8151df96)
Location: include/linux/highmem.h:438
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
```
In fs/hugetlbfs/inode.c (ffffffff815f722b)
Location: include/linux/highmem.h:438
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
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
In mm/secretmem.c (ffffffff814a0066)
Location: include/linux/highmem.h:492
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In fs/buffer.c (ffffffff8150b8a3)
Location: include/linux/highmem.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:folio_zero_new_buffers
```
```
In fs/mpage.c (ffffffff8150f113)
Location: include/linux/highmem.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff81556128)
Location: include/linux/highmem.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
```
In fs/ext4/inline.c (ffffffff815ad7aa)
Location: include/linux/highmem.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/page-io.c (ffffffff815dac7f)
Location: include/linux/highmem.h:492
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/readpage.c (ffffffff815db9a3)
Location: include/linux/highmem.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f2ee)
Location: include/linux/highmem.h:492
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
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
In mm/secretmem.c (ffffffff814cf7bd)
Location: include/linux/highmem.h:612
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In fs/buffer.c (ffffffff8154238c)
Location: include/linux/highmem.h:612
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_folio
  - fs/buffer.c:folio_zero_new_buffers
```
```
In fs/mpage.c (ffffffff81543944)
Location: include/linux/highmem.h:612
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8158c609)
Location: include/linux/highmem.h:612
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
```
In fs/ext4/inline.c (ffffffff815e655c)
Location: include/linux/highmem.h:612
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/page-io.c (ffffffff816134c8)
Location: include/linux/highmem.h:612
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/readpage.c (ffffffff8161426e)
Location: include/linux/highmem.h:612
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/hugetlbfs/inode.c (ffffffff816687fe)
Location: include/linux/highmem.h:612
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
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
