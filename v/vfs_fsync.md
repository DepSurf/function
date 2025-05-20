# Function: <code>vfs_fsync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81240640)
Location: fs/sync.c:207
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:loop_queue_work
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81240640-ffffffff8124065e: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812689c6)
Location: fs/sync.c:207
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81268980-ffffffff8126899e: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8127b9e6)
Location: fs/sync.c:208
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff8127b9a0-ffffffff8127b9be: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81288d76)
Location: fs/sync.c:208
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81288d30-ffffffff81288d4e: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812ab8b6)
Location: fs/sync.c:209
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff812ab870-ffffffff812ab88e: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812d24f6)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff812d24b0-ffffffff812d24ce: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812e78d6)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff812e7890-ffffffff812e78ae: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81306186)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81306140-ffffffff8130615e: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81319206)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff813191c0-ffffffff813191de: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81352fd3)
Location: fs/sync.c:213
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81353040-ffffffff813530b9: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8135f8b3)
Location: fs/sync.c:213
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8135f920-ffffffff8135f999: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81366522)
Location: fs/sync.c:212
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81366590-ffffffff81366609: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813b4c92)
Location: fs/sync.c:213
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff813b4d00-ffffffff813b4d79: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8143a256)
Location: fs/sync.c:200
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8143a2d0-ffffffff8143a35f: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814c8656)
Location: fs/sync.c:200
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff814c86e0-ffffffff814c876f: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814fe886)
Location: fs/sync.c:200
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff814fe910-ffffffff814fe9a5: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81533486)
Location: fs/sync.c:200
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81533510-ffffffff815335a5: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffff8000103d0214)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffff8000103d01a0-ffff8000103d01dc: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05ab590)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
c05ab528-c05ab564: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d284c)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
c0000000004d27e0-c0000000004d2804: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c504)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffe00028c49a-ffffffe00028c4d2: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813117e6)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff813117a0-ffffffff813117be: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813023f6)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff813023b0-ffffffff813023ce: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8130f5d6)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8130f590-ffffffff8130f5ae: vfs_fsync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_fsync(struct file *file, int datasync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81320dd6)
Location: fs/sync.c:210
Inline: True
Inline callers:
  - fs/sync.c:do_fsync
Direct callers:
  - fs/aio.c:aio_fsync_work
  - fs/iomap/swapfile.c:iomap_swapfile_activate
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/loop.c:__loop_update_dio
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81320d90-ffffffff81320dae: vfs_fsync (STB_GLOBAL)
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
