# Function: <code>ip6_sk_dst_lookup_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c4750)
Location: net/ipv6/ip6_output.c:1071
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff817c4750-ffffffff817c4923: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818318c0)
Location: net/ipv6/ip6_output.c:1078
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff818318c0-ffffffff818319fc: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818632f0)
Location: net/ipv6/ip6_output.c:1105
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff818632f0-ffffffff8186342c: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81888b60)
Location: net/ipv6/ip6_output.c:1100
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81888b60-ffffffff81888c99: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81908f70)
Location: net/ipv6/ip6_output.c:1119
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81908f70-ffffffff819090a9: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81960240)
Location: net/ipv6/ip6_output.c:1105
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81960240-ffffffff819603e6: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81995020)
Location: net/ipv6/ip6_output.c:1114
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81995020-ffffffff819951c6: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a015ac)
Location: net/ipv6/ip6_output.c:1178
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a04d76-ffffffff81a04d80: ip6_sk_dst_lookup_flow.cold (STB_LOCAL)
ffffffff81a014d0-ffffffff81a0166d: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a38670)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a38670-ffffffff81a38818: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2cd60)
Location: net/ipv6/ip6_output.c:1182
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b2cd60-ffffffff81b2cefb: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3b770)
Location: net/ipv6/ip6_output.c:1221
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b3b770-ffffffff81b3b90b: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b291d0)
Location: net/ipv6/ip6_output.c:1252
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b291d0-ffffffff81b2936b: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1231
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81d3f3a7-ffffffff81d3f3e7: ip6_sk_dst_lookup_flow.cold (STB_LOCAL)
ffffffff81bf0340-ffffffff81bf04f9: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1253
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81f0bccb-ffffffff81f0bd0b: ip6_sk_dst_lookup_flow.cold (STB_LOCAL)
ffffffff81d889d0-ffffffff81d88b89: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1271
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff820b34cb-ffffffff820b350b: ip6_sk_dst_lookup_flow.cold (STB_LOCAL)
ffffffff81f567d0-ffffffff81f56989: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1272
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff8213466b-ffffffff8213469d: ip6_sk_dst_lookup_flow.cold (STB_LOCAL)
ffffffff81fb61d0-ffffffff81fb63b5: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1281
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff82216229-ffffffff8221625b: ip6_sk_dst_lookup_flow.cold (STB_LOCAL)
ffffffff82083890-ffffffff82083a75: ip6_sk_dst_lookup_flow (STB_GLOBAL)
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
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfa088)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffff800010cfa088-ffff800010cfa278: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e002f4)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
c0e002f4-c0e0056c: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e21fc0)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
c000000000e21fc0-c000000000e2221c: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe0008448cc)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffe0008448cc-ffffffe000844ad2: ip6_sk_dst_lookup_flow (STB_GLOBAL)
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
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d7d00)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff819d7d00-ffffffff819d7ea8: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81994ac0)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81994ac0-ffffffff81994c68: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a42780)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a42780-ffffffff81a42928: ip6_sk_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_sk_dst_lookup_flow(struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst, bool connected);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4e410)
Location: net/ipv6/ip6_output.c:1181
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a4e410-ffffffff81a4e5b8: ip6_sk_dst_lookup_flow (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool connected</code>
</li>
</ul>
</details>
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
