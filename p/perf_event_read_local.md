# Function: <code>perf_event_read_local</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 perf_event_read_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117faa0)
Location: kernel/events/core.c:3297
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
```
**Symbols:**

```
ffffffff8117faa0-ffffffff8117fbda: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 perf_event_read_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81191800)
Location: kernel/events/core.c:3498
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
```
**Symbols:**

```
ffffffff81191800-ffffffff81191944: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 perf_event_read_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0fb0)
Location: kernel/events/core.c:3586
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
```
**Symbols:**

```
ffffffff811a0fb0-ffffffff811a10f4: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a8930)
Location: kernel/events/core.c:3675
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811a8930-ffffffff811a89cf: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bc0c0)
Location: kernel/events/core.c:3580
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811bc0c0-ffffffff811bc205: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dc280)
Location: kernel/events/core.c:3913
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811dc280-ffffffff811dc3ba: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ec650)
Location: kernel/events/core.c:3908
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811ec650-ffffffff811ec7bf: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204050)
Location: kernel/events/core.c:3928
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81204050-ffffffff812041b5: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210c40)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81210c40-ffffffff81210da5: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123cba0)
Location: kernel/events/core.c:4248
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8123cba0-ffffffff8123cd03: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81246dd0)
Location: kernel/events/core.c:4325
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81246dd0-ffffffff81246f39: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124ac70)
Location: kernel/events/core.c:4405
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8124ac70-ffffffff8124ade7: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81284280)
Location: kernel/events/core.c:4513
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81284280-ffffffff812843dd: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d8660)
Location: kernel/events/core.c:4411
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff812d8660-ffffffff812d87d9: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81340bd0)
Location: kernel/events/core.c:4531
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81340bd0-ffffffff81340d51: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81371b70)
Location: kernel/events/core.c:4531
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81371b70-ffffffff81371ce1: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139aec0)
Location: kernel/events/core.c:4566
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8139aec0-ffffffff8139b052: perf_event_read_local (STB_GLOBAL)
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
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029b130)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffff80001029b130-ffff80001029b2b8: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04ca590)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
c04ca590-c04ca708: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034ae10)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
c00000000034ae10-c00000000034b00c: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cd77c)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffe0001cd77c-ffffffe0001cd874: perf_event_read_local (STB_GLOBAL)
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
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209290)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81209290-ffffffff812093f5: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fc060)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811fc060-ffffffff811fc1a8: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207030)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81207030-ffffffff81207195: perf_event_read_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event *event, u64 *value, u64 *enabled, u64 *running);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81215db0)
Location: kernel/events/core.c:4025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_prog_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81215db0-ffffffff81215f15: perf_event_read_local (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 *value</code>
</li>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 *enabled</code>
</li>
<li>
<b>Param added. </b>
<code>u64 *running</code>
</li>
</ul>
</details>
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
