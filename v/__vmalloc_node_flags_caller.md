# Function: <code>__vmalloc_node_flags_caller</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81208670)
Location: mm/vmalloc.c:1831
Inline: False
Direct callers:
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff81208670-ffffffff812086ab: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81221770)
Location: mm/vmalloc.c:1823
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff81221770-ffffffff812217b2: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81243630)
Location: mm/vmalloc.c:1810
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff81243630-ffffffff81243679: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257d30)
Location: mm/vmalloc.c:1816
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff81257d30-ffffffff81257d79: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a7f0)
Location: mm/vmalloc.c:2564
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff8126a7f0-ffffffff8126a83c: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81279700)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff81279700-ffffffff8127974c: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff8000103102b0)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffff8000103102b0-ffff8000103103bc: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c66c)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
```
**Symbols:**

```
c052c66c-c052c6dc: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e1570)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
c0000000003e1570-c0000000003e15d8: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe00021863a)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffe00021863a-ffffffe000218690: __vmalloc_node_flags_caller (STB_GLOBAL)
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
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271d50)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff81271d50-ffffffff81271d9c: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263cc0)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff81263cc0-ffffffff81263d0c: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126faf0)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff8126faf0-ffffffff8126fb3c: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__vmalloc_node_flags_caller(long unsigned int size, int node, gfp_t flags, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f4e0)
Location: mm/vmalloc.c:2572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
```
**Symbols:**

```
ffffffff8127f4e0-ffffffff8127f52c: __vmalloc_node_flags_caller (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
