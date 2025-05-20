# Function: <code>__get_task_ioprio</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __get_task_ioprio(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81752a90)
Location: block/ioprio.c:148
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/seq_file.c:seq_read
  - fs/splice.c:generic_file_splice_read
  - fs/aio.c:aio_prep_rw
  - block/blk-mq.c:blk_mq_submit_bio
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
  - io_uring/rw.c:io_prep_rw
```
**Symbols:**

```
ffffffff81752a90-ffffffff81752b1c: __get_task_ioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __get_task_ioprio(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8178ec50)
Location: block/ioprio.c:149
Inline: True
Direct callers:
  - mm/filemap.c:filemap_splice_read
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
  - fs/seq_file.c:seq_read
  - fs/splice.c:copy_splice_read
  - fs/aio.c:aio_prep_rw
  - block/blk-mq.c:blk_mq_submit_bio
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
  - io_uring/rw.c:io_prep_rw
```
**Symbols:**

```
ffffffff8178ec50-ffffffff8178ece4: __get_task_ioprio (STB_GLOBAL)
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
In mm/filemap.c (ffffffff813bc151)
Location: include/linux/ioprio.h:57
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
```
```
In mm/page_io.c (ffffffff8146458b)
Location: include/linux/ioprio.h:57
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814dd318)
Location: include/linux/ioprio.h:57
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff8151ce65)
Location: include/linux/ioprio.h:57
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff815307f9)
Location: include/linux/ioprio.h:57
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff8155c9b1)
Location: include/linux/ioprio.h:57
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In block/blk-core.c (ffffffff817b46c5)
Location: include/linux/ioprio.h:57
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/ioprio.c (ffffffff817d155e)
Location: include/linux/ioprio.h:57
Inline: True
```
```
In io_uring/rw.c (ffffffff8182945c)
Location: include/linux/ioprio.h:57
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
