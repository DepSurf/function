# Function: <code>ndisc_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8184dd00)
Location: net/ipv6/ndisc.c:723
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8184dd00-ffffffff8184dd5e: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8187fbe0)
Location: net/ipv6/ndisc.c:731
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8187fbe0-ffffffff8187fc3e: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff818a5cd0)
Location: net/ipv6/ndisc.c:731
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff818a5cd0-ffffffff818a5d31: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819286e0)
Location: net/ipv6/ndisc.c:744
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819286e0-ffffffff81928744: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81980a80)
Location: net/ipv6/ndisc.c:744
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81980a80-ffffffff81980ae4: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819b7090)
Location: net/ipv6/ndisc.c:744
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819b7090-ffffffff819b70f4: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a25b20)
Location: net/ipv6/ndisc.c:757
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a25b20-ffffffff81a25b84: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a5c5a0)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a5c5a0-ffffffff81a5c604: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81b55282)
Location: net/ipv6/ndisc.c:759
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81b56b60-ffffffff81b56bc4: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81b638a2)
Location: net/ipv6/ndisc.c:761
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81b651d0-ffffffff81b65234: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81b51c40)
Location: net/ipv6/ndisc.c:761
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81b534c0-ffffffff81b53524: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81c190f0)
Location: net/ipv6/ndisc.c:761
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81c1a9d0-ffffffff81c1aa34: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81db5358)
Location: net/ipv6/ndisc.c:776
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81db6f20-ffffffff81db6f98: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f84f58)
Location: net/ipv6/ndisc.c:777
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81f86be0-ffffffff81f86c58: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe51fd)
Location: net/ipv6/ndisc.c:778
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81fe6f20-ffffffff81fe6f98: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b30b0)
Location: net/ipv6/ndisc.c:778
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff820b4d80-ffffffff820b4df8: ndisc_update (STB_GLOBAL)
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
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffff800010d21938)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffff800010d21938-ffff800010d219cc: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c0e263cc)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
c0e263cc-c0e2644c: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c000000000e51090)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
c000000000e51090-c000000000e51150: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffe000863748)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffe000863748-ffffffe0008637b4: ndisc_update (STB_GLOBAL)
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
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819fbc30)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819fbc30-ffffffff819fbc94: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819b89f0)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819b89f0-ffffffff819b8a54: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a666b0)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a666b0-ffffffff81a66714: ndisc_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ndisc_update(const struct net_device *dev, struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options *ndopts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a72c90)
Location: net/ipv6/ndisc.c:758
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a72c90-ffffffff81a72cf4: ndisc_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
