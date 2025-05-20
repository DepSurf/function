# Function: <code>rw_verify_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120c610)
Location: fs/read_write.c:377
Inline: False
Direct callers:
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_splice_to
  - fs/splice.c:do_splice_direct
  - fs/splice.c:SyS_splice
  - fs/aio.c:aio_run_iocb
```
**Symbols:**

```
ffffffff8120c610-ffffffff8120c6ec: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81232a60)
Location: fs/read_write.c:401
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/splice.c:SyS_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_run_iocb
```
**Symbols:**

```
ffffffff81232a60-ffffffff81232b08: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812455e0)
Location: fs/read_write.c:401
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
  - fs/splice.c:SyS_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff812455e0-ffffffff81245688: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250a50)
Location: fs/read_write.c:359
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:SyS_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81250a50-ffffffff81250af9: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272920)
Location: fs/read_write.c:360
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:SyS_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81272920-ffffffff812729c9: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81298800)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff81298800-ffffffff812988a9: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad680)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
```
**Symbols:**

```
ffffffff812ad680-ffffffff812ad729: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca100)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff812ca100-ffffffff812ca1b1: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dbb20)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff812dbb20-ffffffff812dbbd1: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81312100)
Location: fs/read_write.c:366
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:kernel_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81312100-ffffffff813121b1: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131d6c0)
Location: fs/read_write.c:366
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:kernel_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff8131d6c0-ffffffff8131d771: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81325bb5)
Location: fs/read_write.c:366
Inline: True
Inline callers:
  - fs/read_write.c:kernel_read
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81323990-ffffffff813239e7: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81373835)
Location: fs/read_write.c:366
Inline: True
Inline callers:
  - fs/read_write.c:kernel_read
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81370e90-ffffffff81370ee7: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f1e15)
Location: fs/read_write.c:366
Inline: True
Inline callers:
  - fs/read_write.c:kernel_read
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_read
```
**Symbols:**

```
ffffffff813eeae0-ffffffff813eeb5b: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147a175)
Location: fs/read_write.c:355
Inline: True
Inline callers:
  - fs/read_write.c:kernel_read
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
```
**Symbols:**

```
ffffffff814773c0-ffffffff8147743b: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814aec75)
Location: fs/read_write.c:355
Inline: True
Inline callers:
  - fs/read_write.c:kernel_read
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
```
**Symbols:**

```
ffffffff814abd40-ffffffff814abdbb: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814dd910)
Location: fs/read_write.c:355
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_iter_read
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:kernel_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:vfs_splice_read
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_read
```
**Symbols:**

```
ffffffff814dd910-ffffffff814dda47: rw_verify_area (STB_GLOBAL)
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
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381498)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffff800010381498-ffff800010381584: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056bc8c)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
c056bc8c-c056bdac: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004777d0)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
c0000000004777d0-c0000000004778f4: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe00025651a)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffe00025651a-ffffffe0002565ee: rw_verify_area (STB_GLOBAL)
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
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4100)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff812d4100-ffffffff812d41b1: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c4d80)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff812c4d80-ffffffff812c4e31: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d1f10)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff812d1f10-ffffffff812d1fc1: rw_verify_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file *file, const loff_t *ppos, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e2d70)
Location: fs/read_write.c:365
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_iter_read
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice_direct
  - fs/splice.c:do_splice_to
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff812e2d70-ffffffff812e2e21: rw_verify_area (STB_GLOBAL)
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
