# Function: <code>local_cmpxchg</code>

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
In arch/x86/events/core.c (ffffffff8100566d)
Location: arch/x86/include/asm/local.h:123
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100e2fa)
Location: arch/x86/include/asm/local.h:123
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81010166)
Location: arch/x86/include/asm/local.h:123
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8127696a)
Location: arch/x86/include/asm/local.h:123
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff813727f4)
Location: arch/x86/include/asm/local.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In kernel/events/ring_buffer.c (ffffffff8137c437)
Location: arch/x86/include/asm/local.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81290a0d)
Location: arch/x86/include/asm/local.h:123
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
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
In arch/powerpc/perf/core-book3s.c (c0000000001279ac)
Location: arch/powerpc/include/asm/local.h:79
Inline: True
```
```
In kernel/trace/ring_buffer.c (c00000000029e004)
Location: arch/powerpc/include/asm/local.h:79
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (c000000000352148)
Location: arch/powerpc/include/asm/local.h:79
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_set_period
```
```
In kernel/events/ring_buffer.c (c000000000354848)
Location: arch/powerpc/include/asm/local.h:79
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
