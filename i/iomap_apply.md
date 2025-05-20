# Function: <code>iomap_apply</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129be70)
Location: fs/iomap.c:45
Inline: False
Direct callers:
  - fs/iomap.c:iomap_fiemap
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_zero_range
  - fs/iomap.c:iomap_file_buffered_write
```
**Symbols:**

```
ffffffff8129be70-ffffffff8129bf99: iomap_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1970)
Location: fs/iomap.c:43
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_fiemap
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_zero_range
  - fs/iomap.c:iomap_file_dirty
  - fs/iomap.c:iomap_file_buffered_write
```
**Symbols:**

```
ffffffff812b1970-ffffffff812b1a99: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812becb0)
Location: fs/iomap.c:45
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_seek_data
  - fs/iomap.c:iomap_seek_hole
  - fs/iomap.c:iomap_fiemap
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_zero_range
  - fs/iomap.c:iomap_file_dirty
  - fs/iomap.c:iomap_file_buffered_write
```
**Symbols:**

```
ffffffff812becb0-ffffffff812bedb8: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e2720)
Location: fs/iomap.c:45
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_seek_data
  - fs/iomap.c:iomap_seek_hole
  - fs/iomap.c:iomap_fiemap
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_zero_range
  - fs/iomap.c:iomap_file_dirty
  - fs/iomap.c:iomap_file_buffered_write
```
**Symbols:**

```
ffffffff812e2720-ffffffff812e2830: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f0a0)
Location: fs/iomap.c:47
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap.c:iomap_bmap
  - fs/iomap.c:iomap_swapfile_activate
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_seek_data
  - fs/iomap.c:iomap_seek_hole
  - fs/iomap.c:iomap_fiemap
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_zero_range
  - fs/iomap.c:iomap_file_dirty
  - fs/iomap.c:iomap_file_buffered_write
```
**Symbols:**

```
ffffffff8130f0a0-ffffffff8130f1cb: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81325d40)
Location: fs/iomap.c:48
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap.c:iomap_bmap
  - fs/iomap.c:iomap_swapfile_activate
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_seek_data
  - fs/iomap.c:iomap_seek_hole
  - fs/iomap.c:iomap_fiemap
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_zero_range
  - fs/iomap.c:iomap_file_dirty
  - fs/iomap.c:iomap_file_buffered_write
  - fs/iomap.c:iomap_readpages
  - fs/iomap.c:iomap_readpage
```
**Symbols:**

```
ffffffff81325d40-ffffffff81325e71: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/apply.c (0)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff8134ae70-ffffffff8134aea4: iomap_apply.cold (STB_LOCAL)
ffffffff8134ad30-ffffffff8134ae70: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffff81362ff0)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff81362ff0-ffffffff81363141: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffff813a98c0)
Location: fs/iomap/apply.c:24
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff813a98c0-ffffffff813a9c17: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffff813baf60)
Location: fs/iomap/apply.c:24
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff813baf60-ffffffff813bb270: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffff813c20a0)
Location: fs/iomap/apply.c:24
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff813c20a0-ffffffff813c23a4: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffff800010429bf0)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffff800010429bf0-ffff800010429d40: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (c05f24cc)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
c05f24cc-c05f26c8: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (c000000000539d60)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
c000000000539d60-c000000000539f38: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffe0002c76de)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffe0002c76de-ffffffe0002c77c0: iomap_apply (STB_GLOBAL)
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
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffff8135b5d0)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff8135b5d0-ffffffff8135b721: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffff8134c270)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff8134c270-ffffffff8134c3c1: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffff813590a0)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff813590a0-ffffffff813591f1: iomap_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops *ops, void *data, iomap_actor_t actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/apply.c (ffffffff8136c7a0)
Location: fs/iomap/apply.c:23
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_dirty
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff8136c7a0-ffffffff8136c8f1: iomap_apply (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops *ops</code> ➡️ <code>const struct iomap_ops *ops</code>
</li>
</ul>
</details>
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
