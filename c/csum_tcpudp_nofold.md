# Function: <code>csum_tcpudp_nofold</code>

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
In net/core/skbuff.c (ffffffff817097d6)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8173942b)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177afa4)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81783165)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81786598)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8178b38c)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/inet_lro.c (ffffffff817ababa)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff817ac3c2)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
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
In net/core/skbuff.c (ffffffff81771793)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817a56df)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb878)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff817f06fc)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff817f7daa)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff817f8491)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/netfilter.c (ffffffff818197e1)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
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
In net/core/skbuff.c (ffffffff8179e853)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817d414f)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c1e8)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8182146c)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81828c72)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81829341)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/netfilter.c (ffffffff8184b0a1)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
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
In net/core/skbuff.c (ffffffff817bc49b)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817f3498)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c9c1)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8184214c)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81849fc5)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8184ab05)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/netfilter.c (ffffffff8186eb21)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
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
In net/core/skbuff.c (ffffffff81836b6b)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8186e888)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc115)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a2c)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff818c947c)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff818ca7a5)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/netfilter.c (ffffffff818ef4e1)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
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
In net/core/skbuff.c (ffffffff81880c1a)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff818bfa1e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/route.c (ffffffff818e7215)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911b29)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81917702)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8191f1e0)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819202fb)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/netfilter.c (ffffffff81945e8e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum
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
In net/core/skbuff.c (ffffffff818a1aca)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff818e883e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff8190eb1b)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff8191411d)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819402fa)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e3f)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff8194de39)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8194f00e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/skbuff.c (ffffffff818ec592)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81938050)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819706ee)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819764f3)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4831)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa475)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819b2624)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819b37fe)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/skbuff.c (ffffffff8191e6c2)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8196af10)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819a70de)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819acf03)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db531)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1145)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819e93c4)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819ea52e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/skbuff.c (ffffffff819f1e7b)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81a3ec74)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81a9043e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a923de)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac85d6)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace725)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ad6b93)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8204)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
In net/core/skbuff.c (ffffffff819f1b1b)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81a41a14)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81a9a30e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a9c27e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4576)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada75a)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ae3173)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae48a4)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
In net/core/skbuff.c (ffffffff819d6d9b)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81a264d7)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81a36347)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81a855f4)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a8728d)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf63c)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac57da)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ace076)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81acfaea)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
In net/core/skbuff.c (ffffffff81a873eb)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81adb252)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81aec025)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81b3fce4)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81b41a4d)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d184)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81b83fea)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81b8ca36)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e50a)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
In net/core/skbuff.c (ffffffff81bfcb92)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81c5c75a)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81c6e9c7)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81ccc523)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81cd3914)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d0f2)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81d147a9)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81d1d0f6)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f72a)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
In net/core/skbuff.c (ffffffff81dabac2)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81e12e4a)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e266f7)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81e8c423)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81e93b2d)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2b6c)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda8d9)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81ee4206)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee690a)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
In net/core/skbuff.c (ffffffff81e1b5ca)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81e86774)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e9bc98)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81eea42c)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81ef2330)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31853)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399b9)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81f43a77)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81f4614a)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
In net/core/skbuff.c (ffffffff81ed8b8a)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81f48781)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81f5e3f8)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81fae1dc)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81fb6495)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7a4e)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffaa9)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff820099e7)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8200c28a)
Location: arch/x86/include/asm/checksum_64.h:87
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
__wsum csum_tcpudp_nofold(__be32 saddr, __be32 daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/checksum.c (ffff8000106622a0)
Location: lib/checksum.c:189
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffff8000106622a0-ffff8000106622cc: csum_tcpudp_nofold (STB_GLOBAL)
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
In net/core/skbuff.c (c0cd593c)
Location: arch/arm/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (c0d29424)
Location: arch/arm/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (c0d66304)
Location: arch/arm/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c0d6c6fc)
Location: arch/arm/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (c0d9d854)
Location: arch/arm/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c0da38c8)
Location: arch/arm/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (c0dabf14)
Location: arch/arm/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c0dad040)
Location: arch/arm/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/skbuff.c (c000000000c912ac)
Location: arch/powerpc/include/asm/checksum.h:57
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (c000000000cfe418)
Location: arch/powerpc/include/asm/checksum.h:57
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (c000000000d57790)
Location: arch/powerpc/include/asm/checksum.h:57
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c000000000d5f628)
Location: arch/powerpc/include/asm/checksum.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d330)
Location: arch/powerpc/include/asm/checksum.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c000000000da6104)
Location: arch/powerpc/include/asm/checksum.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (c000000000db1500)
Location: arch/powerpc/include/asm/checksum.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c000000000db2b74)
Location: arch/powerpc/include/asm/checksum.h:57
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__wsum csum_tcpudp_nofold(__be32 saddr, __be32 daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/checksum.c (ffffffe00048eba8)
Location: lib/checksum.c:189
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffe00048eba8-ffffffe00048ebe6: csum_tcpudp_nofold (STB_GLOBAL)
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
In net/core/skbuff.c (ffffffff818be6c2)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8190aee0)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81946f4e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff8194cd73)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b3a1)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81980fb5)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81989234)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8198a39e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/skbuff.c (ffffffff81878602)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff818c4c7b)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81900a3e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81906863)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934e61)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aa75)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff81942cf4)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81943e5e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/skbuff.c (ffffffff8190f6c2)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8195bf10)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819980de)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819b7543)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5b71)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb785)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819f3a04)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819f4b6e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/skbuff.c (ffffffff819307f2)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8197e2f0)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819badbe)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819c0dd2)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef831)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5635)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp.c (ffffffff819fdbc4)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819fed3e)
Location: arch/x86/include/asm/checksum_64.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
