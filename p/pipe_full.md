# Function: <code>pipe_full</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124c9c2)
Location: include/linux/pipe_fs_i.h:151
Inline: True
```
```
In fs/pipe.c (ffffffff813207ba)
Location: include/linux/pipe_fs_i.h:151
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff813529e8)
Location: include/linux/pipe_fs_i.h:151
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:wait_for_space
  - fs/splice.c:add_to_pipe
```
```
In lib/iov_iter.c (ffffffff81586d74)
Location: include/linux/pipe_fs_i.h:151
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81256e02)
Location: include/linux/pipe_fs_i.h:151
Inline: True
```
```
In fs/pipe.c (ffffffff8132bd2a)
Location: include/linux/pipe_fs_i.h:151
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8135f2c8)
Location: include/linux/pipe_fs_i.h:151
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
```
```
In lib/iov_iter.c (ffffffff815a4044)
Location: include/linux/pipe_fs_i.h:151
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125b292)
Location: include/linux/pipe_fs_i.h:153
Inline: True
```
```
In fs/pipe.c (ffffffff81331d67)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff81365be9)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
```
```
In lib/iov_iter.c (ffffffff815aaf34)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8129709e)
Location: include/linux/pipe_fs_i.h:153
Inline: True
```
```
In fs/pipe.c (ffffffff8137f4e7)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff813b44d9)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
```
```
In lib/iov_iter.c (ffffffff81614547)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter
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
In kernel/watch_queue.c (ffffffff812ecf12)
Location: include/linux/pipe_fs_i.h:153
Inline: True
```
```
In fs/pipe.c (ffffffff813ff5ee)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff814398b9)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
```
```
In lib/iov_iter.c (ffffffff816e10dd)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter
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
In kernel/watch_queue.c (ffffffff81357292)
Location: include/linux/pipe_fs_i.h:153
Inline: True
```
```
In fs/pipe.c (ffffffff814893ae)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff814c7be9)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
```
```
In lib/iov_iter.c (ffffffff817d156d)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:append_pipe
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
In kernel/watch_queue.c (ffffffff81388b12)
Location: include/linux/pipe_fs_i.h:153
Inline: True
```
```
In mm/filemap.c (ffffffff8139269a)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:splice_folio_into_pipe
```
```
In mm/shmem.c (ffffffff813c0861)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
```
```
In fs/pipe.c (ffffffff814be2de)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff814fdc3c)
Location: include/linux/pipe_fs_i.h:153
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
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
In kernel/watch_queue.c (ffffffff813b2572)
Location: include/linux/pipe_fs_i.h:169
Inline: True
```
```
In mm/filemap.c (ffffffff813bc2e3)
Location: include/linux/pipe_fs_i.h:169
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:splice_folio_into_pipe
```
```
In mm/shmem.c (ffffffff813eb4ee)
Location: include/linux/pipe_fs_i.h:169
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
```
```
In fs/pipe.c (ffffffff814f075e)
Location: include/linux/pipe_fs_i.h:169
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8153283a)
Location: include/linux/pipe_fs_i.h:169
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
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
