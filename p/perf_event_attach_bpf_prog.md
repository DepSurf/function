# Function: <code>perf_event_attach_bpf_prog</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811909c0)
Location: kernel/trace/bpf_trace.c:781
Inline: False
Direct callers:
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811909c0-ffffffff81190a95: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5b10)
Location: kernel/trace/bpf_trace.c:964
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811a5b10-ffffffff811a5c1d: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b3e20)
Location: kernel/trace/bpf_trace.c:1000
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811b3e20-ffffffff811b3f2d: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2e30)
Location: kernel/trace/bpf_trace.c:1170
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811c2e30-ffffffff811c2f41: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ce5e0)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811ce5e0-ffffffff811ce6f1: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811eaaf0)
Location: kernel/trace/bpf_trace.c:1689
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
```
**Symbols:**

```
ffffffff811eaaf0-ffffffff811eac01: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8c90)
Location: kernel/trace/bpf_trace.c:1943
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
```
**Symbols:**

```
ffffffff811e8c90-ffffffff811e8da1: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9b80)
Location: kernel/trace/bpf_trace.c:1639
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
```
**Symbols:**

```
ffffffff811e9b80-ffffffff811e9c91: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121a9a0)
Location: kernel/trace/bpf_trace.c:1721
Inline: False
```
**Symbols:**

```
ffffffff8121a9a0-ffffffff8121aac2: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81259650)
Location: kernel/trace/bpf_trace.c:1902
Inline: False
```
**Symbols:**

```
ffffffff81259650-ffffffff8125978d: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a9880)
Location: kernel/trace/bpf_trace.c:2119
Inline: False
```
**Symbols:**

```
ffffffff812a9880-ffffffff812a99b3: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cc0f0)
Location: kernel/trace/bpf_trace.c:2128
Inline: False
```
**Symbols:**

```
ffffffff812cc0f0-ffffffff812cc223: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog, u64 bpf_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e9570)
Location: kernel/trace/bpf_trace.c:2233
Inline: False
```
**Symbols:**

```
ffffffff812e9570-ffffffff812e96a3: perf_event_attach_bpf_prog (STB_GLOBAL)
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
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024e750)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffff80001024e750-ffff80001024e85c: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0481738)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c0481738-c0481848: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002ea9b0)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
c0000000002ea9b0-c0000000002eab28: perf_event_attach_bpf_prog (STB_GLOBAL)
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
In kernel/events/core.c (0)
Location: include/linux/trace_events.h:495
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
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c6c00)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811c6c00-ffffffff811c6d11: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b99e0)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811b99e0-ffffffff811b9af1: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c49d0)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811c49d0-ffffffff811c4ae1: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event *event, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d2c30)
Location: kernel/trace/bpf_trace.c:1194
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811d2c30-ffffffff811d2d41: perf_event_attach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 bpf_cookie</code>
</li>
</ul>
</details>
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
