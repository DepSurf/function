# Function: <code>bpf_prog_array_length</code>

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
int bpf_prog_array_length(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119e050)
Location: kernel/bpf/core.c:1461
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff8119e050-ffffffff8119e095: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2a9d)
Location: kernel/bpf/core.c:1559
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811b2780-ffffffff811b27c5: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c1619)
Location: kernel/bpf/core.c:1810
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811c12d0-ffffffff811c1315: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1d3e)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811d1a20-ffffffff811d1a59: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de2de)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811ddfa0-ffffffff811ddfd9: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fada4)
Location: kernel/bpf/core.c:1882
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811faa60-ffffffff811faa9a: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa094)
Location: kernel/bpf/core.c:1884
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811f9cb0-ffffffff811f9cea: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fb005)
Location: kernel/bpf/core.c:1980
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811fac20-ffffffff811fac59: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c725)
Location: kernel/bpf/core.c:1993
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff8122c330-ffffffff8122c369: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e3c9)
Location: kernel/bpf/core.c:2279
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff8126df60-ffffffff8126dfad: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c3a29)
Location: kernel/bpf/core.c:2273
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff812c3550-ffffffff812c359d: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea879)
Location: kernel/bpf/core.c:2290
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff812ea3a0-ffffffff812ea3ed: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308b89)
Location: kernel/bpf/core.c:2466
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff813086b0-ffffffff813086fd: bpf_prog_array_length (STB_GLOBAL)
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
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f4fc)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffff80001025efa8-ffff80001025f00c: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04928ec)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
c04924dc-c049252c: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000304498)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
c000000000303f80-c000000000303fe8: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d408)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffe00019d0fe-ffffffe00019d13e: bpf_prog_array_length (STB_GLOBAL)
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
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d68fe)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811d65c0-ffffffff811d65f9: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c96be)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811c9380-ffffffff811c93b9: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d46ce)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811d4390-ffffffff811d43c9: bpf_prog_array_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e29ee)
Location: kernel/bpf/core.c:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_info
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811e26b0-ffffffff811e26e9: bpf_prog_array_length (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog_array *array</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog_array *progs</code>
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
