# Function: <code>task_nice_ioprio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e18ca)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81427af7)
Location: include/linux/ioprio.h:53
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814416f7)
Location: include/linux/ioprio.h:52
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814509e6)
Location: include/linux/ioprio.h:52
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147c026)
Location: include/linux/ioprio.h:54
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b10e0)
Location: include/linux/ioprio.h:54
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
```
</details>
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81752aea)
Location: include/linux/ioprio.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8178ec7e)
Location: include/linux/ioprio.h:30
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
In mm/filemap.c (ffffffff813bc389)
Location: include/linux/ioprio.h:30
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
```
```
In mm/page_io.c (ffffffff8146459f)
Location: include/linux/ioprio.h:30
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814dd32b)
Location: include/linux/ioprio.h:30
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff8151ce78)
Location: include/linux/ioprio.h:30
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff81530942)
Location: include/linux/ioprio.h:30
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff8155c9cb)
Location: include/linux/ioprio.h:30
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In block/blk-core.c (ffffffff817b46db)
Location: include/linux/ioprio.h:30
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/ioprio.c (ffffffff817d1578)
Location: include/linux/ioprio.h:30
Inline: True
```
```
In io_uring/rw.c (ffffffff81829475)
Location: include/linux/ioprio.h:30
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
