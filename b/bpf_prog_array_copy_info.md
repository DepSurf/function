# Function: <code>bpf_prog_array_copy_info</code>

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
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2a70)
Location: kernel/bpf/core.c:1700
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811b2a70-ffffffff811b2b43: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c15f0)
Location: kernel/bpf/core.c:1954
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811c15f0-ffffffff811c16c3: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1d30)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811d1d30-ffffffff811d1dc8: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de2d0)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811de2d0-ffffffff811de368: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fad90)
Location: kernel/bpf/core.c:2025
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811fad90-ffffffff811fae32: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa080)
Location: kernel/bpf/core.c:2082
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811fa080-ffffffff811fa122: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811faff0)
Location: kernel/bpf/core.c:2178
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811faff0-ffffffff811fb090: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c710)
Location: kernel/bpf/core.c:2198
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff8122c710-ffffffff8122c7b0: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e3b0)
Location: kernel/bpf/core.c:2484
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff8126e3b0-ffffffff8126e480: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c3a10)
Location: kernel/bpf/core.c:2478
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff812c3a10-ffffffff812c3ae0: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea860)
Location: kernel/bpf/core.c:2495
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff812ea860-ffffffff812ea930: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308b70)
Location: kernel/bpf/core.c:2671
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff81308b70-ffffffff81308c40: bpf_prog_array_copy_info (STB_GLOBAL)
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
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f4d0)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffff80001025f4d0-ffff80001025f5b4: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04928d0)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
c04928d0-c04929a0: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000304480)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
c000000000304480-c000000000304574: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d3e2)
Location: kernel/bpf/core.c:1947
Inline: False
```
**Symbols:**

```
ffffffe00019d3e2-ffffffe00019d48e: bpf_prog_array_copy_info (STB_GLOBAL)
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
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d68f0)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811d68f0-ffffffff811d6988: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c96b0)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811c96b0-ffffffff811c9748: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d46c0)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811d46c0-ffffffff811d4758: bpf_prog_array_copy_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_prog_array_copy_info(struct bpf_prog_array *array, u32 *prog_ids, u32 request_cnt, u32 *prog_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e29e0)
Location: kernel/bpf/core.c:1947
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
**Symbols:**

```
ffffffff811e29e0-ffffffff811e2a78: bpf_prog_array_copy_info (STB_GLOBAL)
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
