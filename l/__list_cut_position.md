# Function: <code>__list_cut_position</code>

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
In drivers/char/virtio_console.c (ffffffff81516da1)
Location: include/linux/list.h:234
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In drivers/char/virtio_console.c (ffffffff81569a49)
Location: include/linux/list.h:234
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In drivers/char/virtio_console.c (ffffffff815962d9)
Location: include/linux/list.h:247
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In fs/ext4/mballoc.c (ffffffff81310296)
Location: include/linux/list.h:247
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff815aa0b9)
Location: include/linux/list.h:247
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81335176)
Location: include/linux/list.h:248
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff81610a29)
Location: include/linux/list.h:248
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81363426)
Location: include/linux/list.h:248
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff8164a5b9)
Location: include/linux/list.h:248
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137b636)
Location: include/linux/list.h:271
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff816687a9)
Location: include/linux/list.h:271
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81242995)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813a5756)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff8169e22a)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff81250e55)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813be5d6)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff816c125a)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff8127f4fa)
Location: include/linux/list.h:345
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/io_uring.c (ffffffff81384825)
Location: include/linux/list.h:345
Inline: True
Inline callers:
  - fs/io_uring.c:io_cancel_defer_files
```
```
In fs/ext4/mballoc.c (ffffffff8140a5ed)
Location: include/linux/list.h:345
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff817749ca)
Location: include/linux/list.h:345
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff8128959a)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/io_uring.c (ffffffff813925ea)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - fs/io_uring.c:io_cancel_defer_files
```
```
In fs/ext4/mballoc.c (ffffffff8141d589)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff8178f72a)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff8128ebfd)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/io_uring.c (ffffffff8139a2ef)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
```
```
In fs/ext4/mballoc.c (ffffffff81423cfa)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff817722ba)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff812ceabd)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/io_uring.c (ffffffff813e9a55)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
```
```
In fs/ext4/mballoc.c (ffffffff81477702)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff817f838a)
Location: include/linux/list.h:363
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff8132cbf2)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff814f9d41)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In io_uring/io_uring.c (ffffffff81e920a2)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In drivers/char/virtio_console.c (ffffffff81936c9a)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff813a31d2)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff815945e0)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In io_uring/io_uring.c (ffffffff8178f3ac)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In drivers/char/virtio_console.c (ffffffff81a96b4a)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff813d6782)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff815cb246)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In io_uring/io_uring.c (ffffffff817d06e1)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In drivers/char/virtio_console.c (ffffffff81ae235a)
Location: include/linux/list.h:373
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff81400459)
Location: include/linux/list.h:454
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In io_uring/io_uring.c (ffffffff81813f04)
Location: include/linux/list.h:454
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In drivers/char/virtio_console.c (ffffffff81b3574a)
Location: include/linux/list.h:454
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
</details>
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
In mm/compaction.c (ffff8000102e8044)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffff800010495190)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffff8000108b4448)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (c050c09c)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (c0656ca0)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (c09ae2bc)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (c0000000003a9fd8)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (c0000000005be9b4)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (c00000000094c54c)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffe0001fda0a)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffe000319dda)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffe00056535c)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff812494a5)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813b6bb6)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff81686caa)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff8123c455)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813a7646)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/acpi/nfit/core.c (ffffffff815f7ebf)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
```
```
In drivers/char/virtio_console.c (ffffffff816648ba)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff81247245)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813b4416)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff816b500a)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
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
In mm/compaction.c (ffffffff81256a75)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813c9025)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff816cf7fa)
Location: include/linux/list.h:331
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
</details>
</li>
</ul>

## Differences
