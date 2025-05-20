# Function: <code>inet_iif</code>

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
In net/ipv4/route.c (ffffffff81757792)
Location: include/net/route.h:323
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761e73)
Location: include/net/route.h:323
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ce7e)
Location: include/net/route.h:323
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8178a34e)
Location: include/net/route.h:323
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8178e63f)
Location: include/net/route.h:323
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
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
In net/ipv4/route.c (ffffffff817c3a38)
Location: include/net/route.h:326
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebbd8)
Location: include/net/route.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff817f776d)
Location: include/net/route.h:326
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff817fbc53)
Location: include/net/route.h:326
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
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
In net/ipv4/route.c (ffffffff817f3558)
Location: include/net/route.h:317
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdf58)
Location: include/net/route.h:317
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c54d)
Location: include/net/route.h:317
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff81828679)
Location: include/net/route.h:317
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff8182cba3)
Location: include/net/route.h:317
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
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
In net/ipv4/route.c (ffffffff81811199)
Location: include/net/route.h:325
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e360)
Location: include/net/route.h:325
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cdc6)
Location: include/net/route.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff81849941)
Location: include/net/route.h:325
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff8184e003)
Location: include/net/route.h:325
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
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
In net/ipv4/route.c (ffffffff81890779)
Location: include/net/route.h:328
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189d270)
Location: include/net/route.h:328
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc4f1)
Location: include/net/route.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff818c9405)
Location: include/net/route.h:328
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff818cdd26)
Location: include/net/route.h:328
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
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
In net/ipv4/route.c (ffffffff818e76d2)
Location: include/net/route.h:331
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f1723)
Location: include/net/route.h:331
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911ee8)
Location: include/net/route.h:331
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff8191f52e)
Location: include/net/route.h:331
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff81924490)
Location: include/net/route.h:331
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
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
In net/ipv4/route.c (ffffffff81914582)
Location: include/net/route.h:330
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f283)
Location: include/net/route.h:330
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819406b1)
Location: include/net/route.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff8194e1c2)
Location: include/net/route.h:330
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff8195306b)
Location: include/net/route.h:330
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca4b3)
Location: include/net/route.h:330
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81976a4d)
Location: include/net/route.h:336
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981bcb)
Location: include/net/route.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4bec)
Location: include/net/route.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819ad29d)
Location: include/net/route.h:336
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b2a33)
Location: include/net/route.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff819b7b9f)
Location: include/net/route.h:336
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a390bf)
Location: include/net/route.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff819ad42c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b840b)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db8ec)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819e3f5d)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e97d3)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff819ee89f)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6fc2f)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81a971e5)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2d26)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac89c0)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81ad1630)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad777c)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff81adc627)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69b71)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81c324bd)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aad036)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4960)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81add6b0)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae3dcc)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5b36)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81ae933c)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78643)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81c247a6)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98288)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfa16)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81ac8780)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81acefb9)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0e26)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81ad4967)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6758b)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81d39ea9)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b53711)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d582)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81b86fe0)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8d993)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f843)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81b936b2)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81bb0667)
Location: include/net/route.h:347
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f1b2)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81f065f1)
Location: include/net/route.h:360
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce11c3)
Location: include/net/route.h:360
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d4e5)
Location: include/net/route.h:360
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81d17c8a)
Location: include/net/route.h:360
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1eade)
Location: include/net/route.h:360
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d20b3d)
Location: include/net/route.h:360
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81d24882)
Location: include/net/route.h:360
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81d43b61)
Location: include/net/route.h:360
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc5cc)
Location: include/net/route.h:360
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81e90cfc)
Location: include/net/route.h:355
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea15d3)
Location: include/net/route.h:355
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2f1f)
Location: include/net/route.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81ede50a)
Location: include/net/route.h:355
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee5c25)
Location: include/net/route.h:355
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7dc2)
Location: include/net/route.h:355
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81eec062)
Location: include/net/route.h:355
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81f0cce9)
Location: include/net/route.h:355
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d6e3)
Location: include/net/route.h:355
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81eef4ac)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81effdcf)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31c1d)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81f3d860)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81f45422)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f4762a)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff81f4be50)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81f6c960)
Location: include/net/route.h:347
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe164)
Location: include/net/route.h:347
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81fb360c)
Location: include/net/route.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3f61)
Location: include/net/route.h:341
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7c6b)
Location: include/net/route.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_ao_sign_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/raw.c (ffffffff82003970)
Location: include/net/route.h:341
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff8200b4cf)
Location: include/net/route.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200d76a)
Location: include/net/route.h:341
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff82011f60)
Location: include/net/route.h:341
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff820330b0)
Location: include/net/route.h:341
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccf7f)
Location: include/net/route.h:341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffff800010c59fa8)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffff800010c697d4)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ec98)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffff800010c98930)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9f0c0)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffff800010ca4b24)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38544)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (c0d6962c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (c0d789f8)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (c0d9dbf0)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (c0da6798)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0dac2a0)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (c0db0c68)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (c0e3b854)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (c000000000d5b99c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e520)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d7f8)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (c000000000daa0dc)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db19ac)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (c000000000db7ea4)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6bd34)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffe0007c35f4)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf62a)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eef4a)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffe0007f6a8e)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fba8a)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffe0007ffdf2)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008756a8)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff8194d29c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195827b)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b75c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81983dcd)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989643)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff8198e63f)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f2bf)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff81906d8c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911d6b)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193521c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff8193d88d)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81943103)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff819480ff)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc07f)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff819b7a6c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2a4b)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5f2c)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819ee59d)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f3e13)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff819f8edf)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a79d3f)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/route.c (ffffffff819c12dc)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc44b)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efbec)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819f85fd)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fdfd3)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/icmp.c (ffffffff81a0310f)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86532)
Location: include/net/route.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
</details>
</li>
</ul>

## Differences
