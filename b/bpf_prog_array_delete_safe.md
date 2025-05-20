# Function: <code>bpf_prog_array_delete_safe</code>

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
void bpf_prog_array_delete_safe(struct bpf_prog_array *progs, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119e150)
Location: kernel/bpf/core.c:1500
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff8119e150-ffffffff8119e189: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *progs, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b28b0)
Location: kernel/bpf/core.c:1626
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811b28b0-ffffffff811b28e9: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c1420)
Location: kernel/bpf/core.c:1878
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811c1420-ffffffff811c1459: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1b70)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811d1b70-ffffffff811d1ba3: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de110)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811de110-ffffffff811de143: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fabd0)
Location: kernel/bpf/core.c:1949
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811fabd0-ffffffff811fac03: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9e20)
Location: kernel/bpf/core.c:1951
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811f9e20-ffffffff811f9e53: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fad90)
Location: kernel/bpf/core.c:2047
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811fad90-ffffffff811fadc3: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c4a0)
Location: kernel/bpf/core.c:2060
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff8122c4a0-ffffffff8122c4d3: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e0f0)
Location: kernel/bpf/core.c:2346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff8126e0f0-ffffffff8126e12f: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c3710)
Location: kernel/bpf/core.c:2340
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff812c3710-ffffffff812c374f: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea560)
Location: kernel/bpf/core.c:2357
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff812ea560-ffffffff812ea59f: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308870)
Location: kernel/bpf/core.c:2533
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff81308870-ffffffff813088af: bpf_prog_array_delete_safe (STB_GLOBAL)
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
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f2c0)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffff80001025f2c0-ffff80001025f318: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04926f0)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
c04926f0-c049273c: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003041d0)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
c0000000003041d0-c000000000304228: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d26a)
Location: kernel/bpf/core.c:1871
Inline: False
```
**Symbols:**

```
ffffffe00019d26a-ffffffe00019d2b8: bpf_prog_array_delete_safe (STB_GLOBAL)
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
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6730)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811d6730-ffffffff811d6763: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c94f0)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811c94f0-ffffffff811c9523: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4500)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811d4500-ffffffff811d4533: bpf_prog_array_delete_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_prog_array_delete_safe(struct bpf_prog_array *array, struct bpf_prog *old_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2820)
Location: kernel/bpf/core.c:1871
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
```
**Symbols:**

```
ffffffff811e2820-ffffffff811e2853: bpf_prog_array_delete_safe (STB_GLOBAL)
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
