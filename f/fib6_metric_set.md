# Function: <code>fib6_metric_set</code>

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
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197b3d0)
Location: net/ipv6/ip6_fib.c:632
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff8197b3d0-ffffffff8197b432: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b10b0)
Location: net/ipv6/ip6_fib.c:666
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819b10b0-ffffffff819b1112: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1f430)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a1f430-ffffffff81a1f492: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a560b0)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a560b0-ffffffff81a56112: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4e32a)
Location: net/ipv6/ip6_fib.c:710
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b4ea20-ffffffff81b4ea82: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5cfb8)
Location: net/ipv6/ip6_fib.c:711
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b5d6a0-ffffffff81b5d702: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4b1d3)
Location: net/ipv6/ip6_fib.c:712
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b4b900-ffffffff81b4b962: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c12513)
Location: net/ipv6/ip6_fib.c:714
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81c12c40-ffffffff81c12cce: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dadbec)
Location: net/ipv6/ip6_fib.c:715
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81dae180-ffffffff81dae226: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7d618)
Location: net/ipv6/ip6_fib.c:714
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81f7dca0-ffffffff81f7dd46: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdd825)
Location: net/ipv6/ip6_fib.c:714
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81fddeb0-ffffffff81fddf56: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820aaf90)
Location: net/ipv6/ip6_fib.c:714
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff820aaf90-ffffffff820ab06a: fib6_metric_set (STB_GLOBAL)
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
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1ac58)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffff800010d1ac58-ffff800010d1acd4: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e20004)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c0e20004-c0e20078: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e48fa0)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c000000000e48fa0-c000000000e49074: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085eed6)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffe00085eed6-ffffffe00085ef48: fib6_metric_set (STB_GLOBAL)
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
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f5740)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819f5740-ffffffff819f57a2: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b2500)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819b2500-ffffffff819b2562: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a601c0)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a601c0-ffffffff81a60222: fib6_metric_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info *f6i, int metric, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6c680)
Location: net/ipv6/ip6_fib.c:659
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a6c680-ffffffff81a6c6e2: fib6_metric_set (STB_GLOBAL)
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
