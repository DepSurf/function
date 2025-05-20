# Function: <code>perf_output_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811856a0)
Location: kernel/events/ring_buffer.c:218
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_log_lost_samples
```
**Symbols:**

```
ffffffff811856a0-ffffffff811856b0: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81197940)
Location: kernel/events/ring_buffer.c:265
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81197940-ffffffff81197950: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811a7330)
Location: kernel/events/ring_buffer.c:265
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811a7330-ffffffff811a7340: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811aeaf0)
Location: kernel/events/ring_buffer.c:265
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811aeaf0-ffffffff811aeb00: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c2760)
Location: kernel/events/ring_buffer.c:265
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811c2760-ffffffff811c2770: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e2aa0)
Location: kernel/events/ring_buffer.c:266
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811e2aa0-ffffffff811e2ab0: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f2f10)
Location: kernel/events/ring_buffer.c:266
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811f2f10-ffffffff811f2f20: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120ac00)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8120ac00-ffffffff8120ac10: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81217ee0)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81217ee0-ffffffff81217ef0: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81243880)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81243880-ffffffff812438fb: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124df00)
Location: kernel/events/ring_buffer.c:299
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8124df00-ffffffff8124df8c: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81252840)
Location: kernel/events/ring_buffer.c:299
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81252840-ffffffff812528cc: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8128e100)
Location: kernel/events/ring_buffer.c:299
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8128e100-ffffffff8128e18c: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e2fd0)
Location: kernel/events/ring_buffer.c:299
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff812e2fd0-ffffffff812e2feb: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134b680)
Location: kernel/events/ring_buffer.c:302
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8134b680-ffffffff8134b69b: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137c6d0)
Location: kernel/events/ring_buffer.c:302
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8137c6d0-ffffffff8137c6eb: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a5910)
Location: kernel/events/ring_buffer.c:303
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff813a5910-ffffffff813a592b: perf_output_end (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a29a0)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffff8000102a29a0-ffff8000102a29cc: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c04d2548)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
c04d2548-c04d2564: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c000000000354bc0)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - arch/powerpc/perf/imc-pmu.c:dump_trace_imc_data
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
c000000000354bc0-c000000000354bf0: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d1542)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffe0001d1542-ffffffe0001d156c: perf_output_end (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81210530)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81210530-ffffffff81210540: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812032c0)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff812032c0-ffffffff812032d0: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120e2d0)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8120e2d0-ffffffff8120e2e0: perf_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_output_end(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121d1d0)
Location: kernel/events/ring_buffer.c:297
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8121d1d0-ffffffff8121d1e5: perf_output_end (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
