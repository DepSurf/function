# Function: <code>inet6_addr_modify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817d0239)
Location: net/ipv6/addrconf.c:4106
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183dbe2)
Location: net/ipv6/addrconf.c:4358
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186f7f2)
Location: net/ipv6/addrconf.c:4401
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff818945bc)
Location: net/ipv6/addrconf.c:4477
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81915a3e)
Location: net/ipv6/addrconf.c:4481
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196d0cf)
Location: net/ipv6/addrconf.c:4562
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a2c03)
Location: net/ipv6/addrconf.c:4584
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0dbe0)
Location: net/ipv6/addrconf.c:4620
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81a0dbe0-ffffffff81a0dfad: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a448c0)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81a448c0-ffffffff81a44cf0: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3b1b0)
Location: net/ipv6/addrconf.c:4646
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81b3b1b0-ffffffff81b3b62a: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b49ec0)
Location: net/ipv6/addrconf.c:4673
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81b49ec0-ffffffff81b4a33a: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b37ab0)
Location: net/ipv6/addrconf.c:4677
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81b37ab0-ffffffff81b37ee8: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:4713
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81bfe2a0-ffffffff81bfe6e4: inet6_addr_modify (STB_LOCAL)
ffffffff81d3f9f3-ffffffff81d3fa07: inet6_addr_modify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet6_addr_modify(struct net *net, struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:4720
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81d97c80-ffffffff81d980fd: inet6_addr_modify (STB_LOCAL)
ffffffff81f0c366-ffffffff81f0c37b: inet6_addr_modify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int inet6_addr_modify(struct net *net, struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:4733
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81f66900-ffffffff81f66d7d: inet6_addr_modify (STB_LOCAL)
ffffffff820b3b4c-ffffffff820b3b61: inet6_addr_modify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int inet6_addr_modify(struct net *net, struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:4739
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81fc6a10-ffffffff81fc6e8d: inet6_addr_modify (STB_LOCAL)
ffffffff82134c3d-ffffffff82134c52: inet6_addr_modify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int inet6_addr_modify(struct net *net, struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:4790
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff82094130-ffffffff820945ad: inet6_addr_modify (STB_LOCAL)
ffffffff82216701-ffffffff82216716: inet6_addr_modify.cold (STB_LOCAL)
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
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d06cc8)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffff800010d06cc8-ffff800010d07184: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0d89c)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
c0e0d89c-c0e0dd14: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e31090)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
c000000000e31090-c000000000e315b8: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084eb70)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffe00084eb70-ffffffe00084ef18: inet6_addr_modify (STB_LOCAL)
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
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e3f50)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff819e3f50-ffffffff819e4380: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a0d10)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff819a0d10-ffffffff819a1140: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4e9d0)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81a4e9d0-ffffffff81a4ee00: inet6_addr_modify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr *ifp, struct ifa6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a5a970)
Location: net/ipv6/addrconf.c:4629
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff81a5a970-ffffffff81a5ada0: inet6_addr_modify (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>ifp, cfg</code> ➡️ <code>net, ifp, cfg</code>
</li>
</ul>
</details>
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
