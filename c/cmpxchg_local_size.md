# Function: <code>cmpxchg_local_size</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100641a)
Location: include/asm-generic/atomic-instrumented.h:405
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009afe)
Location: include/asm-generic/atomic-instrumented.h:405
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100aa04)
Location: include/asm-generic/atomic-instrumented.h:405
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100b106)
Location: include/asm-generic/atomic-instrumented.h:405
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8117b753)
Location: include/asm-generic/atomic-instrumented.h:405
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811dcb70)
Location: include/asm-generic/atomic-instrumented.h:405
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_swevent_overflow
```
```
In kernel/events/ring_buffer.c (ffffffff811e28c4)
Location: include/asm-generic/atomic-instrumented.h:405
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In drivers/iommu/intel-iommu.c (ffffffff81671e64)
Location: include/asm-generic/atomic-instrumented.h:405
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
</details>
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
