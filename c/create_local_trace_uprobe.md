# Function: <code>create_local_trace_uprobe</code>

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
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1355
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811b0055-ffffffff811b0073: create_local_trace_uprobe.cold.23 (STB_LOCAL)
ffffffff811afdb0-ffffffff811aff07: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1357
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811be673-ffffffff811be68e: create_local_trace_uprobe.cold.28 (STB_LOCAL)
ffffffff811be420-ffffffff811be597: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1350
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811ce21d-ffffffff811ce238: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811ce020-ffffffff811ce18e: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1556
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811da83b-ffffffff811da856: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811da680-ffffffff811da7e2: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1568
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811f7324-ffffffff811f733f: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811f7120-ffffffff811f72a1: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1580
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff81be651b-ffffffff81be6536: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811f5cd0-ffffffff811f5e51: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1585
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff81bd8203-ffffffff81bd821e: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811f6bc0-ffffffff811f6d41: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1586
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff81cb78ad-ffffffff81cb78c8: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff81228190-ffffffff81228319: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1576
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff81e689b2-ffffffff81e689cd: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff81268290-ffffffff81268424: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812ba460)
Location: kernel/trace/trace_uprobe.c:1582
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff812ba460-ffffffff812ba60f: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812dda70)
Location: kernel/trace/trace_uprobe.c:1583
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff812dda70-ffffffff812ddc1f: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812fbb60)
Location: kernel/trace/trace_uprobe.c:1579
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff812fbb60-ffffffff812fbd0f: create_local_trace_uprobe (STB_GLOBAL)
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
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffff80001025ad80)
Location: kernel/trace/trace_uprobe.c:1556
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffff80001025ad80-ffff80001025aefc: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048de74)
Location: kernel/trace/trace_uprobe.c:1556
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
c048de74-c048dfec: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fe8f0)
Location: kernel/trace/trace_uprobe.c:1556
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
c0000000002fe8f0-c0000000002fead4: create_local_trace_uprobe (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1556
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811d2e5b-ffffffff811d2e76: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811d2ca0-ffffffff811d2e02: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1556
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811c5c2b-ffffffff811c5c46: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811c5a70-ffffffff811c5bd2: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1556
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811d0c2b-ffffffff811d0c46: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811d0a70-ffffffff811d0bd2: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct trace_event_call *create_local_trace_uprobe(char *name, long unsigned int offs, long unsigned int ref_ctr_offset, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1556
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
```
**Symbols:**

```
ffffffff811deeeb-ffffffff811def06: create_local_trace_uprobe.cold (STB_LOCAL)
ffffffff811ded30-ffffffff811dee92: create_local_trace_uprobe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int ref_ctr_offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, offs, is_return</code> ➡️ <code>name, offs, ref_ctr_offset, is_return</code>
</li>
</ul>
</details>
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
