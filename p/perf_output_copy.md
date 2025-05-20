# Function: <code>perf_output_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811854ef)
Location: kernel/events/ring_buffer.c:206
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
Direct callers:
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_log_lost_samples
```
**Symbols:**

```
ffffffff811855a0-ffffffff81185622: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811971d0)
Location: kernel/events/ring_buffer.c:253
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811971d0-ffffffff81197252: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811a6bc0)
Location: kernel/events/ring_buffer.c:253
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811a6bc0-ffffffff811a6c42: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811ae360)
Location: kernel/events/ring_buffer.c:253
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811ae360-ffffffff811ae3e2: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c1fd0)
Location: kernel/events/ring_buffer.c:253
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811c1fd0-ffffffff811c2052: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e2390)
Location: kernel/events/ring_buffer.c:254
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811e2390-ffffffff811e241f: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f2800)
Location: kernel/events/ring_buffer.c:254
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff811f2800-ffffffff811f288f: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120a4d0)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8120a4d0-ffffffff8120a55c: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812177b0)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff812177b0-ffffffff8121783c: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124398e)
Location: kernel/events/ring_buffer.c:285
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81243170-ffffffff812431f2: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124e01e)
Location: kernel/events/ring_buffer.c:287
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8124d810-ffffffff8124d892: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81252960)
Location: kernel/events/ring_buffer.c:287
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81252150-ffffffff812521d1: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8128e220)
Location: kernel/events/ring_buffer.c:287
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8128d9f0-ffffffff8128da71: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e3080)
Location: kernel/events/ring_buffer.c:287
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
Direct callers:
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff812e27f0-ffffffff812e287d: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134b745)
Location: kernel/events/ring_buffer.c:290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
Direct callers:
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
```
**Symbols:**

```
ffffffff8134b5d0-ffffffff8134b5ec: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137c795)
Location: kernel/events/ring_buffer.c:290
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
Direct callers:
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
```
**Symbols:**

```
ffffffff8137c620-ffffffff8137c63c: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a59d5)
Location: kernel/events/ring_buffer.c:291
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
Direct callers:
  - kernel/events/core.c:perf_report_aux_output_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
```
**Symbols:**

```
ffffffff813a5860-ffffffff813a587c: perf_output_copy (STB_GLOBAL)
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
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a20b0)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffff8000102a20b0-ffff8000102a2174: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c04d1bdc)
Location: kernel/events/ring_buffer.c:285
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
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
c04d1bdc-c04d1c94: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c000000000353f80)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
c000000000353f80-c000000000354090: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d0ef8)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffe0001d0ef8-ffffffe0001d0f8e: perf_output_copy (STB_GLOBAL)
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
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120fe00)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8120fe00-ffffffff8120fe8c: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81202b90)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81202b90-ffffffff81202c1c: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120dba0)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8120dba0-ffffffff8120dc2c: perf_output_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int perf_output_copy(struct perf_output_handle *handle, const void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121ca50)
Location: kernel/events/ring_buffer.c:285
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_bpf_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_log_throttle
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_log_lost_samples
  - kernel/events/core.c:perf_event_aux_event
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:__perf_event__output_id_sample
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff8121ca50-ffffffff8121cadc: perf_output_copy (STB_GLOBAL)
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
