# Function: <code>grab_cache_page_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e170)
Location: mm/filemap.c:2470
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8118e170-ffffffff8118e1ac: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1330)
Location: mm/filemap.c:2648
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/iomap.c:iomap_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff811a1330-ffffffff811a136c: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b0f30)
Location: mm/filemap.c:2764
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/iomap.c:iomap_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff811b0f30-ffffffff811b0f66: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b88d0)
Location: mm/filemap.c:2904
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff811b88d0-ffffffff811b890a: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd110)
Location: mm/filemap.c:3080
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff811cd110-ffffffff811cd14d: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ee240)
Location: mm/filemap.c:3080
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff811ee240-ffffffff811ee279: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200550)
Location: mm/filemap.c:3149
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81200550-ffffffff81200586: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81216ab0)
Location: mm/filemap.c:3268
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81216ab0-ffffffff81216ae8: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812243c0)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff812243c0-ffffffff812243f8: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812537b0)
Location: mm/filemap.c:3259
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff812537b0-ffffffff812537ea: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e430)
Location: mm/filemap.c:3353
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff8125e430-ffffffff8125e46a: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81260990)
Location: mm/filemap.c:3601
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81260990-ffffffff812609ca: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129d380)
Location: mm/filemap.c:3718
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff8129d380-ffffffff8129d3ba: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300aa0)
Location: mm/folio-compat.c:133
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81300aa0-ffffffff81300ac4: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b360)
Location: mm/folio-compat.c:105
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff8136b360-ffffffff8136b384: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d4e0)
Location: mm/folio-compat.c:106
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff8139d4e0-ffffffff8139d504: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7240)
Location: mm/folio-compat.c:100
Inline: False
Direct callers:
  - fs/buffer.c:block_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff813c7240-ffffffff813c7264: grab_cache_page_write_begin (STB_GLOBAL)
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
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1a48)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffff8000102b1a48-ffff8000102b1aac: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04de694)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
c04de694-c04de6d0: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003694b0)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
c0000000003694b0-c000000000369514: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d737c)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffe0001d737c-ffffffe0001d73ce: grab_cache_page_write_begin (STB_GLOBAL)
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
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121ca10)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8121ca10-ffffffff8121ca48: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120fbf0)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8120fbf0-ffffffff8120fc28: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121a7b0)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8121a7b0-ffffffff8121a7e8: grab_cache_page_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *grab_cache_page_write_begin(struct address_space *mapping, long unsigned int index, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81229880)
Location: mm/filemap.c:3225
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81229880-ffffffff812298b8: grab_cache_page_write_begin (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
