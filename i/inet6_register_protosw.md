# Function: <code>inet6_register_protosw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff817c3050)
Location: net/ipv6/af_inet6.c:572
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff817c3050-ffffffff817c3102: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff818300c0)
Location: net/ipv6/af_inet6.c:586
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff818300c0-ffffffff8183017d: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81861b40)
Location: net/ipv6/af_inet6.c:597
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff81861b40-ffffffff81861bfd: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81886260)
Location: net/ipv6/af_inet6.c:598
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff81886260-ffffffff81886319: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81907470)
Location: net/ipv6/af_inet6.c:603
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff81907470-ffffffff81907529: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:629
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff8195ef8a-ffffffff8195efbb: inet6_register_protosw.cold.14 (STB_LOCAL)
ffffffff8195e050-ffffffff8195e0e8: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:641
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff81993b7a-ffffffff81993bab: inet6_register_protosw.cold.16 (STB_LOCAL)
ffffffff81992bb0-ffffffff81992c48: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff819ff62e-ffffffff819ff661: inet6_register_protosw.cold (STB_LOCAL)
ffffffff819fe610-ffffffff819fe6aa: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff81a3622e-ffffffff81a36261: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81a35200-ffffffff81a3529a: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:731
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
```
**Symbols:**

```
ffffffff81b2b2e7-ffffffff81b2b31a: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81b2a1b0-ffffffff81b2a24a: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:728
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
```
**Symbols:**

```
ffffffff81c32ad4-ffffffff81c32b07: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81b38b10-ffffffff81b38baa: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:732
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
```
**Symbols:**

```
ffffffff81c24de4-ffffffff81c24e17: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81b26800-ffffffff81b2689a: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:734
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
```
**Symbols:**

```
ffffffff81d3f081-ffffffff81d3f0b4: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81bec250-ffffffff81bec387: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:745
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
```
**Symbols:**

```
ffffffff81f0b9c0-ffffffff81f0b9f1: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81d847b0-ffffffff81d848ef: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81f520e0)
Location: net/ipv6/af_inet6.c:754
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
```
**Symbols:**

```
ffffffff81f520e0-ffffffff81f5224e: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81fb1af0)
Location: net/ipv6/af_inet6.c:742
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
```
**Symbols:**

```
ffffffff81fb1af0-ffffffff81fb1c5e: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff8207f210)
Location: net/ipv6/af_inet6.c:751
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
```
**Symbols:**

```
ffffffff8207f210-ffffffff8207f37e: inet6_register_protosw (STB_GLOBAL)
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
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffff800010cf6418)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffff800010cf6418-ffff800010cf6564: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (c0dfc580)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
c0dfc580-c0dfc660: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (c000000000e1c010)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
c000000000e1c010-c000000000e1c14c: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffe0008415b4)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffe0008415b4-ffffffe00084167a: inet6_register_protosw (STB_GLOBAL)
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
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff819d58be-ffffffff819d58f1: inet6_register_protosw.cold (STB_LOCAL)
ffffffff819d4890-ffffffff819d492a: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff8199267e-ffffffff819926b1: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81991650-ffffffff819916ea: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff81a4033e-ffffffff81a40371: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81a3f310-ffffffff81a3f3aa: inet6_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int inet6_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:667
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/raw.c:rawv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
```
**Symbols:**

```
ffffffff81a4bf2e-ffffffff81a4bf61: inet6_register_protosw.cold (STB_LOCAL)
ffffffff81a4ae10-ffffffff81a4aeaa: inet6_register_protosw (STB_GLOBAL)
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
