# Function: <code>inet_ctl_sock_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8177b8b0)
Location: include/net/inet_common.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff8178de40)
Location: include/net/inet_common.h:42
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
```
```
In net/ipv4/igmp.c (ffffffff8179576a)
Location: include/net/inet_common.h:42
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff817de56c)
Location: include/net/inet_common.h:42
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff817e7448)
Location: include/net/inet_common.h:42
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
```
```
In net/ipv6/mcast.c (ffffffff817e97b4)
Location: include/net/inet_common.h:42
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817efbec)
Location: include/net/inet_common.h:42
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817e9130)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff817fb5d4)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff8180315a)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff8184c48c)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81855848)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
```
```
In net/ipv6/mcast.c (ffffffff81858004)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185e7dc)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81819325)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff8182c48f)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff818340fa)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff8187e35c)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff8188753d)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/icmp.c:icmpv6_sk_init
```
```
In net/ipv6/mcast.c (ffffffff8188a0c4)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189091c)
Location: include/net/inet_common.h:47
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81839a43)
Location: include/net/inet_common.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff8184d793)
Location: include/net/inet_common.h:48
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff818556da)
Location: include/net/inet_common.h:48
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff818a43ac)
Location: include/net/inet_common.h:48
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff818adaeb)
Location: include/net/inet_common.h:48
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff818b00f4)
Location: include/net/inet_common.h:48
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b6f0c)
Location: include/net/inet_common.h:48
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818b920b)
Location: include/net/inet_common.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff818cd4c8)
Location: include/net/inet_common.h:49
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff818d557a)
Location: include/net/inet_common.h:49
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81926d5c)
Location: include/net/inet_common.h:49
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81930780)
Location: include/net/inet_common.h:49
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81932da4)
Location: include/net/inet_common.h:49
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81939d3c)
Location: include/net/inet_common.h:49
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8190e60b)
Location: include/net/inet_common.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff819238a8)
Location: include/net/inet_common.h:51
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff8192beda)
Location: include/net/inet_common.h:51
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff8197f10c)
Location: include/net/inet_common.h:51
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81989410)
Location: include/net/inet_common.h:51
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff8198b851)
Location: include/net/inet_common.h:51
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81991fec)
Location: include/net/inet_common.h:51
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193c9fb)
Location: include/net/inet_common.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff81952698)
Location: include/net/inet_common.h:53
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff8195b36a)
Location: include/net/inet_common.h:53
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff819b56dc)
Location: include/net/inet_common.h:53
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff819bfd30)
Location: include/net/inet_common.h:53
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff819c24f1)
Location: include/net/inet_common.h:53
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c885c)
Location: include/net/inet_common.h:53
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a0e5d)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff819b6f55)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff819c003a)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81a241ac)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81a2ea05)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81a312e1)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a371fc)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d7a2d)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff819edc55)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff819f6bda)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81a5ac2c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81a65555)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81a67e31)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6dd1c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4acf)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff81adba55)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff81ae4e1a)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81b5393c)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81b5dca5)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81b60131)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6701c)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad02df)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff81ae8525)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff81af1cea)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81b61ecc)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81b6c475)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81b6e8a1)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7557c)
Location: include/net/inet_common.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abb441)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff81ad37ba)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff81add4da)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81b5017c)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81b5a7ca)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81b5cca1)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6402c)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b78799)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff81b92432)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff81b9c94a)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81c174dc)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81c21e02)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81c244f1)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2baec)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d2e98a)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81db32fc)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/mcast.c (ffffffff81dc19c1)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc902c)
Location: include/net/inet_common.h:62
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef697a)
Location: include/net/inet_common.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81f8291c)
Location: include/net/inet_common.h:68
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/mcast.c (ffffffff81f922e1)
Location: include/net/inet_common.h:68
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99d2c)
Location: include/net/inet_common.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f563ea)
Location: include/net/inet_common.h:69
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81fe2c2c)
Location: include/net/inet_common.h:69
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/mcast.c (ffffffff81ff2c51)
Location: include/net/inet_common.h:69
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa6fc)
Location: include/net/inet_common.h:69
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201c88a)
Location: include/net/inet_common.h:71
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff820b0b4c)
Location: include/net/inet_common.h:71
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/mcast.c (ffffffff820c08e1)
Location: include/net/inet_common.h:71
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c83ec)
Location: include/net/inet_common.h:71
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8a8f4)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffff800010ca37b4)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffff800010cad704)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffff800010d1ffb4)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffff800010d2b50c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffff800010d2dcb4)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d364cc)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9aa5c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (c0db0488)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (c0dba608)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (c0e24b6c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (c0e2f194)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (c0e31b98)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (c0e39408)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d990d4)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (c000000000db6fdc)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (c000000000dc3d20)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (c000000000e4e754)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (c000000000e5c94c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (c000000000e5fa34)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (c000000000e68ab4)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebaf8)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffe0007ff61a)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffe000807b52)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffe000862110)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffe00086b754)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffe00086dd10)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873b22)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8197789d)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff8198d9f5)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff8199697a)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff819fa2bc)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81a04be5)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81a074c1)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d3ac)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193135d)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff819474b5)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff8195043a)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff819b707c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff819c19a5)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff819c4281)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca16c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e206d)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff819f8295)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff81a0121a)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81a64d3c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81a6f665)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81a71f41)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a77e2c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819ebdbd)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/icmp.c (ffffffff81a02595)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_exit
```
```
In net/ipv4/igmp.c (ffffffff81a0b70a)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_exit
```
```
In net/ipv6/ndisc.c (ffffffff81a7126c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_exit
```
```
In net/ipv6/icmp.c (ffffffff81a7bc95)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_sk_exit
```
```
In net/ipv6/mcast.c (ffffffff81a7e571)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8459c)
Location: include/net/inet_common.h:54
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcpv6_net_exit
```
</details>
</li>
</ul>

## Differences
