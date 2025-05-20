# Function: <code>__percpu_add_return_case_32</code>

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
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/kernel/debug-monitors.c (ffff800010086314)
Location: arch/arm64/include/asm/percpu.h:115
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:disable_debug_monitors
  - arch/arm64/kernel/debug-monitors.c:disable_debug_monitors
  - arch/arm64/kernel/debug-monitors.c:enable_debug_monitors
  - arch/arm64/kernel/debug-monitors.c:enable_debug_monitors
```
```
In kernel/taskstats.c (ffff80001020d350)
Location: arch/arm64/include/asm/percpu.h:115
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In kernel/trace/trace.c (ffff8000102210f8)
Location: arch/arm64/include/asm/percpu.h:115
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
```
In kernel/trace/bpf_trace.c (ffff80001024db3c)
Location: arch/arm64/include/asm/percpu.h:115
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In drivers/nvdimm/region_devs.c (ffff800010957a50)
Location: arch/arm64/include/asm/percpu.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
</details>
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
