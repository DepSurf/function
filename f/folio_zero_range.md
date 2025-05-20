# Function: <code>folio_zero_range</code>

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
In mm/truncate.c (ffffffff8130822d)
Location: include/linux/highmem.h:435
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In fs/libfs.c (ffffffff8142c90f)
Location: include/linux/highmem.h:435
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (ffffffff814461e3)
Location: include/linux/highmem.h:435
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8148bb7a)
Location: include/linux/highmem.h:435
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_readpage_iter
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
In mm/truncate.c (ffffffff813721e8)
Location: include/linux/highmem.h:450
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff8138f866)
Location: include/linux/highmem.h:450
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In fs/libfs.c (ffffffff814b9d08)
Location: include/linux/highmem.h:450
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (ffffffff814d5177)
Location: include/linux/highmem.h:450
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8151fbdd)
Location: include/linux/highmem.h:450
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_readpage_iter
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
In mm/truncate.c (ffffffff813a4389)
Location: include/linux/highmem.h:504
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff813bf3f8)
Location: include/linux/highmem.h:504
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In fs/libfs.c (ffffffff814eec71)
Location: include/linux/highmem.h:504
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (ffffffff8150c232)
Location: include/linux/highmem.h:504
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
```
```
In fs/iomap/buffered-io.c (ffffffff81557c8d)
Location: include/linux/highmem.h:504
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff815b480d)
Location: include/linux/highmem.h:504
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff815cfee7)
Location: include/linux/highmem.h:504
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
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
In mm/truncate.c (ffffffff813cded6)
Location: include/linux/highmem.h:624
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff813ea44c)
Location: include/linux/highmem.h:624
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In fs/libfs.c (ffffffff81522cc5)
Location: include/linux/highmem.h:624
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (ffffffff81540e29)
Location: include/linux/highmem.h:624
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8158e2ad)
Location: include/linux/highmem.h:624
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff815ed61d)
Location: include/linux/highmem.h:624
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff81608764)
Location: include/linux/highmem.h:624
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
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
