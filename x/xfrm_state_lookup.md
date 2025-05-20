# Function: <code>xfrm_state_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff817b9470)
Location: net/xfrm/xfrm_state.c:1392
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff817b9470-ffffffff817b94e2: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81825640)
Location: net/xfrm/xfrm_state.c:1393
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81825640-ffffffff818256b2: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818590d0)
Location: net/xfrm/xfrm_state.c:1422
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81857000-ffffffff81857018: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff8187c087)
Location: net/xfrm/xfrm_state.c:1577
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff8187b8d0-ffffffff8187b8e8: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818fc93d)
Location: net/xfrm/xfrm_state.c:1593
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff818fc860-ffffffff818fc878: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff8195385f)
Location: net/xfrm/xfrm_state.c:1594
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819530d0-ffffffff819530e8: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819879a5)
Location: net/xfrm/xfrm_state.c:1628
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81986eb0-ffffffff81986ec8: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819f1780)
Location: net/xfrm/xfrm_state.c:1726
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819f0cc0-ffffffff819f0cd8: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a28650)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a27b90-ffffffff81a27ba8: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b1ac3d)
Location: net/xfrm/xfrm_state.c:1731
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b19fc0-ffffffff81b19ff3: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b293f2)
Location: net/xfrm/xfrm_state.c:1765
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b283d0-ffffffff81b28414: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b17032)
Location: net/xfrm/xfrm_state.c:1764
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b15fc0-ffffffff81b16004: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81bdb3e2)
Location: net/xfrm/xfrm_state.c:1808
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81bd9b70-ffffffff81bd9bb4: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81d72169)
Location: net/xfrm/xfrm_state.c:1810
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81d70b60-ffffffff81d70be1: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f3dd7b)
Location: net/xfrm/xfrm_state.c:1964
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81f3c500-ffffffff81f3c581: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f9d6b5)
Location: net/xfrm/xfrm_state.c:1961
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81f9be50-ffffffff81f9bed1: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff8206aa15)
Location: net/xfrm/xfrm_state.c:1961
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state
```
**Symbols:**

```
ffffffff820691b0-ffffffff82069231: xfrm_state_lookup (STB_GLOBAL)
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
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffff800010ce7d48)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffff800010ce4530-ffff800010ce4594: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c0deefd4)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
c0dee4c4-c0dee4f4: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c000000000e09db8)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
c000000000e08fd0-c000000000e09000: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffe000835576)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffe000833cb4-ffffffe000833d06: xfrm_state_lookup (STB_GLOBAL)
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
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819c7ce0)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819c7220-ffffffff819c7238: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81984ad0)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81984010-ffffffff81984028: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a32760)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a31ca0-ffffffff81a31cb8: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state *xfrm_state_lookup(struct net *net, u32 mark, const xfrm_address_t *daddr, __be32 spi, u8 proto, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a3e087)
Location: net/xfrm/xfrm_state.c:1728
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a3d560-ffffffff81a3d5c0: xfrm_state_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
