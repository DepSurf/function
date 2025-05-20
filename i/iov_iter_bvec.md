# Function: <code>iov_iter_bvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_bvec(struct iov_iter *i, int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb840)
Location: lib/iov_iter.c:542
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff813fb840-ffffffff813fb864: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_bvec(struct iov_iter *i, int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81442bf0)
Location: lib/iov_iter.c:491
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81442bf0-ffffffff81442c14: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_bvec(struct iov_iter *i, int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145fe00)
Location: lib/iov_iter.c:818
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8145fe00-ffffffff8145fe24: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_bvec(struct iov_iter *i, int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464ef0)
Location: lib/iov_iter.c:944
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81464ef0-ffffffff81464f14: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_bvec(struct iov_iter *i, int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490e70)
Location: lib/iov_iter.c:946
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81490e70-ffffffff81490e93: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_bvec(struct iov_iter *i, int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c60c0)
Location: lib/iov_iter.c:1076
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff814c60c0-ffffffff814c60e3: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814d9ee0)
Location: lib/iov_iter.c:1130
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff814d9ee0-ffffffff814d9f0e: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8150aca9-ffffffff8150acda: iov_iter_bvec.cold (STB_LOCAL)
ffffffff81505760-ffffffff8150579b: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815236a0)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff815236a0-ffffffff815236c9: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81586ca0)
Location: lib/iov_iter.c:1178
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - fs/io_uring.c:io_import_fixed
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81586ca0-ffffffff81586cc9: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a3f70)
Location: lib/iov_iter.c:1185
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - fs/io_uring.c:io_import_fixed
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff815a3f70-ffffffff815a3f99: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815aae80)
Location: lib/iov_iter.c:1287
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - fs/io_uring.c:io_import_iovec
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff815aae80-ffffffff815aaeac: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614160)
Location: lib/iov_iter.c:1143
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - fs/io_uring.c:io_import_iovec
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81614160-ffffffff8161418a: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e0a90)
Location: lib/iov_iter.c:1195
Inline: False
Direct callers:
  - mm/page_io.c:__swap_read_unplug
  - mm/page_io.c:swap_write_unplug
  - fs/splice.c:iter_file_splice_write
  - io_uring/io_uring.c:__io_import_iovec
  - drivers/block/loop.c:lo_read_simple
```
**Symbols:**

```
ffffffff816e0a90-ffffffff816e0acd: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d0df0)
Location: lib/iov_iter.c:1013
Inline: False
Direct callers:
  - mm/page_io.c:__swap_read_unplug
  - mm/page_io.c:swap_write_unplug
  - fs/splice.c:iter_file_splice_write
  - fs/coredump.c:dump_user_range
  - io_uring/rsrc.c:io_import_fixed
  - drivers/block/loop.c:lo_read_simple
```
**Symbols:**

```
ffffffff817d0df0-ffffffff817d0e2d: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8180fbc0)
Location: lib/iov_iter.c:726
Inline: False
Direct callers:
  - mm/page_io.c:__swap_read_unplug
  - mm/page_io.c:swap_write_unplug
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:copy_splice_read
  - fs/coredump.c:dump_user_range
  - io_uring/rsrc.c:io_import_fixed
  - drivers/block/loop.c:lo_read_simple
  - net/core/skbuff.c:__skb_send_sock
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff8180fbc0-ffffffff8180fbfd: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81855830)
Location: lib/iov_iter.c:626
Inline: False
Direct callers:
  - mm/page_io.c:__swap_read_unplug
  - mm/page_io.c:swap_write_unplug
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:copy_splice_read
  - fs/coredump.c:dump_user_range
  - block/bio-integrity.c:bio_integrity_copy_user
  - block/bio-integrity.c:bio_integrity_free
  - io_uring/rsrc.c:io_import_fixed
  - drivers/block/loop.c:lo_read_simple
  - net/core/skbuff.c:__skb_send_sock
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81855830-ffffffff8185586d: iov_iter_bvec (STB_GLOBAL)
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
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d4f8)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffff80001062d4f8-ffff80001062d534: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d40ec)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - fs/io_uring.c:io_import_iovec
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
c07d40ec-c07d4150: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d06c0)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
c0000000007d06c0-c0000000007d06f8: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d350)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffe00045d350-ffffffe00045d378: iov_iter_bvec (STB_GLOBAL)
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
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151bc80)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8151bc80-ffffffff8151bca9: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150bf70)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8150bf70-ffffffff8150bf99: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81517d10)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81517d10-ffffffff81517d39: iov_iter_bvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter *i, unsigned int direction, const struct bio_vec *bvec, long unsigned int nr_segs, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815314b0)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff815314b0-ffffffff815314d9: iov_iter_bvec (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int direction</code> ➡️ <code>unsigned int direction</code>
</li>
</ul>
</details>
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
