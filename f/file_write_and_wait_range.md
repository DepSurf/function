# Function: <code>file_write_and_wait_range</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ba050)
Location: mm/filemap.c:645
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
```
**Symbols:**

```
ffffffff811ba050-ffffffff811ba103: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cda30)
Location: mm/filemap.c:747
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync_common
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff811cda30-ffffffff811cdad3: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef560)
Location: mm/filemap.c:747
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync_common
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff811ef560-ffffffff811ef603: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81201360)
Location: mm/filemap.c:724
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff81201360-ffffffff81201403: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218f50)
Location: mm/filemap.c:767
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff81218f50-ffffffff81218ff3: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226830)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff81226830-ffffffff812268ed: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812517c0)
Location: mm/filemap.c:754
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff812517c0-ffffffff81251873: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125cee0)
Location: mm/filemap.c:755
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff8125cee0-ffffffff8125cf93: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261b60)
Location: mm/filemap.c:786
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff81261b60-ffffffff81261bf5: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129b030)
Location: mm/filemap.c:804
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - block/fops.c:blkdev_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff8129b030-ffffffff8129b115: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f58c0)
Location: mm/filemap.c:773
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - block/fops.c:blkdev_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff812f58c0-ffffffff812f597c: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135f770)
Location: mm/filemap.c:768
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - block/fops.c:blkdev_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff8135f770-ffffffff8135f82c: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390750)
Location: mm/filemap.c:775
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/buffer.c:generic_buffers_fsync_noflush
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - block/fops.c:blkdev_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff81390750-ffffffff81390809: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba3d0)
Location: mm/filemap.c:770
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/buffer.c:generic_buffers_fsync_noflush
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - block/fops.c:blkdev_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff813ba3d0-ffffffff813ba489: file_write_and_wait_range (STB_GLOBAL)
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
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3b68)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffff8000102b3b68-ffff8000102b3c60: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0e34)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
c04e0e34-c04e0ee8: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036a970)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
c00000000036a970-c00000000036aa78: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d90e0)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffe0001d90e0-ffffffe0001d918e: file_write_and_wait_range (STB_GLOBAL)
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
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121ee80)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff8121ee80-ffffffff8121ef3d: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212040)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff81212040-ffffffff812120fd: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121cc20)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff8121cc20-ffffffff8121ccdd: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file *file, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122bcb0)
Location: mm/filemap.c:776
Inline: False
Direct callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/block_dev.c:blkdev_fsync
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fuse/file.c:fuse_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
**Symbols:**

```
ffffffff8122bcb0-ffffffff8122bd6d: file_write_and_wait_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
