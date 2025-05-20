# Function: <code>filemap_invalidate_lock_shared</code>

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
In mm/filemap.c (ffffffff8129d715)
Location: include/linux/fs.h:839
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff812a8adf)
Location: include/linux/fs.h:839
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/ext4/file.c (ffffffff81454bde)
Location: include/linux/fs.h:839
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8146bff8)
Location: include/linux/fs.h:839
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff814fa5d7)
Location: include/linux/fs.h:839
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
In mm/filemap.c (ffffffff812f45af)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff81301c4a)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/secretmem.c (ffffffff813e39fa)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/file.c (ffffffff814d239a)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814ebfc0)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff8158aaa6)
Location: include/linux/fs.h:794
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
In mm/filemap.c (ffffffff8135e692)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff8136c3bd)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/secretmem.c (ffffffff8146b3d7)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/file.c (ffffffff8156aee7)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81585d2a)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff81631203)
Location: include/linux/fs.h:809
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
In mm/filemap.c (ffffffff81391435)
Location: include/linux/fs.h:824
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff8139e5d3)
Location: include/linux/fs.h:824
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/secretmem.c (ffffffff814a01bd)
Location: include/linux/fs.h:824
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/file.c (ffffffff815a2d9d)
Location: include/linux/fs.h:824
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815bc5e5)
Location: include/linux/fs.h:824
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff81669439)
Location: include/linux/fs.h:824
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
In mm/filemap.c (ffffffff813bb195)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
```
```
In mm/readahead.c (ffffffff813c826c)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/secretmem.c (ffffffff814cf848)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/ext4/file.c (ffffffff815dbabd)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815f53c5)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/dax.c (ffffffff816a3739)
Location: include/linux/fs.h:857
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
