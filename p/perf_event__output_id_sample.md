# Function: <code>perf_event__output_id_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81178c9a)
Location: kernel/events/core.c:5231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_log_lost_samples
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
```
**Symbols:**

```
ffffffff81182e20-ffffffff81182e3b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81189521)
Location: kernel/events/core.c:5548
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81194d60-ffffffff81194d7b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811988f1)
Location: kernel/events/core.c:5646
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811a47c0-ffffffff811a47db: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a06d9)
Location: kernel/events/core.c:5738
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811abe00-ffffffff811abe1c: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b4044)
Location: kernel/events/core.c:5688
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811bf780-ffffffff811bf79c: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d4c29)
Location: kernel/events/core.c:6049
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811dfa40-ffffffff811dfa5b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e5449)
Location: kernel/events/core.c:6058
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811efe90-ffffffff811efeab: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fca89)
Location: kernel/events/core.c:6136
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff812076a0-ffffffff812076bb: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209c09)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81214a10-ffffffff81214a2b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81237dc2)
Location: kernel/events/core.c:6635
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81240fb0-ffffffff81240fcb: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241b9a)
Location: kernel/events/core.c:6713
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8124b540-ffffffff8124b55b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245645)
Location: kernel/events/core.c:6824
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8124f5d0-ffffffff8124f5eb: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812805f5)
Location: kernel/events/core.c:6948
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8128a2f0-ffffffff8128a30b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e0c32)
Location: kernel/events/core.c:6853
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff812ded50-ffffffff812ded88: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813490d2)
Location: kernel/events/core.c:7110
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81346f80-ffffffff81346fb8: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136d7f2)
Location: kernel/events/core.c:7119
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81378090-ffffffff813780c8: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813968c2)
Location: kernel/events/core.c:7192
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff813a1370-ffffffff813a13a8: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010292be0)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffff80001029ecd0-ffff80001029ecfc: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c1584)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
c04ce6bc-c04ce6e4: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000341094)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
c00000000034fcd0-c00000000034fcf0: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5624)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffe0001ce488-ffffffe0001ce4b2: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202229)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8120d060-ffffffff8120d07b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f4f79)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811ffe30-ffffffff811ffe4b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffff9)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8120ae00-ffffffff8120ae1b: perf_event__output_id_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void perf_event__output_id_sample(struct perf_event *event, struct perf_output_handle *handle, struct perf_sample_data *sample);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f089)
Location: kernel/events/core.c:6252
Inline: True
Inline callers:
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
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81219c10-ffffffff81219c2b: perf_event__output_id_sample (STB_GLOBAL)
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
