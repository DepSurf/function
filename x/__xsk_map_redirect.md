# Function: <code>__xsk_map_redirect</code>

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
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811cb340)
Location: kernel/bpf/xskmap.c:124
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811cb340-ffffffff811cb3a1: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811dec50)
Location: kernel/bpf/xskmap.c:125
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811dec50-ffffffff811decb1: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f45b0)
Location: kernel/bpf/xskmap.c:123
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f45b0-ffffffff811f4611: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81201550)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81201550-ffffffff812015b1: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __xsk_map_redirect(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba8110)
Location: net/xdp/xsk.c:226
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81ba8110-ffffffff81ba8179: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __xsk_map_redirect(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7df0)
Location: net/xdp/xsk.c:270
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81bb7df0-ffffffff81bb7eae: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __xsk_map_redirect(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6fb0)
Location: net/xdp/xsk.c:285
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81ba6fb0-ffffffff81ba7090: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __xsk_map_redirect(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c74c30)
Location: net/xdp/xsk.c:285
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81c74c30-ffffffff81c74d10: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __xsk_map_redirect(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e18cd0)
Location: net/xdp/xsk.c:270
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81e18cd0-ffffffff81e18ddd: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __xsk_map_redirect(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81feff70)
Location: net/xdp/xsk.c:270
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81feff70-ffffffff81ff007d: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __xsk_map_redirect(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206c110)
Location: net/xdp/xsk.c:271
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8206c110-ffffffff8206c21d: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __xsk_map_redirect(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213fd10)
Location: net/xdp/xsk.c:373
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8213fd10-ffffffff8213fff9: __xsk_map_redirect (STB_GLOBAL)
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
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffff8000102894e8)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffff8000102894e8-ffff800010289568: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c04b8ec8)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
c04b8ec8-c04b8f24: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c000000000334b50)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
c000000000334b50-c000000000334bf8: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffe0001bd8ca)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffe0001bd8ca-ffffffe0001bd94a: __xsk_map_redirect (STB_GLOBAL)
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
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f9b70)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f9b70-ffffffff811f9bd1: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811ec8c0)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811ec8c0-ffffffff811ec921: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f7940)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f7940-ffffffff811f79a1: __xsk_map_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __xsk_map_redirect(struct bpf_map *map, struct xdp_buff *xdp, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81205ec0)
Location: kernel/bpf/xskmap.c:175
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81205ec0-ffffffff81205f21: __xsk_map_redirect (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bpf_map *map</code>
</li>
<li>
<b>Param reordered. </b>
<code>map, xdp, xs</code> ➡️ <code>xs, xdp</code>
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
