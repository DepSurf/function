# Function: <code>destroy_local_trace_kprobe</code>

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
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a8bf0)
Location: kernel/trace/trace_kprobe.c:1505
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811a8bf0-ffffffff811a8c2c: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b6fb0)
Location: kernel/trace/trace_kprobe.c:1421
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811b6fb0-ffffffff811b6ff1: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:1431
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811c617d-ffffffff811c6190: destroy_local_trace_kprobe.cold (STB_LOCAL)
ffffffff811c6030-ffffffff811c6060: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d1d80)
Location: kernel/trace/trace_kprobe.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811d1d80-ffffffff811d1dc4: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ee770)
Location: kernel/trace/trace_kprobe.c:1823
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811ee770-ffffffff811ee7d5: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ec9c0)
Location: kernel/trace/trace_kprobe.c:1844
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811ec9c0-ffffffff811eca25: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ed720)
Location: kernel/trace/trace_kprobe.c:1847
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811ed720-ffffffff811ed785: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8121e790)
Location: kernel/trace/trace_kprobe.c:1845
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff8121e790-ffffffff8121e7f5: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8125ddf0)
Location: kernel/trace/trace_kprobe.c:1839
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff8125ddf0-ffffffff8125de6d: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ae8b0)
Location: kernel/trace/trace_kprobe.c:1791
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff812ae8b0-ffffffff812ae92d: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812d0dc0)
Location: kernel/trace/trace_kprobe.c:1748
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff812d0dc0-ffffffff812d0e45: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ee8c0)
Location: kernel/trace/trace_kprobe.c:1831
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff812ee8c0-ffffffff812ee945: destroy_local_trace_kprobe (STB_GLOBAL)
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
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff800010251f48)
Location: kernel/trace/trace_kprobe.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffff800010251f48-ffff800010251fa8: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0484e38)
Location: kernel/trace/trace_kprobe.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
c0484e38-c0484ecc: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002f0420)
Location: kernel/trace/trace_kprobe.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
c0000000002f0420-c0000000002f04a8: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ca3a0)
Location: kernel/trace/trace_kprobe.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811ca3a0-ffffffff811ca3e4: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811bd170)
Location: kernel/trace/trace_kprobe.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811bd170-ffffffff811bd1b4: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c8170)
Location: kernel/trace/trace_kprobe.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811c8170-ffffffff811c81b4: destroy_local_trace_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call *event_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d63d0)
Location: kernel/trace/trace_kprobe.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_kprobe_destroy
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
```
**Symbols:**

```
ffffffff811d63d0-ffffffff811d6414: destroy_local_trace_kprobe (STB_GLOBAL)
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
