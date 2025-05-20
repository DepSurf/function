# Function: <code>addrconf_prefix_rcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817d0890)
Location: net/ipv6/addrconf.c:2323
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff817d0890-ffffffff817d10c7: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183e1d0)
Location: net/ipv6/addrconf.c:2476
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff8183e1d0-ffffffff8183e8eb: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186fde0)
Location: net/ipv6/addrconf.c:2491
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff8186fde0-ffffffff818704fb: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81894b40)
Location: net/ipv6/addrconf.c:2546
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81894b40-ffffffff818952ad: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81916010)
Location: net/ipv6/addrconf.c:2571
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81916010-ffffffff8191674b: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2600
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff8196f473-ffffffff8196f484: addrconf_prefix_rcv.cold.80 (STB_LOCAL)
ffffffff8196d710-ffffffff8196ddee: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2616
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819a5023-ffffffff819a5034: addrconf_prefix_rcv.cold.82 (STB_LOCAL)
ffffffff819a3270-ffffffff819a3965: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2656
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a11463-ffffffff81a11497: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81a0f560-ffffffff81a0fc92: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a480d2-ffffffff81a480e3: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81a462a0-ffffffff81a469d1: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2634
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b3ebb8-ffffffff81b3ebc9: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81b3d310-ffffffff81b3d922: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2661
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81c32c62-ffffffff81c32c73: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81b4bf70-ffffffff81b4c49a: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2663
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81c24f88-ffffffff81c24f99: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81b39b60-ffffffff81b3a096: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2683
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81d3fa99-ffffffff81d3faaa: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81c00310-ffffffff81c00840: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2687
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81f0c40e-ffffffff81f0c41f: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81d99e40-ffffffff81d9a42d: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f68c20)
Location: net/ipv6/addrconf.c:2687
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81f68c20-ffffffff81f69216: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc8cf0)
Location: net/ipv6/addrconf.c:2692
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81fc8cf0-ffffffff81fc9281: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff82096470)
Location: net/ipv6/addrconf.c:2721
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff82096470-ffffffff82096a2c: addrconf_prefix_rcv (STB_GLOBAL)
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
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d08f00)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffff800010d08f00-ffff800010d0957c: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0f4c0)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c0e0f4c0-c0e0fb50: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e33490)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c000000000e33490-c000000000e33ce0: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe000850c6e)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffe000850c6e-ffffffe0008512e4: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819e7762-ffffffff819e7773: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff819e5930-ffffffff819e6061: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819a4522-ffffffff819a4533: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff819a26f0-ffffffff819a2e21: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a521e2-ffffffff81a521f3: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81a503b0-ffffffff81a50ae1: addrconf_prefix_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void addrconf_prefix_rcv(struct net_device *dev, u8 *opt, int len, bool sllao);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:2658
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a5e132-ffffffff81a5e143: addrconf_prefix_rcv.cold (STB_LOCAL)
ffffffff81a5c3d0-ffffffff81a5ca1b: addrconf_prefix_rcv (STB_GLOBAL)
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
