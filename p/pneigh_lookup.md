# Function: <code>pneigh_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81724a40)
Location: net/core/neighbour.c:576
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81724a40-ffffffff81724bcf: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8178e4f0)
Location: net/core/neighbour.c:576
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff8178e4f0-ffffffff8178e695: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817bbdc0)
Location: net/core/neighbour.c:577
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff817bbdc0-ffffffff817bbf65: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817da4c0)
Location: net/core/neighbour.c:612
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff817da4c0-ffffffff817da644: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81854c60)
Location: net/core/neighbour.c:612
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff81854c60-ffffffff81854de7: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818a01d0)
Location: net/core/neighbour.c:614
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff818a01d0-ffffffff818a036a: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c2b50)
Location: net/core/neighbour.c:711
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff818c2b50-ffffffff818c2cee: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8190f8e0)
Location: net/core/neighbour.c:715
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff8190f8e0-ffffffff8190fa8a: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81941f50)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff81941f50-ffffffff819420fa: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a11590)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff81a11590-ffffffff81a1173a: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a118f0)
Location: net/core/neighbour.c:714
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff81a118f0-ffffffff81a11a9a: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff819f8560)
Location: net/core/neighbour.c:718
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff819f8560-ffffffff819f870a: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:718
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff81d36a20-ffffffff81d36a3c: pneigh_lookup.cold (STB_LOCAL)
ffffffff81aaa3e0-ffffffff81aaa592: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:763
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff81f03301-ffffffff81f03315: pneigh_lookup.cold (STB_LOCAL)
ffffffff81c23200-ffffffff81c233b9: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:801
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff820abb45-ffffffff820abb59: pneigh_lookup.cold (STB_LOCAL)
ffffffff81dd4fd0-ffffffff81dd5189: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:770
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff8212d299-ffffffff8212d2ad: pneigh_lookup.cold (STB_LOCAL)
ffffffff81e45f20-ffffffff81e460d9: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:778
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff8220efc5-ffffffff8220efd9: pneigh_lookup.cold (STB_LOCAL)
ffffffff81f04bc0-ffffffff81f04d79: pneigh_lookup (STB_GLOBAL)
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
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be5270)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffff800010be5270-ffff800010be552c: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cfc940)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
c0cfc940-c0cfcb14: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc3ff0)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
c000000000cc3ff0-c000000000cc429c: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe000768724)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffe000768724-ffffffe0007688de: pneigh_lookup (STB_GLOBAL)
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
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e1f20)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff818e1f20-ffffffff818e20ca: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8189bd60)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff8189bd60-ffffffff8189bf0a: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81932f50)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff81932f50-ffffffff819330fa: pneigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pneigh_entry *pneigh_lookup(struct neigh_table *tbl, struct net *net, const void *pkey, struct net_device *dev, int creat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81954880)
Location: net/core/neighbour.c:712
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ndisc.c:ndisc_recv_na
```
**Symbols:**

```
ffffffff81954880-ffffffff81954a2a: pneigh_lookup (STB_GLOBAL)
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
