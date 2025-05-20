# Function: <code>sock_queue_rcv_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81702e90)
Location: net/core/sock.c:447
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81702e90-ffffffff81703085: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81768530)
Location: net/core/sock.c:443
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81768530-ffffffff81768560: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81795580)
Location: net/core/sock.c:443
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81795580-ffffffff817955b0: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b3b40)
Location: net/core/sock.c:485
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff817b3b40-ffffffff817b3b70: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182d1f0)
Location: net/core/sock.c:475
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8182d1f0-ffffffff8182d220: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81876fd0)
Location: net/core/sock.c:481
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81876fd0-ffffffff81877000: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897770)
Location: net/core/sock.c:437
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81897770-ffffffff818977a0: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1b90)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff818e1b90-ffffffff818e1bc2: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81913d80)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81913d80-ffffffff81913db2: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5ec0)
Location: net/core/sock.c:483
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff819e5ec0-ffffffff819e5ef2: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5980)
Location: net/core/sock.c:473
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff819e5980-ffffffff819e59b2: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cba90)
Location: net/core/sock.c:473
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff819cba90-ffffffff819cbac2: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7b150)
Location: net/core/sock.c:492
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81a7b150-ffffffff81a7b182: sock_queue_rcv_skb (STB_GLOBAL)
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
In net/ipv4/raw.c (ffffffff81d15c57)
Location: include/net/sock.h:2432
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d5431d)
Location: include/net/sock.h:2432
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/raw.c (ffffffff81dbe73c)
Location: include/net/sock.h:2432
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaacd)
Location: include/net/sock.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/packet/af_packet.c (ffffffff81df398b)
Location: include/net/sock.h:2432
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/mctp/route.c (ffffffff81e3a578)
Location: include/net/sock.h:2432
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
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
In net/ipv4/raw.c (ffffffff81edc077)
Location: include/net/sock.h:2480
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1e4f8)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/raw.c (ffffffff81f8ec02)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81fac7d7)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/packet/af_packet.c (ffffffff81fc873d)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/mctp/route.c (ffffffff82013a25)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
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
In net/ipv4/ipmr.c (ffffffff81f7dfe2)
Location: include/net/sock.h:2468
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff8200cf71)
Location: include/net/sock.h:2468
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/packet/af_packet.c (ffffffff82026fcd)
Location: include/net/sock.h:2468
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/mctp/route.c (ffffffff8209086c)
Location: include/net/sock.h:2468
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
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
In net/ipv4/ipmr.c (ffffffff8204481e)
Location: include/net/sock.h:2458
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6mr.c (ffffffff820dbf41)
Location: include/net/sock.h:2458
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/packet/af_packet.c (ffffffff820f7e64)
Location: include/net/sock.h:2458
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/mctp/route.c (ffffffff82166dac)
Location: include/net/sock.h:2458
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
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
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bad238)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffff800010bad238-ffff800010bad280: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cca518)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
c0cca518-c0cca554: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c82660)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
c000000000c82660-c000000000c826e0: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073f150)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffe00073f150-ffffffe00073f192: sock_queue_rcv_skb (STB_GLOBAL)
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
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b3d80)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff818b3d80-ffffffff818b3db2: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186dcd0)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8186dcd0-ffffffff8186dd02: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81904d80)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81904d80-ffffffff81904db2: sock_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81925e40)
Location: net/core/sock.c:486
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81925e40-ffffffff81925e72: sock_queue_rcv_skb (STB_GLOBAL)
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
