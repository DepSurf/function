# Function: <code>bpf_get_raw_tracepoint</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b4170)
Location: kernel/trace/bpf_trace.c:1116
Inline: False
```
**Symbols:**

```
ffffffff811b4170-ffffffff811b4277: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3190)
Location: kernel/trace/bpf_trace.c:1285
Inline: False
```
**Symbols:**

```
ffffffff811c3190-ffffffff811c328c: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ce940)
Location: kernel/trace/bpf_trace.c:1309
Inline: False
```
**Symbols:**

```
ffffffff811ce940-ffffffff811cea3c: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811eae60)
Location: kernel/trace/bpf_trace.c:1804
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff811eae60-ffffffff811eaf5c: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9000)
Location: kernel/trace/bpf_trace.c:2058
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff811e9000-ffffffff811e90fc: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9ef0)
Location: kernel/trace/bpf_trace.c:1754
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff811e9ef0-ffffffff811e9fec: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121ad20)
Location: kernel/trace/bpf_trace.c:1838
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
ffffffff8121ad20-ffffffff8121ae1c: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81259a10)
Location: kernel/trace/bpf_trace.c:2019
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff81259a10-ffffffff81259b21: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a9c70)
Location: kernel/trace/bpf_trace.c:2236
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff812a9c70-ffffffff812a9d81: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cc4e0)
Location: kernel/trace/bpf_trace.c:2245
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff812cc4e0-ffffffff812cc5f1: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e9960)
Location: kernel/trace/bpf_trace.c:2350
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
```
**Symbols:**

```
ffffffff812e9960-ffffffff812e9a71: bpf_get_raw_tracepoint (STB_GLOBAL)
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
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024ebb8)
Location: kernel/trace/bpf_trace.c:1309
Inline: False
```
**Symbols:**

```
ffff80001024ebb8-ffff80001024ecfc: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0481b40)
Location: kernel/trace/bpf_trace.c:1309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
c0481b40-c0481c54: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002eae60)
Location: kernel/trace/bpf_trace.c:1309
Inline: False
```
**Symbols:**

```
c0000000002eae60-c0000000002eb2d4: bpf_get_raw_tracepoint (STB_GLOBAL)
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
Location: include/linux/trace_events.h:515
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
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c6f60)
Location: kernel/trace/bpf_trace.c:1309
Inline: False
```
**Symbols:**

```
ffffffff811c6f60-ffffffff811c705c: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b9d40)
Location: kernel/trace/bpf_trace.c:1309
Inline: False
```
**Symbols:**

```
ffffffff811b9d40-ffffffff811b9e3c: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4d30)
Location: kernel/trace/bpf_trace.c:1309
Inline: False
```
**Symbols:**

```
ffffffff811c4d30-ffffffff811c4e2c: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_raw_event_map *bpf_get_raw_tracepoint(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d2f90)
Location: kernel/trace/bpf_trace.c:1309
Inline: False
```
**Symbols:**

```
ffffffff811d2f90-ffffffff811d308c: bpf_get_raw_tracepoint (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
