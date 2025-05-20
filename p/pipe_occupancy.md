# Function: <code>pipe_occupancy</code>

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
Location: include/linux/pipe_fs_i.h:140
Inline: True
```
```
In fs/pipe.c (ffffffff8132085d)
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
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
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:wait_for_space
  - fs/splice.c:pipe_to_sendpage
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff81470b0e)
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In lib/iov_iter.c (ffffffff81589554)
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
```
In drivers/char/virtio_console.c (ffffffff81777463)
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
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
Location: include/linux/pipe_fs_i.h:140
Inline: True
```
```
In fs/pipe.c (ffffffff8132bddd)
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
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
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:pipe_to_sendpage
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8148b3ee)
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In lib/iov_iter.c (ffffffff815a7cc6)
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
```
In drivers/char/virtio_console.c (ffffffff81792193)
Location: include/linux/pipe_fs_i.h:140
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
```
```
In fs/pipe.c (ffffffff81331e1d)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:pipe_to_sendpage
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8149145e)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In lib/iov_iter.c (ffffffff815ad647)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/char/virtio_console.c (ffffffff81774c13)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
```
```
In fs/pipe.c (ffffffff8137f5ad)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:pipe_to_sendpage
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff814e8e7e)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In lib/iov_iter.c (ffffffff81614505)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/char/virtio_console.c (ffffffff817f9e43)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
```
```
In fs/pipe.c (ffffffff813ff6f1)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:pipe_to_sendpage
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff81576cf5)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In lib/iov_iter.c (ffffffff816e0f82)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/char/virtio_console.c (ffffffff81938948)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
```
```
In fs/pipe.c (ffffffff814894d1)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:pipe_to_sendpage
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8161c4d5)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In lib/iov_iter.c (ffffffff817d1577)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_pipe
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:append_pipe
```
```
In drivers/char/virtio_console.c (ffffffff81a98a08)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
```
```
In mm/filemap.c (ffffffff8139269a)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:splice_folio_into_pipe
```
```
In mm/shmem.c (ffffffff813c0791)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
```
```
In fs/pipe.c (ffffffff814be401)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
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
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:copy_splice_read
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8165462f)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In drivers/char/virtio_console.c (ffffffff81ae421e)
Location: include/linux/pipe_fs_i.h:142
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
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
Location: include/linux/pipe_fs_i.h:158
Inline: True
```
```
In mm/filemap.c (ffffffff813bc2e3)
Location: include/linux/pipe_fs_i.h:158
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:splice_folio_into_pipe
```
```
In mm/shmem.c (ffffffff813eb421)
Location: include/linux/pipe_fs_i.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
```
```
In fs/pipe.c (ffffffff814f0881)
Location: include/linux/pipe_fs_i.h:158
Inline: True
Inline callers:
  - fs/pipe.c:pipe_resize_ring
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
Location: include/linux/pipe_fs_i.h:158
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:copy_splice_read
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8168ecbf)
Location: include/linux/pipe_fs_i.h:158
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In drivers/char/virtio_console.c (ffffffff81b375ee)
Location: include/linux/pipe_fs_i.h:158
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
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
