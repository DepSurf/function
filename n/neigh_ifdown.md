# Function: <code>neigh_ifdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81727ae0)
Location: net/core/neighbour.c:253
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81727ae0-ffffffff81727bbf: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817915f0)
Location: net/core/neighbour.c:253
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff817915f0-ffffffff817916cf: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817beec0)
Location: net/core/neighbour.c:254
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff817beec0-ffffffff817bef9f: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817dced0)
Location: net/core/neighbour.c:290
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff817dced0-ffffffff817dcfaf: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81858760)
Location: net/core/neighbour.c:290
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81858760-ffffffff81858842: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818a3bd0)
Location: net/core/neighbour.c:293
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff818a3bd0-ffffffff818a3cc9: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c7120)
Location: net/core/neighbour.c:370
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff818c70c0-ffffffff818c70d4: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff819132a0)
Location: net/core/neighbour.c:370
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81913240-ffffffff81913254: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81945900)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff819458a0-ffffffff819458b4: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a15882)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81a15910-ffffffff81a15924: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a15b72)
Location: net/core/neighbour.c:369
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81a15c00-ffffffff81a15c14: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff819fc6e2)
Location: net/core/neighbour.c:373
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff819fc770-ffffffff819fc784: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81aae711)
Location: net/core/neighbour.c:373
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81aae7b0-ffffffff81aae7c4: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81c2743a)
Location: net/core/neighbour.c:416
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81c274e0-ffffffff81c274fe: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd9f9c)
Location: net/core/neighbour.c:454
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81dda060-ffffffff81dda07e: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e4acfc)
Location: net/core/neighbour.c:454
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81e4adc0-ffffffff81e4adde: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f09a1c)
Location: net/core/neighbour.c:462
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81f09ae0-ffffffff81f09afe: neigh_ifdown (STB_GLOBAL)
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
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be48bc)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffff800010be4838-ffff800010be4874: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cff550)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
c0cff4e8-c0cff50c: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc89f0)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
c000000000cc8950-c000000000cc8988: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076b84e)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffe00076b7ca-ffffffe00076b800: neigh_ifdown (STB_GLOBAL)
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
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e58d0)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff818e5870-ffffffff818e5884: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8189f710)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff8189f6b0-ffffffff8189f6c4: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81936900)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff819368a0-ffffffff819368b4: neigh_ifdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int neigh_ifdown(struct neigh_table *tbl, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81958090)
Location: net/core/neighbour.c:367
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
Direct callers:
  - net/ipv4/arp.c:arp_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
**Symbols:**

```
ffffffff81958030-ffffffff81958044: neigh_ifdown (STB_GLOBAL)
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
