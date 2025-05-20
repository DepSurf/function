# Function: <code>ndisc_send_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff817e0940)
Location: net/ipv6/ndisc.c:558
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff817e0940-ffffffff817e0a93: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8184d880)
Location: net/ipv6/ndisc.c:573
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff8184d880-ffffffff8184da53: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8187f730)
Location: net/ipv6/ndisc.c:571
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff8187f730-ffffffff8187f92b: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff818a5820)
Location: net/ipv6/ndisc.c:571
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff818a5820-ffffffff818a5a19: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81928230)
Location: net/ipv6/ndisc.c:584
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81928230-ffffffff8192842f: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819805c0)
Location: net/ipv6/ndisc.c:584
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff819805c0-ffffffff819807c9: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819b6bd0)
Location: net/ipv6/ndisc.c:584
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff819b6bd0-ffffffff819b6dd9: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a25650)
Location: net/ipv6/ndisc.c:597
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81a25650-ffffffff81a2585b: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a5c0d0)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81a5c0d0-ffffffff81a5c2db: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81b566b0)
Location: net/ipv6/ndisc.c:599
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81b566b0-ffffffff81b568ac: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81b64d20)
Location: net/ipv6/ndisc.c:601
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81b64d20-ffffffff81b64f1c: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81b52ff0)
Location: net/ipv6/ndisc.c:601
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81b52ff0-ffffffff81b531f2: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81c1a500)
Location: net/ipv6/ndisc.c:601
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81c1a500-ffffffff81c1a702: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81db6b70)
Location: net/ipv6/ndisc.c:648
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81db6b70-ffffffff81db6c33: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f86800)
Location: net/ipv6/ndisc.c:649
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81f86800-ffffffff81f868c3: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe6b40)
Location: net/ipv6/ndisc.c:650
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81fe6b40-ffffffff81fe6c03: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b49a0)
Location: net/ipv6/ndisc.c:650
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff820b49a0-ffffffff820b4a63: ndisc_send_ns (STB_GLOBAL)
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
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffff800010d21480)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffff800010d21480-ffff800010d21674: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c0e25ea4)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
c0e25ea4-c0e260d8: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c000000000e509f0)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
c000000000e509f0-c000000000e50c98: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffe000863346)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffe000863346-ffffffe000863508: ndisc_send_ns (STB_GLOBAL)
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
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819fb760)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff819fb760-ffffffff819fb96b: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819b8520)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff819b8520-ffffffff819b872b: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a661e0)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81a661e0-ffffffff81a663eb: ndisc_send_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ndisc_send_ns(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *daddr, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81a727c0)
Location: net/ipv6/ndisc.c:598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
```
**Symbols:**

```
ffffffff81a727c0-ffffffff81a729cb: ndisc_send_ns (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 nonce</code>
</li>
</ul>
</details>
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
