# Function: <code>list_cut_position</code>

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
In drivers/char/virtio_console.c (ffffffff81516d78)
Location: include/linux/list.h:260
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
In drivers/char/virtio_console.c (ffffffff81569a1e)
Location: include/linux/list.h:260
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
In drivers/char/virtio_console.c (ffffffff815962ae)
Location: include/linux/list.h:273
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
In fs/ext4/mballoc.c (ffffffff8131025c)
Location: include/linux/list.h:273
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff815aa08e)
Location: include/linux/list.h:273
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
In fs/ext4/mballoc.c (ffffffff8133513c)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff816109fe)
Location: include/linux/list.h:274
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
In fs/ext4/mballoc.c (ffffffff813633ec)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff8164a58e)
Location: include/linux/list.h:274
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
In fs/ext4/mballoc.c (ffffffff8137b5fc)
Location: include/linux/list.h:297
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff8166877e)
Location: include/linux/list.h:297
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
In mm/compaction.c (ffffffff81242935)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813a571c)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff8169e201)
Location: include/linux/list.h:357
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
In mm/compaction.c (ffffffff81250df5)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813be59c)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff816c1231)
Location: include/linux/list.h:357
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
In mm/compaction.c (ffffffff8127f4d5)
Location: include/linux/list.h:371
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/io_uring.c (ffffffff81384805)
Location: include/linux/list.h:371
Inline: True
Inline callers:
  - fs/io_uring.c:io_cancel_defer_files
```
```
In fs/ext4/mballoc.c (ffffffff8140a5b0)
Location: include/linux/list.h:371
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff817749a1)
Location: include/linux/list.h:371
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
In mm/compaction.c (ffffffff81289575)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/io_uring.c (ffffffff813925c1)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - fs/io_uring.c:io_cancel_defer_files
```
```
In fs/ext4/mballoc.c (ffffffff8141d54c)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff8178f701)
Location: include/linux/list.h:389
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
In mm/compaction.c (ffffffff8128ebd8)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/io_uring.c (ffffffff8139a2cb)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
```
```
In fs/ext4/mballoc.c (ffffffff81423cbd)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff81772291)
Location: include/linux/list.h:389
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
In mm/compaction.c (ffffffff812cea98)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/io_uring.c (ffffffff813e9a31)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
```
```
In fs/ext4/mballoc.c (ffffffff814776c8)
Location: include/linux/list.h:389
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff817f8361)
Location: include/linux/list.h:389
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
In mm/compaction.c (ffffffff8132cbd8)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff814f9a21)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In io_uring/io_uring.c (ffffffff81e91fcc)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In drivers/char/virtio_console.c (ffffffff81936c71)
Location: include/linux/list.h:399
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
In mm/compaction.c (ffffffff813a31b8)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff81594241)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In io_uring/io_uring.c (ffffffff8178f37b)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In drivers/char/virtio_console.c (ffffffff81a96b21)
Location: include/linux/list.h:399
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
In mm/compaction.c (ffffffff813d6768)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff815cb211)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In io_uring/io_uring.c (ffffffff817d06b0)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In drivers/char/virtio_console.c (ffffffff81ae2331)
Location: include/linux/list.h:399
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
In mm/compaction.c (ffffffff8140043b)
Location: include/linux/list.h:480
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In io_uring/io_uring.c (ffffffff81813ed3)
Location: include/linux/list.h:480
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In drivers/char/virtio_console.c (ffffffff81b35721)
Location: include/linux/list.h:480
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
In mm/compaction.c (ffff8000102e8014)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffff80001049515c)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffff8000108b4424)
Location: include/linux/list.h:357
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
In mm/compaction.c (c050c05c)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (c0656c4c)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (c09ae2a4)
Location: include/linux/list.h:357
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
In mm/compaction.c (c0000000003a9fac)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (c0000000005be988)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (c00000000094c534)
Location: include/linux/list.h:357
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
In mm/compaction.c (ffffffe0001fd9f4)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffe000319dbe)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffe000565346)
Location: include/linux/list.h:357
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
In mm/compaction.c (ffffffff81249445)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813b6b7c)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff81686c81)
Location: include/linux/list.h:357
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
In mm/compaction.c (ffffffff8123c3f5)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813a760c)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/acpi/nfit/core.c (ffffffff815f7ea1)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
```
```
In drivers/char/virtio_console.c (ffffffff81664891)
Location: include/linux/list.h:357
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
In mm/compaction.c (ffffffff812471e5)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813b43dc)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff816b4fe1)
Location: include/linux/list.h:357
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
In mm/compaction.c (ffffffff81256a15)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In fs/ext4/mballoc.c (ffffffff813c8feb)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In drivers/char/virtio_console.c (ffffffff816cf7d1)
Location: include/linux/list.h:357
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
</details>
</li>
</ul>

## Differences
