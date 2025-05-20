# Function: <code>fib_nhc_update_mtu</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819ca430)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff819ca430-ffffffff819ca491: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a01020)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81a01020-ffffffff81a01081: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af00a0)
Location: net/ipv4/fib_semantics.c:1892
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81af00a0-ffffffff81af0101: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afcff0)
Location: net/ipv4/fib_semantics.c:1891
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81afcff0-ffffffff81afd051: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae8810)
Location: net/ipv4/fib_semantics.c:1894
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81ae8810-ffffffff81ae8871: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1939
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81d3cfa4-ffffffff81d3cfc1: fib_nhc_update_mtu.cold (STB_LOCAL)
ffffffff81ba87c0-ffffffff81ba8851: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1926
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81f097f0-ffffffff81f0980d: fib_nhc_update_mtu.cold (STB_LOCAL)
ffffffff81d3b1f0-ffffffff81d3b28d: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1932
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff820b10cb-ffffffff820b10e8: fib_nhc_update_mtu.cold (STB_LOCAL)
ffffffff81f03b90-ffffffff81f03c2d: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1932
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff82132356-ffffffff82132373: fib_nhc_update_mtu.cold (STB_LOCAL)
ffffffff81f63570-ffffffff81f6360d: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1940
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff82213d14-ffffffff82213d31: fib_nhc_update_mtu.cold (STB_LOCAL)
ffffffff82029b40-ffffffff82029bdd: fib_nhc_update_mtu (STB_GLOBAL)
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
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb9670)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffff800010cb9670-ffff800010cb9704: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc4e08)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
c0dc4e08-c0dc4eb0: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dd2510)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
c000000000dd2510-c000000000dd2598: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00081029e)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffe00081029e-ffffffe000810304: fib_nhc_update_mtu (STB_GLOBAL)
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
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819a0dc0)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff819a0dc0-ffffffff819a0e21: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8195a880)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff8195a880-ffffffff8195a8e1: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a0b660)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81a0b660-ffffffff81a0b6c1: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib_nhc_update_mtu(struct fib_nh_common *nhc, u32 new, u32 orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a15e50)
Location: net/ipv4/fib_semantics.c:1874
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81a15e50-ffffffff81a15eb1: fib_nhc_update_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
