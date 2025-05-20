# Function: <code>bpf_prog_array_copy</code>

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
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119e190)
Location: kernel/bpf/core.c:1512
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff8119e190-ffffffff8119e2dd: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b28f0)
Location: kernel/bpf/core.c:1638
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811b28f0-ffffffff811b2a64: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c1460)
Location: kernel/bpf/core.c:1890
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811c1460-ffffffff811c15e2: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1bb0)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811d1bb0-ffffffff811d1d2d: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de150)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811de150-ffffffff811de2cd: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fac10)
Location: kernel/bpf/core.c:1961
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811fac10-ffffffff811fad8c: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9f00)
Location: kernel/bpf/core.c:2018
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811f9f00-ffffffff811fa07c: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fae70)
Location: kernel/bpf/core.c:2114
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811fae70-ffffffff811fafec: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, u64 bpf_cookie, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c580)
Location: kernel/bpf/core.c:2127
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff8122c580-ffffffff8122c709: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, u64 bpf_cookie, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e210)
Location: kernel/bpf/core.c:2413
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff8126e210-ffffffff8126e3a8: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, u64 bpf_cookie, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c3860)
Location: kernel/bpf/core.c:2407
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff812c3860-ffffffff812c39f8: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, u64 bpf_cookie, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea6b0)
Location: kernel/bpf/core.c:2424
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff812ea6b0-ffffffff812ea848: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, u64 bpf_cookie, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff813089c0)
Location: kernel/bpf/core.c:2600
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff813089c0-ffffffff81308b58: bpf_prog_array_copy (STB_GLOBAL)
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
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f318)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffff80001025f318-ffff80001025f4cc: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c049273c)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
c049273c-c04928d0: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000304230)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
c000000000304230-c000000000304480: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d2b8)
Location: kernel/bpf/core.c:1883
Inline: False
```
**Symbols:**

```
ffffffe00019d2b8-ffffffe00019d3e2: bpf_prog_array_copy (STB_GLOBAL)
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
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6770)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811d6770-ffffffff811d68ed: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c9530)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811c9530-ffffffff811c96ad: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4540)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811d4540-ffffffff811d46bd: bpf_prog_array_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array *old_array, struct bpf_prog *exclude_prog, struct bpf_prog *include_prog, struct bpf_prog_array **new_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2860)
Location: kernel/bpf/core.c:1883
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff811e2860-ffffffff811e29dd: bpf_prog_array_copy (STB_GLOBAL)
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
<li>
<b>Param reordered. </b>
<code>old_array, exclude_prog, include_prog, new_array</code> ➡️ <code>old_array, exclude_prog, include_prog, bpf_cookie, new_array</code>
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
