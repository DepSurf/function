# Function: <code>__perf_event__output_id_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81178a00)
Location: kernel/events/core.c:5207
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_log_lost_samples
```
**Symbols:**

```
ffffffff81178a00-ffffffff81178ab4: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81189140)
Location: kernel/events/core.c:5524
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff81189140-ffffffff811891f4: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81198510)
Location: kernel/events/core.c:5622
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff81198510-ffffffff811985c4: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0210)
Location: kernel/events/core.c:5714
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff811a0210-ffffffff811a02c4: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3b40)
Location: kernel/events/core.c:5664
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff811b3b40-ffffffff811b3bf4: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3040)
Location: kernel/events/core.c:6025
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff811d3040-ffffffff811d3106: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e3330)
Location: kernel/events/core.c:6034
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff811e3330-ffffffff811e33f6: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa500)
Location: kernel/events/core.c:6112
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
```
**Symbols:**

```
ffffffff811fa500-ffffffff811fa5c6: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812075d0)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
ffffffff812075d0-ffffffff81207696: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812308d0)
Location: kernel/events/core.c:6611
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
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff812308d0-ffffffff81230996: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123a500)
Location: kernel/events/core.c:6689
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff8123a500-ffffffff8123a5c6: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ed30)
Location: kernel/events/core.c:6800
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff8123ed30-ffffffff8123edf6: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81279760)
Location: kernel/events/core.c:6924
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff81279760-ffffffff81279826: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cc910)
Location: kernel/events/core.c:6829
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff812cc910-ffffffff812cc9fb: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81334870)
Location: kernel/events/core.c:7086
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff81334870-ffffffff8133495b: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813655b0)
Location: kernel/events/core.c:7095
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff813655b0-ffffffff8136569e: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138e6d0)
Location: kernel/events/core.c:7168
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff8138e6d0-ffffffff8138e7be: __perf_event__output_id_sample (STB_LOCAL)
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
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010290ff0)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
ffff800010290ff0-ffff8000102910c4: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c101c)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
c04c101c-c04c1108: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033ece0)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
c00000000033ece0-c00000000033ee18: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c3bd6)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
ffffffe0001c3bd6-ffffffe0001c3caa: __perf_event__output_id_sample (STB_LOCAL)
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
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffbf0)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
ffffffff811ffbf0-ffffffff811ffcb6: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2940)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
ffffffff811f2940-ffffffff811f2a06: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd9c0)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
ffffffff811fd9c0-ffffffff811fda86: __perf_event__output_id_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __perf_event__output_id_sample(struct perf_output_handle *handle, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ca20)
Location: kernel/events/core.c:6228
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
```
**Symbols:**

```
ffffffff8120ca20-ffffffff8120cae6: __perf_event__output_id_sample (STB_LOCAL)
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
