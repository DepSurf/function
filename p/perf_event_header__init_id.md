# Function: <code>perf_event_header__init_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81178c34)
Location: kernel/events/core.c:5199
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
ffffffff81182e00-ffffffff81182e15: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811894e8)
Location: kernel/events/core.c:5516
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
ffffffff81194d40-ffffffff81194d55: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811988b8)
Location: kernel/events/core.c:5614
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
ffffffff811a47a0-ffffffff811a47b5: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0694)
Location: kernel/events/core.c:5706
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
ffffffff811abde0-ffffffff811abdf6: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3fff)
Location: kernel/events/core.c:5656
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
ffffffff811bf760-ffffffff811bf776: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d4bf6)
Location: kernel/events/core.c:6017
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
ffffffff811dfa20-ffffffff811dfa39: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e5416)
Location: kernel/events/core.c:6026
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
ffffffff811efe70-ffffffff811efe89: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fca56)
Location: kernel/events/core.c:6104
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
ffffffff81207680-ffffffff81207699: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209bd6)
Location: kernel/events/core.c:6220
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
ffffffff812149f0-ffffffff81214a09: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81237d8b)
Location: kernel/events/core.c:6603
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
ffffffff81240f90-ffffffff81240fa5: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241b5b)
Location: kernel/events/core.c:6681
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
ffffffff8124b520-ffffffff8124b535: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245606)
Location: kernel/events/core.c:6792
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
ffffffff8124f5b0-ffffffff8124f5c5: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812805b6)
Location: kernel/events/core.c:6916
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
ffffffff8128a2d0-ffffffff8128a2e5: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e0bd9)
Location: kernel/events/core.c:6821
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
ffffffff812ded20-ffffffff812ded4e: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81349079)
Location: kernel/events/core.c:7078
Inline: True
Inline callers:
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81346f30-ffffffff81346f69: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136d799)
Location: kernel/events/core.c:7085
Inline: True
Inline callers:
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81378030-ffffffff8137807d: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81396869)
Location: kernel/events/core.c:7158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff813a1310-ffffffff813a135d: perf_event_header__init_id (STB_GLOBAL)
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
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010292bac)
Location: kernel/events/core.c:6220
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
ffff80001029eca8-ffff80001029eccc: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c1558)
Location: kernel/events/core.c:6220
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
c04ce69c-c04ce6bc: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034103c)
Location: kernel/events/core.c:6220
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
  - arch/powerpc/perf/imc-pmu.c:dump_trace_imc_data
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
c00000000034fcb0-c00000000034fccc: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c55ee)
Location: kernel/events/core.c:6220
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
ffffffe0001ce460-ffffffe0001ce488: perf_event_header__init_id (STB_GLOBAL)
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
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812021f6)
Location: kernel/events/core.c:6220
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
ffffffff8120d040-ffffffff8120d059: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f4f46)
Location: kernel/events/core.c:6220
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
ffffffff811ffe10-ffffffff811ffe29: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fffc6)
Location: kernel/events/core.c:6220
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
ffffffff8120ade0-ffffffff8120adf9: perf_event_header__init_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void perf_event_header__init_id(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f056)
Location: kernel/events/core.c:6220
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
ffffffff81219bf0-ffffffff81219c09: perf_event_header__init_id (STB_GLOBAL)
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
