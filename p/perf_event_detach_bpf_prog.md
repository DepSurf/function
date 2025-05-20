# Function: <code>perf_event_detach_bpf_prog</code>

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
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81190aa0)
Location: kernel/trace/bpf_trace.c:814
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81190aa0-ffffffff81190b60: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5c20)
Location: kernel/trace/bpf_trace.c:1006
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811a5c20-ffffffff811a5ce5: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b3f30)
Location: kernel/trace/bpf_trace.c:1042
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811b3f30-ffffffff811b3ff5: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2f50)
Location: kernel/trace/bpf_trace.c:1212
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811c2f50-ffffffff811c3015: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ce700)
Location: kernel/trace/bpf_trace.c:1236
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811ce700-ffffffff811ce7c5: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811eac10)
Location: kernel/trace/bpf_trace.c:1731
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811eac10-ffffffff811eacd5: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8db0)
Location: kernel/trace/bpf_trace.c:1985
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811e8db0-ffffffff811e8e75: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9ca0)
Location: kernel/trace/bpf_trace.c:1681
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811e9ca0-ffffffff811e9d65: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121aad0)
Location: kernel/trace/bpf_trace.c:1765
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff8121aad0-ffffffff8121ab97: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81259790)
Location: kernel/trace/bpf_trace.c:1946
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff81259790-ffffffff81259870: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a99d0)
Location: kernel/trace/bpf_trace.c:2163
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff812a99d0-ffffffff812a9aaa: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cc240)
Location: kernel/trace/bpf_trace.c:2172
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff812cc240-ffffffff812cc31a: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e96c0)
Location: kernel/trace/bpf_trace.c:2277
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff812e96c0-ffffffff812e979a: perf_event_detach_bpf_prog (STB_GLOBAL)
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
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024e860)
Location: kernel/trace/bpf_trace.c:1236
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffff80001024e860-ffff80001024e920: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0481848)
Location: kernel/trace/bpf_trace.c:1236
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
c0481848-c0481914: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002eab30)
Location: kernel/trace/bpf_trace.c:1236
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
c0000000002eab30-c0000000002eac54: perf_event_detach_bpf_prog (STB_GLOBAL)
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
Location: include/linux/trace_events.h:500
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
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c6d20)
Location: kernel/trace/bpf_trace.c:1236
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811c6d20-ffffffff811c6de5: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b9b00)
Location: kernel/trace/bpf_trace.c:1236
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811b9b00-ffffffff811b9bc5: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4af0)
Location: kernel/trace/bpf_trace.c:1236
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811c4af0-ffffffff811c4bb5: perf_event_detach_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_detach_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d2d50)
Location: kernel/trace/bpf_trace.c:1236
Inline: False
Direct callers:
  - kernel/events/core.c:_free_event
```
**Symbols:**

```
ffffffff811d2d50-ffffffff811d2e15: perf_event_detach_bpf_prog (STB_GLOBAL)
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
