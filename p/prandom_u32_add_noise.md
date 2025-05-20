# Function: <code>prandom_u32_add_noise</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff82fd59d6)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In kernel/time/timer.c (ffffffff811420ea)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
```
```
In mm/slab_common.c (ffffffff81288e5a)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In net/core/dev.c (ffffffff81a0963c)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
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
In arch/x86/mm/kaslr.c (ffffffff831e0472)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In kernel/time/timer.c (ffffffff811432da)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
```
```
In mm/slab_common.c (ffffffff8128e51a)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In net/core/dev.c (ffffffff819effac)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
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
In arch/x86/mm/kaslr.c (ffffffff832c3b0b)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In kernel/time/timer.c (ffffffff8116685a)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - kernel/time/timer.c:update_process_times
```
```
In mm/slab_common.c (ffffffff812ce45a)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In net/core/dev.c (ffffffff81aa13dc)
Location: include/linux/prandom.h:59
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
