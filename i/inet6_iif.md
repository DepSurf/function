# Function: <code>inet6_iif</code>

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
In net/ipv4/ping.c (ffffffff817a353c)
Location: include/linux/ipv6.h:122
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff817e3123)
Location: include/linux/ipv6.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffff817e574b)
Location: include/linux/ipv6.h:122
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f04bc)
Location: include/linux/ipv6.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff8181059d)
Location: include/linux/ipv6.h:139
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81852b87)
Location: include/linux/ipv6.h:139
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff818539ed)
Location: include/linux/ipv6.h:139
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818604f7)
Location: include/linux/ipv6.h:139
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81841a9d)
Location: include/linux/ipv6.h:145
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81884887)
Location: include/linux/ipv6.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff818856fd)
Location: include/linux/ipv6.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189247e)
Location: include/linux/ipv6.h:145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff818631e7)
Location: include/linux/ipv6.h:149
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff818aac37)
Location: include/linux/ipv6.h:149
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff818abac7)
Location: include/linux/ipv6.h:149
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8ad4)
Location: include/linux/ipv6.h:149
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff818e3317)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff8192d793)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff8192e687)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b999)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81939cb7)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819864ec)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81987614)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994bae)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81969944)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819bce8f)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819bdc21)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb49c)
Location: include/linux/ipv6.h:151
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff819d05b5)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a2b984)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a2c707)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a35d6c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39f00)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81a07105)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a624e7)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a63247)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a6c88c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70a90)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81af7705)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b5b095)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c197)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81b65a8c)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a21b)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81b045e5)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b697b3)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b6a887)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81b741ec)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78cb3)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b80bc4)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/ipv4/ping.c (ffffffff81aef5f5)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b57b66)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b58e27)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81b62c4c)
Location: include/linux/ipv6.h:158
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67940)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f7e3)
Location: include/linux/ipv6.h:158
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/ipv4/ping.c (ffffffff81bb0b81)
Location: include/linux/ipv6.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81c1f091)
Location: include/linux/ipv6.h:163
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81c203df)
Location: include/linux/ipv6.h:163
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81c2a6e7)
Location: include/linux/ipv6.h:163
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f4e8)
Location: include/linux/ipv6.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81c378a0)
Location: include/linux/ipv6.h:163
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/ipv4/ping.c (ffffffff81d440f4)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81dbb9fa)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81dbd146)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81dc7b9a)
Location: include/linux/ipv6.h:166
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd74c)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd540b)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/ipv4/ping.c (ffffffff81f0d5c3)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81f8baff)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81f8d166)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81f9890a)
Location: include/linux/ipv6.h:166
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e84c)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6b17)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/ipv4/ping.c (ffffffff81f6d225)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81fec060)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fed936)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81ff92ea)
Location: include/linux/ipv6.h:166
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff308)
Location: include/linux/ipv6.h:166
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff82033979)
Location: include/linux/ipv6.h:169
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff820b9e6e)
Location: include/linux/ipv6.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bb546)
Location: include/linux/ipv6.h:169
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/reassembly.c (ffffffff820c6f69)
Location: include/linux/ipv6.h:169
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ce018)
Location: include/linux/ipv6.h:169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffff800010cc0038)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffff800010d2710c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffff800010d28564)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffff800010d35290)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38f5c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (c0dcc528)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (c0e2c140)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c0e2d630)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (c0e3721c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (c0e3bb2c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (c000000000ddb3cc)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (c000000000e57fb4)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c000000000e5990c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (c000000000e67044)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c41c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffe000816ac2)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffe000868fa4)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffe000869de6)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffe000872670)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087630a)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff819a6ea5)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a01b77)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a028d7)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a0bf1c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10120)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81960965)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819be937)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819bf697)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff819c8cdc)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccee0)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81a11745)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a6c5f7)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a6d357)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a7699c)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7aba0)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ping.c (ffffffff81a1c0b5)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a78c2f)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a79977)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/reassembly.c (ffffffff81a830d1)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a873e0)
Location: include/linux/ipv6.h:157
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
</details>
</li>
</ul>

## Differences
