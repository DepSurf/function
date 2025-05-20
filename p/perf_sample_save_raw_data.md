# Function: <code>perf_sample_save_raw_data</code>

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
In arch/x86/events/amd/ibs.c (ffffffff8100f198)
Location: include/linux/perf_event.h:1226
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff812c92d0)
Location: include/linux/perf_event.h:1226
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff8136e69c)
Location: include/linux/perf_event.h:1226
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
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
In arch/x86/events/amd/ibs.c (ffffffff810148d8)
Location: include/linux/perf_event.h:1242
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff812e6310)
Location: include/linux/perf_event.h:1242
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff8139778c)
Location: include/linux/perf_event.h:1242
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
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
