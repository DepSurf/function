# Function: <code>inet6_del_protocol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81800a10)
Location: net/ipv6/protocol.c:39
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81800a10-ffffffff81800a49: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81872130)
Location: net/ipv6/protocol.c:39
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81872130-ffffffff81872169: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff818a6710)
Location: net/ipv6/protocol.c:39
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff818a6710-ffffffff818a6749: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff818cd170)
Location: net/ipv6/protocol.c:39
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff818cd170-ffffffff818cd1a9: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81951f50)
Location: net/ipv6/protocol.c:39
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81951f50-ffffffff81951f89: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff819ab4d0)
Location: net/ipv6/protocol.c:39
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff819ab4d0-ffffffff819ab509: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff819e1ff0)
Location: net/ipv6/protocol.c:39
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff819e1ff0-ffffffff819e2029: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81a50c80)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81a50c80-ffffffff81a50cb9: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81a878a0)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81a878a0-ffffffff81a878d9: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81b82d60)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81b82d60-ffffffff81b82d99: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81b923e0)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81b923e0-ffffffff81b92419: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81b81530)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81b81530-ffffffff81b81569: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81c4d550)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81c4d550-ffffffff81c4d589: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81dedae0)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81dedae0-ffffffff81dedb23: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81fc19e0)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81fc19e0-ffffffff81fc1a23: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff82022960)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff82022960-ffffffff820229a3: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff820f1a80)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff820f1a80-ffffffff820f1ac3: inet6_del_protocol (STB_GLOBAL)
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
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffff800010d54168)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffff800010d54168-ffff800010d541ec: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (c0e548ec)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
c0e548ec-c0e54948: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (c000000000e8ccb0)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
c000000000e8ccb0-c000000000e8cd34: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffe00088bd12)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffe00088bd12-ffffffe00088bd6c: inet6_del_protocol (STB_GLOBAL)
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
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81a26f30)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81a26f30-ffffffff81a26f69: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff819e3cf0)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff819e3cf0-ffffffff819e3d29: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81a92ae0)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81a92ae0-ffffffff81a92b19: inet6_del_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet6_del_protocol(const struct inet6_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/protocol.c (ffffffff81a9ebe0)
Location: net/ipv6/protocol.c:35
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_exit
  - net/ipv6/udp.c:udpv6_init
  - net/ipv6/udplite.c:udplitev6_exit
  - net/ipv6/udplite.c:udplitev6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_exit
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/exthdrs.c:ipv6_exthdrs_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
**Symbols:**

```
ffffffff81a9ebe0-ffffffff81a9ec19: inet6_del_protocol (STB_GLOBAL)
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
