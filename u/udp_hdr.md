# Function: <code>udp_hdr</code>

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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/netpoll.c (ffffffff817393e3)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81786561)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8178b059)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff817b0004)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff817e1d61)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818000d4)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/udp_offload.c (ffffffff818016cc)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/skbuff.c (ffffffff8177150f)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a569b)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff817f7314)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff817f8994)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cf34)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff818501d1)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81866a34)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871791)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/skbuff.c (ffffffff8179e62f)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/netpoll.c (ffffffff817d410b)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81828234)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81829870)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e7f4)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81881fd1)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81899134)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5cf1)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bc27d)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/netpoll.c (ffffffff817f3450)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81849524)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8184a89d)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff818722c4)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff818aa9a1)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff818bf355)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc751)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/skbuff.c (ffffffff8183694d)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/netpoll.c (ffffffff8186e840)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff818c8fe4)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff818ca51e)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2ca4)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff8192d4c1)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff819424af)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819514f0)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/skbuff.c (ffffffff81880a5d)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/netpoll.c (ffffffff818bf9d5)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff8191f136)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81920da1)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff819495d6)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81985f12)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff8199b2dc)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aaa85)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/skbuff.c (ffffffff818a190d)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/core/netpoll.c (ffffffff818e87f5)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff8194dd90)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8194ef61)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b2a0)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff819bc7dc)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff819d1c16)
Location: include/linux/udp.h:25
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e1575)
Location: include/linux/udp.h:25
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff818ec2fd)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (ffffffff81938007)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff819b256f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819b374c)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e47d0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81a2b31f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81a409ce)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a50335)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff8191e42d)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (ffffffff8196aec7)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff819e930f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819ea47c)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b7e0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81a61e7f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81a7764e)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a86f55)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f1a69)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/netpoll.c (ffffffff81a3ec2b)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81ad7ade)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad7f7e)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c880)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81b5a69c)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81b7197e)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78c20)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82205)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f1709)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/netpoll.c (ffffffff81a419cb)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81ae412e)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae47e9)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1abb0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81b68d9c)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81b80622)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87ba0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91902)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d6999)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/netpoll.c (ffffffff81a2648b)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81acf31e)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81acfa0d)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0886d)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81b53f20)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f244)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7685d)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80b50)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a86fe9)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/netpoll.c (ffffffff81adb1f4)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81b8dd3e)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e42d)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb76d)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81c1d3cf)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81c37304)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c412dd)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cb70)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bfc7a0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/netpoll.c (ffffffff81c5c707)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81d1ee65)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f661)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d6122b)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81db9a20)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81dd4eb2)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfa6b)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81decfc2)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (ffffffff816a5f3f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81dab6b0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/netpoll.c (ffffffff81e12df7)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81ee5f75)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6831)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bb2b)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81f89ab0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81fa65b8)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1d5b)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0dc2)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (ffffffff816de91f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81e1b174)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/netpoll.c (ffffffff81e86720)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81f45775)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81f46071)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b56b)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81fe935e)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff82006e02)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012469)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021d52)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (ffffffff8171b4ef)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81ed8734)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/netpoll.c (ffffffff81f4872d)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff8200b8c5)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8200c1b1)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052c72)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff820b5e70)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff820d5c62)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0e82)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f0e72)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb8b9c)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (ffff800010c11528)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffff800010c9ec10)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffff800010ca0044)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7a44)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffff800010d26e88)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffff800010d40cb8)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffff800010d536b8)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (c0cd5620)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (c0d293d8)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (c0dabe70)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c0dacfc0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (c0de1550)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (c0e2bf54)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (c0e436a8)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (c0e53f70)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (c000000000c90f08)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (c000000000cfe214)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (c000000000db1460)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c000000000db2ae0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (c000000000df7998)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (c000000000e57c74)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (c000000000e75430)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (c000000000e8be48)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffe000748266)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (ffffffe00078d6e2)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffe0007fb76c)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc7a8)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffe0008280e4)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffe000868df0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffe00087c4ce)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b3c8)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff818be42d)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (ffffffff8190ae97)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff8198917f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8198a2ec)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bae70)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81a0150f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81a16cde)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a265e5)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In drivers/net/vxlan.c (ffffffff81772703)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff8187836d)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (ffffffff818c4c32)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff81942c3f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81943dac)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/udp_tunnel.c (ffffffff819720d3)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_tunnel.c:udp_tun_rx_dst
  - net/ipv4/udp_tunnel.c:udp_tun_rx_dst
  - net/ipv4/udp_tunnel.c:udp_tun_rx_dst
  - net/ipv4/udp_tunnel.c:udp_tunnel_xmit_skb
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977c60)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff819be2cf)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff819d3a9e)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e33a5)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5a46)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff8190f42d)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (ffffffff8195bec7)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff819f394f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819f4abc)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a258f0)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81a6bf8f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81a8175e)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a92195)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In security/lsm_audit.c (0)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/skbuff.c (ffffffff8193055d)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/core/netpoll.c (ffffffff8197e2a7)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/udp.c (ffffffff819fdb0f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819fec97)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30d80)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv6/udp.c (ffffffff81a7859f)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e05e)
Location: include/linux/udp.h:21
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e245)
Location: include/linux/udp.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
</details>
</li>
</ul>

## Differences
