# Function: <code>csum_tcpudp_magic</code>

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
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8173942b)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e083)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81783165)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81786598)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8178b38c)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/inet_lro.c (ffffffff817abbac)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff817ac3c2)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum
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
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817a56df)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb4d3)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff817f06fc)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff817f3aa6)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff817f8491)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/netfilter.c (ffffffff8181970f)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817d414f)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181be43)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8182146c)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81824896)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81829341)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/netfilter.c (ffffffff8184afcf)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817f3498)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c622)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8184214c)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff818455e2)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8184ab05)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/netfilter.c (ffffffff8186ea50)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8186e888)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbd52)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a2c)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff818c5037)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff818ca7a5)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/netfilter.c (ffffffff818ef412)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff818bfa1e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/route.c (ffffffff818e7215)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911755)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81917702)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff8191ab01)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819202fb)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/netfilter.c (ffffffff81945dec)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff818e883e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff8190e879)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff8191411d)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193ff45)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e3f)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff819492c1)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8194f00e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81938050)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819703d3)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819764f3)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4455)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa475)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff819ad8e8)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819b37fe)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8196af10)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819a6dc3)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819acf03)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db075)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1145)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff819e4598)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819ea52e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81a3ec74)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81a9013b)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a923de)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac6005)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace725)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81ad1f80)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8204)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81a41a14)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81a9a00b)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a9c27e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1c85)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada75a)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81ade0c0)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae48a4)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81a264d7)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81a36347)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81a852ed)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a8728d)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcf45)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac57da)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81ac90d3)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81acfaea)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81adb252)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81aec025)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81b3f9dd)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81b41a4d)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79dd5)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81b83fea)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81b87961)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e50a)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81c5c75a)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81c6e9c7)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81ccc1f3)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81cd3914)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09c15)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81d147a9)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81d187d7)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f72a)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81e12e4a)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e266f7)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81e8c0c3)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81e93b2d)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecf2d5)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda8d9)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81edf137)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee690a)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81e86774)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e9bc98)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81eea108)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81ef2330)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2df95)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399b9)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81f3e575)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81f4614a)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff81f48781)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81f5e3f8)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/netfilter/utils.c (ffffffff81fadeb8)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81fb6495)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2b45)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffaa9)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff82004815)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8200c28a)
Location: arch/x86/include/asm/checksum_64.h:112
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
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
In net/core/skbuff.c (ffff800010bb8e30)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffff800010c116a8)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffff800010c567a8)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffff800010c5cf6c)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e43c)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffff800010c95188)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffff800010c99014)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffff800010ca0104)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/arm/include/asm/checksum.h:125
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (c0d29424)
Location: arch/arm/include/asm/checksum.h:125
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (c0d65ff4)
Location: arch/arm/include/asm/checksum.h:125
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c0d6c6fc)
Location: arch/arm/include/asm/checksum.h:125
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (c0d998a8)
Location: arch/arm/include/asm/checksum.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c0da38c8)
Location: arch/arm/include/asm/checksum.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (c0da7228)
Location: arch/arm/include/asm/checksum.h:125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c0dad040)
Location: arch/arm/include/asm/checksum.h:125
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/powerpc/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (c000000000cfe418)
Location: arch/powerpc/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (c000000000d572ec)
Location: arch/powerpc/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c000000000d5f628)
Location: arch/powerpc/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97a90)
Location: arch/powerpc/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c000000000da6104)
Location: arch/powerpc/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (c000000000daa9dc)
Location: arch/powerpc/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c000000000db2b74)
Location: arch/powerpc/include/asm/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
In net/core/skbuff.c (ffffffe0007484ca)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffe00078d8cc)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffe0007c0810)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffe0007c5d04)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee81e)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f439e)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffe0007f8abe)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc842)
Location: include/asm-generic/checksum.h:75
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8190aee0)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81946c33)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff8194cd73)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197aee5)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81980fb5)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff81984408)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8198a39e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff818c4c7b)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81900723)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81906863)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819349a5)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aa75)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff8193dec8)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81943e5e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8195bf10)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff81997dc3)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819b7543)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e56b5)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb785)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff819eebd8)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819f4b6e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
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
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8197e2f0)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (ffffffff819baaa3)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819c0dd2)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef365)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5635)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/udp.c (ffffffff819f8d48)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819fed3e)
Location: arch/x86/include/asm/checksum_64.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
</details>
</li>
</ul>

## Differences
