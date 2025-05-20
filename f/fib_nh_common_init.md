# Function: <code>fib_nh_common_init</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c78f0)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff819c78f0-ffffffff819c79ee: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819fe4a0)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff819fe4a0-ffffffff819fe59e: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct net *net, struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aecd60)
Location: net/ipv4/fib_semantics.c:573
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81aecd60-ffffffff81aece65: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct net *net, struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af9970)
Location: net/ipv4/fib_semantics.c:573
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81af9970-ffffffff81af9a75: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct net *net, struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae5070)
Location: net/ipv4/fib_semantics.c:574
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81ae5070-ffffffff81ae516d: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct net *net, struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba4d40)
Location: net/ipv4/fib_semantics.c:579
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81ba4d40-ffffffff81ba4e3d: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_nh_common_init(struct net *net, struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81d376d0)
Location: net/ipv4/fib_semantics.c:581
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81d376d0-ffffffff81d377eb: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_nh_common_init(struct net *net, struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81efff10)
Location: net/ipv4/fib_semantics.c:583
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81efff10-ffffffff81f0002b: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_nh_common_init(struct net *net, struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f5f990)
Location: net/ipv4/fib_semantics.c:583
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81f5f990-ffffffff81f5faab: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_nh_common_init(struct net *net, struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff82025f60)
Location: net/ipv4/fib_semantics.c:584
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff82025f60-ffffffff8202607b: fib_nh_common_init (STB_GLOBAL)
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
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb65a8)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffff800010cb65a8-ffff800010cb66e4: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc2120)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
c0dc2120-c0dc2250: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dce820)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
c000000000dce820-c000000000dce998: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080dd66)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffe00080dd66-ffffffe00080de20: fib_nh_common_init (STB_GLOBAL)
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
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199e240)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff8199e240-ffffffff8199e33e: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81957d00)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81957d00-ffffffff81957dfe: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a08ae0)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a08ae0-ffffffff81a08bde: fib_nh_common_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fib_nh_common_init(struct fib_nh_common *nhc, struct nlattr *encap, u16 encap_type, void *cfg, gfp_t gfp_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a13240)
Location: net/ipv4/fib_semantics.c:566
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_init
```
**Symbols:**

```
ffffffff81a13240-ffffffff81a1333e: fib_nh_common_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>nhc, encap, encap_type, cfg, gfp_flags, extack</code> ➡️ <code>net, nhc, encap, encap_type, cfg, gfp_flags, extack</code>
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
