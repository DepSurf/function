# Function: <code>iter_iov</code>

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
In mm/madvise.c (ffffffff81429669)
Location: include/linux/uio.h:86
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__do_sys_process_madvise
```
```
In fs/read_write.c (ffffffff814abe6b)
Location: include/linux/uio.h:86
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165ec2a)
Location: include/linux/uio.h:86
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff81777b85)
Location: include/linux/uio.h:86
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In io_uring/net.c (ffffffff817d66b3)
Location: include/linux/uio.h:86
Inline: True
Inline callers:
  - io_uring/net.c:io_setup_async_msg
```
```
In io_uring/rw.c (ffffffff817e45d8)
Location: include/linux/uio.h:86
Inline: True
Inline callers:
  - io_uring/rw.c:io_req_map_rw
  - io_uring/rw.c:loop_rw_iter
```
```
In lib/iov_iter.c (ffffffff8180ffae)
Location: include/linux/uio.h:86
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:first_iovec_segment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_is_aligned
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/net/tun.c (ffffffff81c470ad)
Location: include/linux/uio.h:86
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
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
In mm/madvise.c (ffffffff81462e99)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:__do_sys_process_madvise
```
```
In fs/read_write.c (ffffffff814dd21b)
Location: include/linux/uio.h:81
Inline: True
```
```
In fs/fuse/file.c (ffffffff81698a10)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In block/blk-map.c (ffffffff817b9dbf)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - block/blk-map.c:bio_alloc_map_data
```
```
In io_uring/net.c (ffffffff8181a576)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - io_uring/net.c:io_setup_async_msg
```
```
In io_uring/rw.c (ffffffff818286a0)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - io_uring/rw.c:io_req_map_rw
  - io_uring/rw.c:loop_rw_iter
```
```
In lib/iov_iter.c (ffffffff8185953a)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_is_aligned
  - lib/iov_iter.c:iov_iter_advance
```
```
In drivers/net/tun.c (ffffffff81cfc96d)
Location: include/linux/uio.h:81
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
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
