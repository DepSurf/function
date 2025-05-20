# Function: <code>local_add_return</code>

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
In kernel/trace/ring_buffer.c (ffffffff811474cf)
Location: arch/x86/include/asm/local.h:105
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
```
```
In kernel/events/core.c (ffffffff81183144)
Location: arch/x86/include/asm/local.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff81151bb9)
Location: arch/x86/include/asm/local.h:105
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811950e4)
Location: arch/x86/include/asm/local.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff8115a40b)
Location: arch/x86/include/asm/local.h:105
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811a4b44)
Location: arch/x86/include/asm/local.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff8115d49e)
Location: arch/x86/include/asm/local.h:105
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811ac0f7)
Location: arch/x86/include/asm/local.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff8116a6ce)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811bfa88)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff811793a7)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811dfc85)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff81186a77)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811f00d5)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff81193c62)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff81207a17)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff8119f782)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff81214d87)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff811b6167)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff812412f4)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff811b3a8b)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff8124b8a0)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In net/core/net_namespace.c (ffffffff819f9430)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a35c9a)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In kernel/trace/ring_buffer.c (ffffffff811b45cc)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff8124f92e)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/mmap_lock.c (ffffffff8129b868)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In net/core/net_namespace.c (ffffffff819de87b)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81a1cded)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In kernel/trace/ring_buffer.c (ffffffff811de79c)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff8128a64e)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/mmap_lock.c (ffffffff812dc358)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In net/core/net_namespace.c (ffffffff81a8e65b)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81ad066d)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In kernel/trace/ring_buffer.c (ffffffff812153ae)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff812df0e1)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/mmap_lock.c (ffffffff8133c2c4)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In net/core/net_namespace.c (ffffffff81c04597)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81c4def0)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In kernel/trace/ring_buffer.c (ffffffff8125e9fe)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/memalloc.c (ffffffff8131b9b0)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff813472bf)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/mmap_lock.c (ffffffff813b3e04)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In net/core/net_namespace.c (ffffffff81db4067)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e02d3a)
Location: arch/x86/include/asm/local.h:106
Inline: True
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
In kernel/trace/ring_buffer.c (ffffffff81275bde)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/memalloc.c (ffffffff8134b3f0)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff813783c5)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/mmap_lock.c (ffffffff813e8754)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In net/core/net_namespace.c (ffffffff81e24717)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e752ba)
Location: arch/x86/include/asm/local.h:106
Inline: True
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
In kernel/trace/ring_buffer.c (ffffffff8129085e)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/memalloc.c (ffffffff81371db8)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free_rcu
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:unit_alloc
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff813a16c4)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/mmap_lock.c (ffffffff814133e4)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In net/core/net_namespace.c (ffffffff81ee2367)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81f34b5a)
Location: arch/x86/include/asm/local.h:106
Inline: True
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029e9e0)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (c000000000352334)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/ring_buffer.c (c000000000354964)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In block/genhd.c (c000000000793a50)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/trace/ring_buffer.c (ffffffff81197da2)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff8120d3d7)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff8118b552)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff812001a7)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff81195b72)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff8120b177)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In kernel/trace/ring_buffer.c (ffffffff811a3a02)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff81219f87)
Location: arch/x86/include/asm/local.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
</details>
</li>
</ul>

## Differences
