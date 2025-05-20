# Function: <code>filemap_invalidate_unlock_shared</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129d7e6)
Location: include/linux/fs.h:850
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff812a8bcd)
Location: include/linux/fs.h:850
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/ext4/file.c (ffffffff81454c0a)
Location: include/linux/fs.h:850
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8146c03d)
Location: include/linux/fs.h:850
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff814fa5c0)
Location: include/linux/fs.h:850
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
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
In mm/filemap.c (ffffffff812f4683)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff81301d0e)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/secretmem.c (ffffffff813e3aa7)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/file.c (ffffffff814d23c2)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814ec007)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8158aaef)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
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
In mm/filemap.c (ffffffff8135e97d)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff8136c48e)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/secretmem.c (ffffffff8146b484)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/file.c (ffffffff8156af0f)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81585d71)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8163124c)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
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
In mm/filemap.c (ffffffff81391512)
Location: include/linux/fs.h:835
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff8139e6b0)
Location: include/linux/fs.h:835
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/secretmem.c (ffffffff814a0266)
Location: include/linux/fs.h:835
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/file.c (ffffffff815a2dc5)
Location: include/linux/fs.h:835
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815bc62c)
Location: include/linux/fs.h:835
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff81669482)
Location: include/linux/fs.h:835
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
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
In mm/filemap.c (ffffffff813bb27c)
Location: include/linux/fs.h:868
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff813c83df)
Location: include/linux/fs.h:868
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/secretmem.c (ffffffff814cf8ed)
Location: include/linux/fs.h:868
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/file.c (ffffffff815dbae5)
Location: include/linux/fs.h:868
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815f540c)
Location: include/linux/fs.h:868
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff816a3782)
Location: include/linux/fs.h:868
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
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
