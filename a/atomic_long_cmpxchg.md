# Function: <code>atomic_long_cmpxchg</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204f40)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff813099a6)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (ffffffff81330ee1)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In net/core/skbuff.c (ffffffff818e6ce3)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a75dc1)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/events/core.c (ffffffff81211b30)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff8131ca16)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (ffffffff81344f7f)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In net/core/skbuff.c (ffffffff819190c3)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81aacb24)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/events/core.c (ffffffff8123da60)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff8135669e)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff81385801)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In net/core/skbuff.c (ffffffff819ecd2e)
Location: include/asm-generic/atomic-long.h:411
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ba856e)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111c845)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
```
```
In kernel/events/core.c (ffffffff81247e20)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff81363043)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff81396835)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_buffer_account_pin
```
```
In net/core/skbuff.c (ffffffff819ec9ee)
Location: include/asm-generic/atomic-long.h:411
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81bb82d4)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111d432)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/events/core.c (ffffffff8124bce0)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff81369ae3)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff8139183a)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
```
```
In net/core/skbuff.c (ffffffff819d2ece)
Location: include/asm-generic/atomic-long.h:411
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7492)
Location: include/asm-generic/atomic-long.h:411
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/ucount.c (ffffffff810ea223)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d75c)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/events/core.c (ffffffff812875a0)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff813b87d3)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff813df743)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
```
```
In net/core/skbuff.c (ffffffff81a82bae)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81c750ac)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/ucount.c (ffffffff81104e94)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8115fd70)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/events/core.c (ffffffff812dbd35)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff8143e09e)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In io_uring/io_uring.c (ffffffff816cd3cb)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
```
```
In lib/sbitmap.c (ffffffff81773928)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In net/core/skbuff.c (ffffffff81bf78c5)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/xdp/xdp_umem.c (ffffffff81e19250)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/ucount.c (ffffffff8112a7cf)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81193110)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/events/core.c (ffffffff81344025)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff814ccaae)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/xdp/xdp_umem.c (ffffffff81ff04a6)
Location: include/linux/atomic/atomic-instrumented.h:1738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/ucount.c (ffffffff8113784f)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a4980)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/events/core.c (ffffffff813750b5)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
```
```
In fs/nsfs.c (ffffffff81502cee)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/xdp/xdp_umem.c (ffffffff8206c654)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/ucount.c (ffffffff81142a5f)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b4470)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/events/core.c (ffffffff8139e3e5)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
```
```
In fs/nsfs.c (ffffffff81537918)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/xdp/xdp_umem.c (ffffffff82140452)
Location: include/linux/atomic/atomic-instrumented.h:4319
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/trace/ring_buffer.c (ffff80001021abe4)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffff8000102a0790)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_set_period
  - kernel/events/core.c:free_event
```
```
In kernel/events/ring_buffer.c (ffff8000102a2730)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In fs/nsfs.c (ffff8000103d4668)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (ffff8000104010bc)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In drivers/perf/arm-cci.c (ffff800010b912b4)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm_pmu.c (ffff800010b94fdc)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b965fc)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98e4c)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_update
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a69c)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c09c)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_update
```
```
In net/core/skbuff.c (ffff800010bb2d64)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (ffff800010d813b0)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/trace/ring_buffer.c (c0459718)
Location: include/asm-generic/atomic-long.h:904
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (c04cb564)
Location: include/asm-generic/atomic-long.h:904
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In kernel/events/ring_buffer.c (c04d22c8)
Location: include/asm-generic/atomic-long.h:904
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In fs/nsfs.c (c05ae5a8)
Location: include/asm-generic/atomic-long.h:904
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (c05d1e9c)
Location: include/asm-generic/atomic-long.h:904
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In net/core/skbuff.c (c0ccf8f0)
Location: include/asm-generic/atomic-long.h:904
Inline: True
```
```
In net/xdp/xdp_umem.c (c0e7b95c)
Location: include/asm-generic/atomic-long.h:904
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/events/core.c (c00000000034c1f8)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (c0000000004d72f0)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (c000000000509518)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In net/core/skbuff.c (c000000000c89c08)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (c000000000ec1320)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/riscv/kernel/perf_event.c (ffffffe0000b95fa)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_pmu_read
```
```
In kernel/trace/ring_buffer.c (ffffffe0001795d6)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffe0001c5450)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:free_event
```
```
In kernel/events/ring_buffer.c (ffffffe0001d13a8)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In fs/nsfs.c (ffffffe00028eb30)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (ffffffe0002b06c0)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In net/core/skbuff.c (ffffffe000743840)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad84a)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/events/core.c (ffffffff8120a180)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff81314ff6)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (ffffffff8133d55f)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In net/core/skbuff.c (ffffffff818b90c3)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a4beb4)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/events/core.c (ffffffff811fcf70)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff81305be6)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (ffffffff8132e21f)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In net/core/skbuff.c (ffffffff81873013)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a08aa4)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/events/core.c (ffffffff81207f20)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff81312de6)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (ffffffff8133b02f)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In net/core/skbuff.c (ffffffff8190a0c3)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d64)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/events/core.c (ffffffff81216cc0)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff81324621)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In fs/io_uring.c (ffffffff8134e1df)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In net/core/skbuff.c (ffffffff8192b1c3)
Location: include/asm-generic/atomic-long.h:410
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ac4184)
Location: include/asm-generic/atomic-long.h:410
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
