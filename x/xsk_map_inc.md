# Function: <code>xsk_map_inc</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff8120116a)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff812014f0-ffffffff81201510: xsk_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ba920e)
Location: net/xdp/xskmap.c:14
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_delete_from_maps
```
**Symbols:**

```
ffffffff81ba93b0-ffffffff81ba93c2: xsk_map_inc (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffff8000102891d4)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffff800010289430-ffff800010289468: xsk_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c04b8a78)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c04b8e58-c04b8e80: xsk_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c0000000003345d0)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c000000000334a60-c000000000334ac4: xsk_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffe0001bd50e)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffe0001bd818-ffffffe0001bd858: xsk_map_inc (STB_GLOBAL)
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
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f978a)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811f9b10-ffffffff811f9b30: xsk_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811ec4da)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811ec860-ffffffff811ec880: xsk_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f755a)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811f78e0-ffffffff811f7900: xsk_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xsk_map_inc(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81205ada)
Location: kernel/bpf/xskmap.c:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81205e60-ffffffff81205e80: xsk_map_inc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
