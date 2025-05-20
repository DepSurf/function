# Function: <code>local_try_cmpxchg</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100ad6c)
Location: arch/x86/include/asm/local.h:128
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff81013a43)
Location: arch/x86/include/asm/local.h:128
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81015947)
Location: arch/x86/include/asm/local.h:128
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff81291599)
Location: arch/x86/include/asm/local.h:128
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
```
```
In kernel/events/core.c (ffffffff8139bb72)
Location: arch/x86/include/asm/local.h:128
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff813a56a9)
Location: arch/x86/include/asm/local.h:128
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
