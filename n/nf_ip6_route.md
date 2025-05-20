# Function: <code>nf_ip6_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nf_ip6_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff817fdb50)
Location: net/ipv6/netfilter.c:110
Inline: False
```
**Symbols:**

```
ffffffff817fdb50-ffffffff817fdb9a: nf_ip6_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nf_ip6_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff8186d480)
Location: net/ipv6/netfilter.c:110
Inline: False
```
**Symbols:**

```
ffffffff8186d480-ffffffff8186d4ca: nf_ip6_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nf_ip6_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff818a0260)
Location: net/ipv6/netfilter.c:111
Inline: False
```
**Symbols:**

```
ffffffff818a0260-ffffffff818a02aa: nf_ip6_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nf_ip6_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff818c68a0)
Location: net/ipv6/netfilter.c:111
Inline: False
```
**Symbols:**

```
ffffffff818c68a0-ffffffff818c68ea: nf_ip6_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nf_ip6_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81949c80)
Location: net/ipv6/netfilter.c:112
Inline: False
```
**Symbols:**

```
ffffffff81949c80-ffffffff81949cca: nf_ip6_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nf_ip6_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff819a2c90)
Location: net/ipv6/netfilter.c:87
Inline: False
```
**Symbols:**

```
ffffffff819a2c90-ffffffff819a2cda: nf_ip6_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nf_ip6_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff819d9930)
Location: net/ipv6/netfilter.c:89
Inline: False
```
**Symbols:**

```
ffffffff819d9930-ffffffff819d997a: nf_ip6_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81970769)
Location: include/linux/netfilter_ipv6.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819a7159)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a904b9)
Location: include/linux/netfilter_ipv6.h:99
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a9a389)
Location: include/linux/netfilter_ipv6.h:99
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a85679)
Location: include/linux/netfilter_ipv6.h:99
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81b3fd69)
Location: include/linux/netfilter_ipv6.h:99
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81ccc5b9)
Location: include/linux/netfilter_ipv6.h:99
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81e8c4c9)
Location: include/linux/netfilter_ipv6.h:99
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81eea559)
Location: include/linux/netfilter_ipv6.h:99
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81fae309)
Location: include/linux/netfilter_ipv6.h:99
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffff800010c56c1c)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c0d6637c)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c000000000d5786c)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffe0007c0bb8)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81946fc9)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81900ab9)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81998159)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819bae39)
Location: include/linux/netfilter_ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_route
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
</ul>
