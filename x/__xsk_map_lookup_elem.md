# Function: <code>__xsk_map_lookup_elem</code>

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
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811cb310)
Location: kernel/bpf/xskmap.c:112
Inline: False
Direct callers:
  - net/core/filter.c:__xdp_map_lookup_elem
```
**Symbols:**

```
ffffffff811cb310-ffffffff811cb334: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811dec20)
Location: kernel/bpf/xskmap.c:113
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811dec20-ffffffff811dec44: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f41c8)
Location: kernel/bpf/xskmap.c:111
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f4580-ffffffff811f45a4: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81200f68)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff81201520-ffffffff81201544: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29a3b)
Location: include/net/xdp_sock.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
```
In net/xdp/xskmap.c (ffffffff81ba8ec8)
Location: include/net/xdp_sock.h:84
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a39b)
Location: include/net/xdp_sock.h:83
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
```
In net/xdp/xskmap.c (ffffffff81bb8728)
Location: include/net/xdp_sock.h:83
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_lookup_elem
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
In net/xdp/xskmap.c (ffffffff81ba795e)
Location: net/xdp/xskmap.c:127
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
  - net/xdp/xskmap.c:xsk_map_lookup_elem
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
In net/xdp/xskmap.c (ffffffff81c755e1)
Location: net/xdp/xskmap.c:131
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
  - net/xdp/xskmap.c:xsk_map_lookup_elem
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
In net/xdp/xskmap.c (ffffffff81e197fe)
Location: net/xdp/xskmap.c:133
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
  - net/xdp/xskmap.c:xsk_map_lookup_elem
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
In net/xdp/xskmap.c (ffffffff81ff0b6e)
Location: net/xdp/xskmap.c:133
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
  - net/xdp/xskmap.c:xsk_map_lookup_elem
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
In net/xdp/xskmap.c (ffffffff8206ccde)
Location: net/xdp/xskmap.c:141
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
  - net/xdp/xskmap.c:xsk_map_lookup_elem
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
In net/xdp/xskmap.c (ffffffff82140b7e)
Location: net/xdp/xskmap.c:141
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
  - net/xdp/xskmap.c:xsk_map_lookup_elem
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
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffff800010288cd0)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffff800010289498-ffff8000102894e4: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c04b88f8)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
c04b8e9c-c04b8ec8: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c00000000033420c)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
c000000000334b10-c000000000334b48: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffe0001bd318)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffe0001bd882-ffffffe0001bd8ca: __xsk_map_lookup_elem (STB_GLOBAL)
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
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f9588)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f9b40-ffffffff811f9b64: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811ec2d8)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811ec890-ffffffff811ec8b4: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f7358)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f7910-ffffffff811f7934: __xsk_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct xdp_sock *__xsk_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff812058d8)
Location: kernel/bpf/xskmap.c:163
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff81205e90-ffffffff81205eb4: __xsk_map_lookup_elem (STB_GLOBAL)
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
