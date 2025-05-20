# Function: <code>__cpu_map_lookup_elem</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811af6a8)
Location: kernel/bpf/cpumap.c:551
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:__xdp_map_lookup_elem
```
**Symbols:**

```
ffffffff811b02b0-ffffffff811b02d4: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ca1a8)
Location: kernel/bpf/cpumap.c:514
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:__xdp_map_lookup_elem
```
**Symbols:**

```
ffffffff811cad80-ffffffff811cada4: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ddac8)
Location: kernel/bpf/cpumap.c:516
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811de680-ffffffff811de6a4: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f3178)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f3fb0-ffffffff811f3fd4: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811fff18)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff81200d50-ffffffff81200d74: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812279d8)
Location: kernel/bpf/cpumap.c:509
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff812287b0-ffffffff812287d4: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8122e528)
Location: kernel/bpf/cpumap.c:608
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff8122f6a0-ffffffff8122f6c4: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8123341e)
Location: kernel/bpf/cpumap.c:565
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8126d071)
Location: kernel/bpf/cpumap.c:630
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812bbdfe)
Location: kernel/bpf/cpumap.c:633
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8131f1ce)
Location: kernel/bpf/cpumap.c:632
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8134f01e)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8137651e)
Location: kernel/bpf/cpumap.c:597
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
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
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffff800010287970)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffff8000102889a0-ffff8000102889ec: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c04b77f8)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
c04b86e8-c04b8714: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c000000000332a5c)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
c000000000333f10-c000000000333f48: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffe0001bc330)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffe0001bd0c8-ffffffe0001bd110: __cpu_map_lookup_elem (STB_GLOBAL)
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
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f8538)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f9370-ffffffff811f9394: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811eb288)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811ec0c0-ffffffff811ec0e4: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f6308)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f7140-ffffffff811f7164: __cpu_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81204878)
Location: kernel/bpf/cpumap.c:555
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff812056c0-ffffffff812056e4: __cpu_map_lookup_elem (STB_GLOBAL)
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
