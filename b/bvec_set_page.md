# Function: <code>bvec_set_page</code>

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
In mm/page_io.c (ffffffff8142ae53)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/splice.c (ffffffff814fcd48)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
```
```
In fs/coredump.c (ffffffff815511bb)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In block/bio.c (ffffffff8176bb02)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - block/bio.c:bio_add_folio_nofail
  - block/bio.c:bio_add_hw_page
```
```
In block/bio-integrity.c (ffffffff817b4500)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In io_uring/rsrc.c (ffffffff817e366f)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
```
```
In drivers/block/virtio_blk.c (ffffffff81b7ecc8)
Location: include/linux/bvec.h:44
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81be4f08)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
```
```
In net/core/skbuff.c (ffffffff81e10f63)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_send_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f85ff5)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81fa7e8d)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In mm/page_io.c (ffffffff81464660)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/splice.c (ffffffff81531978)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
```
```
In fs/coredump.c (ffffffff815870b1)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In block/bio.c (ffffffff817adfa2)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - block/bio.c:bio_add_folio_nofail
  - block/bio.c:bio_add_hw_page
```
```
In block/bio-integrity.c (ffffffff817f95f8)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_map_user
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In io_uring/rsrc.c (ffffffff81827716)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
```
```
In drivers/block/virtio_blk.c (ffffffff81bd33c3)
Location: include/linux/bvec.h:44
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81c3a068)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
```
```
In net/core/skbuff.c (ffffffff81ecda93)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_send_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d5d5)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff8207514d)
Location: include/linux/bvec.h:44
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
