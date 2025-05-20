# Function: <code>inet_ctl_sock_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81793ac0)
Location: net/ipv4/af_inet.c:1428
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/icmp.c:icmpv6_sk_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81793ac0-ffffffff81793b3c: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81801620)
Location: net/ipv4/af_inet.c:1492
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/icmp.c:icmpv6_sk_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81801620-ffffffff8180169c: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81832430)
Location: net/ipv4/af_inet.c:1506
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/icmp.c:icmpv6_sk_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81832430-ffffffff818324ac: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81853730)
Location: net/ipv4/af_inet.c:1527
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81853730-ffffffff818537b0: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d35a0)
Location: net/ipv4/af_inet.c:1531
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff818d35a0-ffffffff818d3626: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81929a70)
Location: net/ipv4/af_inet.c:1600
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81929a70-ffffffff81929af2: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81959060)
Location: net/ipv4/af_inet.c:1609
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81959060-ffffffff819590e2: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bdb30)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff819bdb30-ffffffff819bdbb6: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f4740)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff819f4740-ffffffff819f47c6: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae2450)
Location: net/ipv4/af_inet.c:1656
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81ae2450-ffffffff81ae24d6: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81aef2f0)
Location: net/ipv4/af_inet.c:1648
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81aef2f0-ffffffff81aef376: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adaa40)
Location: net/ipv4/af_inet.c:1649
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81adaa40-ffffffff81adaac6: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b99c80)
Location: net/ipv4/af_inet.c:1654
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81b99c80-ffffffff81b99d06: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2bc50)
Location: net/ipv4/af_inet.c:1642
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81d2bc50-ffffffff81d2bced: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef3880)
Location: net/ipv4/af_inet.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81ef3880-ffffffff81ef3928: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f53330)
Location: net/ipv4/af_inet.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81f53330-ffffffff81f533d8: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff820196e0)
Location: net/ipv4/af_inet.c:1682
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff820196e0-ffffffff82019788: inet_ctl_sock_create (STB_GLOBAL)
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
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010caa5f0)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffff800010caa5f0-ffff800010caa6a4: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db6cf8)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
c0db6cf8-c0db6d8c: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc06f0)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
c000000000dc06f0-c000000000dc07a8: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe0008053ee)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffe0008053ee-ffffffe00080545e: inet_ctl_sock_create (STB_GLOBAL)
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
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819944e0)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff819944e0-ffffffff81994566: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194dfa0)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff8194dfa0-ffffffff8194e026: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819fed80)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff819fed80-ffffffff819fee06: inet_ctl_sock_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_ctl_sock_create(struct sock **sk, short unsigned int family, short unsigned int type, unsigned char protocol, struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a08e50)
Location: net/ipv4/af_inet.c:1624
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcpv6_net_init
```
**Symbols:**

```
ffffffff81a08e50-ffffffff81a08ed6: inet_ctl_sock_create (STB_GLOBAL)
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
