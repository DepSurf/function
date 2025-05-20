# Function: <code>xsk_map_put</code>

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
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff812011dc)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81201510-ffffffff81201520: xsk_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ba9281)
Location: net/xdp/xskmap.c:20
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_delete_from_maps
```
**Symbols:**

```
ffffffff81ba93d0-ffffffff81ba93e0: xsk_map_put (STB_GLOBAL)
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
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffff80001028927c)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffff800010289468-ffff800010289494: xsk_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c04b8b34)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c04b8e80-c04b8e9c: xsk_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c0000000003347a0)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c000000000334ad0-c000000000334b04: xsk_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffe0001bd5d0)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffe0001bd858-ffffffe0001bd882: xsk_map_put (STB_GLOBAL)
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
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f97fc)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811f9b30-ffffffff811f9b40: xsk_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811ec54c)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811ec880-ffffffff811ec890: xsk_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f75cc)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811f7900-ffffffff811f7910: xsk_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xsk_map_put(struct xsk_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81205b4c)
Location: kernel/bpf/xskmap.c:27
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81205e80-ffffffff81205e90: xsk_map_put (STB_GLOBAL)
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
