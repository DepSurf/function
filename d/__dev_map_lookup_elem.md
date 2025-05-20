# Function: <code>__dev_map_lookup_elem</code>

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
struct net_device *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811aeff8)
Location: kernel/bpf/devmap.c:249
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:__xdp_map_lookup_elem
```
**Symbols:**

```
ffffffff811af670-ffffffff811af69c: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811c9778)
Location: kernel/bpf/devmap.c:301
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:__xdp_map_lookup_elem
```
**Symbols:**

```
ffffffff811c9fd0-ffffffff811c9ff4: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811dd078)
Location: kernel/bpf/devmap.c:302
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811dd8e0-ffffffff811dd904: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f26c8)
Location: kernel/bpf/devmap.c:283
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f2f40-ffffffff811f2f64: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811fee98)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811ffce0-ffffffff811ffd04: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81226518)
Location: kernel/bpf/devmap.c:409
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff81227690-ffffffff812276b4: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122d108)
Location: kernel/bpf/devmap.c:395
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff8122e1e0-ffffffff8122e204: __dev_map_lookup_elem (STB_GLOBAL)
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
In kernel/bpf/devmap.c (ffffffff81231f9e)
Location: kernel/bpf/devmap.c:388
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_redirect
  - kernel/bpf/devmap.c:dev_map_lookup_elem
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
In kernel/bpf/devmap.c (ffffffff8126b157)
Location: kernel/bpf/devmap.c:428
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_redirect
  - kernel/bpf/devmap.c:dev_map_lookup_elem
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
In kernel/bpf/devmap.c (ffffffff812b9d8b)
Location: kernel/bpf/devmap.c:429
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_redirect
  - kernel/bpf/devmap.c:dev_map_lookup_elem
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
In kernel/bpf/devmap.c (ffffffff8131d00b)
Location: kernel/bpf/devmap.c:429
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_redirect
  - kernel/bpf/devmap.c:dev_map_lookup_elem
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
In kernel/bpf/devmap.c (ffffffff8134cd8b)
Location: kernel/bpf/devmap.c:426
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_redirect
  - kernel/bpf/devmap.c:dev_map_lookup_elem
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
In kernel/bpf/devmap.c (ffffffff813742bb)
Location: kernel/bpf/devmap.c:435
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_redirect
  - kernel/bpf/devmap.c:dev_map_lookup_elem
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
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff8000102863e8)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffff800010287628-ffff800010287674: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b6654)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
c04b75c4-c04b75f0: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c00000000033106c)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
c000000000332750-c000000000332788: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bb230)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffe0001bc0fe-ffffffe0001bc146: __dev_map_lookup_elem (STB_GLOBAL)
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
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f74b8)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f8300-ffffffff811f8324: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ea208)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811eb050-ffffffff811eb074: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f5288)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f60d0-ffffffff811f60f4: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812037b8)
Location: kernel/bpf/devmap.c:421
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_lookup_elem
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff81204640-ffffffff81204664: __dev_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct net_device *</code> ➡️ <code>struct bpf_dtab_netdev *</code>
</li>
</ul>
</details>
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
