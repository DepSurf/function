# Function: <code>iov_iter_iovec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120bc6d)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - fs/read_write.c:do_loop_readv_writev
```
```
In block/bio.c (ffffffff813b256c)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-map.c (ffffffff813bf436)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81231ab3)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - fs/read_write.c:do_loop_readv_writev
```
```
In block/bio.c (ffffffff813f5be5)
Location: include/linux/uio.h:57
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244063)
Location: include/linux/uio.h:63
Inline: True
Inline callers:
  - fs/read_write.c:do_loop_readv_writev
```
```
In block/bio.c (ffffffff8140f5f5)
Location: include/linux/uio.h:63
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250eed)
Location: include/linux/uio.h:67
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In block/bio.c (ffffffff8141d020)
Location: include/linux/uio.h:67
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
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
In fs/read_write.c (ffffffff81272aed)
Location: include/linux/uio.h:67
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
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
In fs/read_write.c (ffffffff812989d9)
Location: include/linux/uio.h:67
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad85a)
Location: include/linux/uio.h:104
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca4dc)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dbefc)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (ffffffff81340afa)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81310a87)
Location: include/linux/uio.h:106
Inline: True
```
```
In fs/io_uring.c (ffffffff8137c064)
Location: include/linux/uio.h:106
Inline: True
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
In mm/madvise.c (ffffffff812c1a8f)
Location: include/linux/uio.h:105
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In fs/read_write.c (ffffffff8131cae7)
Location: include/linux/uio.h:105
Inline: True
```
```
In fs/io_uring.c (ffffffff8138987f)
Location: include/linux/uio.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:loop_rw_iter
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
In mm/madvise.c (ffffffff812c8988)
Location: include/linux/uio.h:113
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In fs/read_write.c (ffffffff81322c57)
Location: include/linux/uio.h:113
Inline: True
```
```
In fs/io_uring.c (ffffffff8139069c)
Location: include/linux/uio.h:113
Inline: True
Inline callers:
  - fs/io_uring.c:loop_rw_iter
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
In mm/madvise.c (ffffffff8130d908)
Location: include/linux/uio.h:123
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In fs/read_write.c (ffffffff81370147)
Location: include/linux/uio.h:123
Inline: True
```
```
In fs/io_uring.c (ffffffff813ddc72)
Location: include/linux/uio.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:loop_rw_iter
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
In mm/madvise.c (ffffffff81378dd1)
Location: include/linux/uio.h:125
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In fs/read_write.c (ffffffff813eec19)
Location: include/linux/uio.h:125
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816c86ea)
Location: include/linux/uio.h:125
Inline: True
Inline callers:
  - io_uring/io_uring.c:loop_rw_iter
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
In mm/madvise.c (ffffffff813f6791)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In fs/read_write.c (ffffffff81477519)
Location: include/linux/uio.h:144
Inline: True
```
```
In io_uring/rw.c (ffffffff817a330a)
Location: include/linux/uio.h:144
Inline: True
Inline callers:
  - io_uring/rw.c:loop_rw_iter
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381974)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (ffff800010400abc)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c108)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (c05d298c)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000477e00)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (c00000000050a4b8)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002568ac)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (ffffffe0002ad0f6)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d44dc)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (ffffffff813390da)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c515c)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (ffffffff81329e0a)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d22ec)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (ffffffff81336baa)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e314c)
Location: include/linux/uio.h:106
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
```
```
In fs/io_uring.c (ffffffff81349c7e)
Location: include/linux/uio.h:106
Inline: True
```
</details>
</li>
</ul>

## Differences
