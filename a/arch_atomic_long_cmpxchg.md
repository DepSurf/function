# Function: <code>arch_atomic_long_cmpxchg</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea223)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d75c)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/events/core.c (ffffffff812875a0)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff813b87d3)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff813df743)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
```
```
In net/core/skbuff.c (ffffffff81a82bae)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81c750ac)
Location: include/linux/atomic/atomic-long.h:411
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
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8115fd70)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/events/core.c (ffffffff812dbd35)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff8143e09e)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In io_uring/io_uring.c (ffffffff816cd3cb)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
```
```
In lib/sbitmap.c (ffffffff81773928)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In net/core/skbuff.c (ffffffff81bf78c5)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/xdp/xdp_umem.c (ffffffff81e19250)
Location: include/linux/atomic/atomic-long.h:411
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
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81193110)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/events/core.c (ffffffff81344025)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff814ccaae)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/xdp/xdp_umem.c (ffffffff81ff04a6)
Location: include/linux/atomic/atomic-long.h:411
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
