# Function: <code>ip6_dst_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c4660)
Location: net/ipv6/ip6_output.c:1020
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
**Symbols:**

```
ffffffff817c4660-ffffffff817c4677: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818317d0)
Location: net/ipv6/ip6_output.c:1027
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff818317d0-ffffffff818317e7: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81863230)
Location: net/ipv6/ip6_output.c:1056
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81863230-ffffffff81863247: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81887a30)
Location: net/ipv6/ip6_output.c:1051
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81887a30-ffffffff81887a47: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81908ce0)
Location: net/ipv6/ip6_output.c:1070
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81908ce0-ffffffff81908cf7: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8195feb0)
Location: net/ipv6/ip6_output.c:1052
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff8195feb0-ffffffff8195fec7: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81994c40)
Location: net/ipv6/ip6_output.c:1061
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81994c40-ffffffff81994c57: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a00830)
Location: net/ipv6/ip6_output.c:1125
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81a00830-ffffffff81a00847: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a37400)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81a37400-ffffffff81a37417: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2c920)
Location: net/ipv6/ip6_output.c:1129
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81b2c920-ffffffff81b2c937: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3b330)
Location: net/ipv6/ip6_output.c:1167
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81b3b330-ffffffff81b3b347: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b291b0)
Location: net/ipv6/ip6_output.c:1198
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81b291b0-ffffffff81b291c7: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81bf0320)
Location: net/ipv6/ip6_output.c:1177
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81bf0320-ffffffff81bf0337: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d88b90)
Location: net/ipv6/ip6_output.c:1199
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81d88b90-ffffffff81d88bb3: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f569a0)
Location: net/ipv6/ip6_output.c:1217
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81f569a0-ffffffff81f569c3: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb63d0)
Location: net/ipv6/ip6_output.c:1218
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81fb63d0-ffffffff81fb63f3: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff82083a90)
Location: net/ipv6/ip6_output.c:1227
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff82083a90-ffffffff82083ab3: ip6_dst_lookup (STB_GLOBAL)
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
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cf9f88)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffff800010cf9f88-ffff800010cf9fd8: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0dfe904)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
c0dfe904-c0dfe928: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e1ee80)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
c000000000e1ee80-c000000000e1ee9c: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe000843462)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffe000843462-ffffffe0008434a8: ip6_dst_lookup (STB_GLOBAL)
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
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d6a90)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff819d6a90-ffffffff819d6aa7: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81993850)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81993850-ffffffff81993867: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a41510)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81a41510-ffffffff81a41527: ip6_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_dst_lookup(struct net *net, struct sock *sk, struct dst_entry **dst, struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4d170)
Location: net/ipv6/ip6_output.c:1128
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
**Symbols:**

```
ffffffff81a4d170-ffffffff81a4d187: ip6_dst_lookup (STB_GLOBAL)
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
