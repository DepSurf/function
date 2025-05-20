# Function: <code>sort_r</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81520370)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff81520370-ffffffff815205aa: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_func_t swap_func, const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81583520)
Location: lib/sort.c:199
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff81583520-ffffffff81583762: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_func_t swap_func, const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815a03a0)
Location: lib/sort.c:199
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff815a03a0-ffffffff815a05e2: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_func_t swap_func, const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815a7190)
Location: lib/sort.c:199
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff815a7190-ffffffff815a73d6: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_func_t swap_func, const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff816100d0)
Location: lib/sort.c:199
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff816100d0-ffffffff81610316: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_r_func_t swap_func, const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff816dc480)
Location: lib/sort.c:210
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/syscall.c:map_create
  - mm/slub.c:slab_debug_trace_open
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff816dc480-ffffffff816dc712: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_r_func_t swap_func, const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff817cc190)
Location: lib/sort.c:210
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/btf.c:btf_parse_field_offs
  - mm/slub.c:slab_debug_trace_open
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff817cc190-ffffffff817cc422: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_r_func_t swap_func, const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8180a5d0)
Location: lib/sort.c:210
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/btf.c:btf_parse_fields
  - mm/slub.c:slab_debug_trace_open
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff8180a5d0-ffffffff8180a860: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_r_func_t swap_func, const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81850db0)
Location: lib/sort.c:210
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/btf.c:btf_parse_fields
  - mm/slub.c:slab_debug_trace_open
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff81850db0-ffffffff81851040: sort_r (STB_GLOBAL)
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
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffff800011440d68)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
  - lib/sort.c:sort
```
**Symbols:**

```
ffff8000106298a0-ffff800010629a84: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (c07d0b38)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
c07d0b38-c07d0d48: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (c0000000007cb250)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
c0000000007cb250-c0000000007cb504: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffe00045a4f6)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffe00045a4f6-ffffffe00045a676: sort_r (STB_GLOBAL)
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
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81518950)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff81518950-ffffffff81518b8a: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81508c50)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff81508c50-ffffffff81508e8a: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815149e0)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff815149e0-ffffffff81514c1a: sort_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sort_r(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *, const void *), void (*swap_func)(void *, void *, int), const void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8152e150)
Location: lib/sort.c:204
Inline: False
Direct callers:
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff8152e150-ffffffff8152e38a: sort_r (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*cmp_func)(const void *, const void *, const void *)</code> ➡️ <code>cmp_r_func_t cmp_func</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*swap_func)(void *, void *, int)</code> ➡️ <code>swap_func_t swap_func</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>swap_func_t swap_func</code> ➡️ <code>swap_r_func_t swap_func</code>
</li>
</ul>
</details>
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
