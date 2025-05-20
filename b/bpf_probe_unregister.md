# Function: <code>bpf_probe_unregister</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5f10)
Location: kernel/trace/bpf_trace.c:1170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffffffff811a5f10-ffffffff811a5f4d: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b42e0)
Location: kernel/trace/bpf_trace.c:1210
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffffffff811b42e0-ffffffff811b42f5: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c32f0)
Location: kernel/trace/bpf_trace.c:1382
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffffffff811c32f0-ffffffff811c3305: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ceaa0)
Location: kernel/trace/bpf_trace.c:1406
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffffffff811ceaa0-ffffffff811ceab5: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811eafc0)
Location: kernel/trace/bpf_trace.c:1900
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_release
```
**Symbols:**

```
ffffffff811eafc0-ffffffff811eafd5: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9160)
Location: kernel/trace/bpf_trace.c:2156
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_release
```
**Symbols:**

```
ffffffff811e9160-ffffffff811e9175: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ea050)
Location: kernel/trace/bpf_trace.c:1853
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_release
```
**Symbols:**

```
ffffffff811ea050-ffffffff811ea065: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121ae80)
Location: kernel/trace/bpf_trace.c:1937
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_release
```
**Symbols:**

```
ffffffff8121ae80-ffffffff8121ae95: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81259bd0)
Location: kernel/trace/bpf_trace.c:2118
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_release
```
**Symbols:**

```
ffffffff81259bd0-ffffffff81259bef: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a9e60)
Location: kernel/trace/bpf_trace.c:2341
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_release
```
**Symbols:**

```
ffffffff812a9e60-ffffffff812a9e7f: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cc6d0)
Location: kernel/trace/bpf_trace.c:2350
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_release
```
**Symbols:**

```
ffffffff812cc6d0-ffffffff812cc6ef: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e9b50)
Location: kernel/trace/bpf_trace.c:2455
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_release
```
**Symbols:**

```
ffffffff812e9b50-ffffffff812e9b6f: bpf_probe_unregister (STB_GLOBAL)
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
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024ed70)
Location: kernel/trace/bpf_trace.c:1406
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffff80001024ed70-ffff80001024ed8c: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0481cc4)
Location: kernel/trace/bpf_trace.c:1406
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
c0481cc4-c0481ce0: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002eb3a0)
Location: kernel/trace/bpf_trace.c:1406
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
c0000000002eb3a0-c0000000002eb3d8: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/trace_events.h:511
Inline: True
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
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c70c0)
Location: kernel/trace/bpf_trace.c:1406
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffffffff811c70c0-ffffffff811c70d5: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b9ea0)
Location: kernel/trace/bpf_trace.c:1406
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffffffff811b9ea0-ffffffff811b9eb5: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4e90)
Location: kernel/trace/bpf_trace.c:1406
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffffffff811c4e90-ffffffff811c4ea5: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map *btp, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d30f0)
Location: kernel/trace/bpf_trace.c:1406
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
```
**Symbols:**

```
ffffffff811d30f0-ffffffff811d3105: bpf_probe_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
