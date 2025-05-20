# Function: <code>ioprio_value</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fe64b)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In block/blk-ioc.c (0)
Location: include/uapi/linux/ioprio.h:110
Inline: True
```
```
In block/ioprio.c (ffffffff8178ecbd)
Location: include/uapi/linux/ioprio.h:110
Inline: True
```
```
In block/blk-ioprio.c (ffffffff817a90a0)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - block/blk-ioprio.c:blkcg_set_ioprio
```
```
In drivers/block/loop.c (0)
Location: include/uapi/linux/ioprio.h:110
Inline: True
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
In mm/filemap.c (ffffffff813bc3ce)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
```
```
In mm/page_io.c (ffffffff814645e2)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814dd376)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff8151cebb)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff8153098d)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff8155ca0e)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/ext4/super.c (ffffffff8163714c)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In block/blk-core.c (ffffffff817b471e)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/blk-ioc.c (0)
Location: include/uapi/linux/ioprio.h:110
Inline: True
```
```
In block/ioprio.c (ffffffff817d15b7)
Location: include/uapi/linux/ioprio.h:110
Inline: True
```
```
In block/blk-ioprio.c (ffffffff817ece60)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - block/blk-ioprio.c:blkcg_set_ioprio
```
```
In io_uring/rw.c (ffffffff818294ba)
Location: include/uapi/linux/ioprio.h:110
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
```
```
In drivers/block/loop.c (0)
Location: include/uapi/linux/ioprio.h:110
Inline: True
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
