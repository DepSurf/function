# Function: <code>skb_has_frag_list</code>

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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2782
Inline: True
```
```
In net/core/skbuff.c (ffffffff81708332)
Location: include/linux/skbuff.h:2782
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2782
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738e9a)
Location: include/linux/skbuff.h:2782
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/skbuff.h:2782
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175c79f)
Location: include/linux/skbuff.h:2782
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2782
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8178653d)
Location: include/linux/skbuff.h:2782
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2782
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c7392)
Location: include/linux/skbuff.h:2782
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/skbuff.h:2782
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2782
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81803780)
Location: include/linux/skbuff.h:2782
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2975
Inline: True
```
```
In net/core/skbuff.c (ffffffff8176f040)
Location: include/linux/skbuff.h:2975
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2975
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a515a)
Location: include/linux/skbuff.h:2975
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/skbuff.h:2975
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817c9576)
Location: include/linux/skbuff.h:2975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2975
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f373d)
Location: include/linux/skbuff.h:2975
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2975
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81834486)
Location: include/linux/skbuff.h:2975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/skbuff.h:2975
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:2975
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818749c0)
Location: include/linux/skbuff.h:2975
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:3028
Inline: True
```
```
In net/core/skbuff.c (ffffffff8179c530)
Location: include/linux/skbuff.h:3028
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3028
Inline: True
```
```
In net/core/netpoll.c (ffffffff817d3bca)
Location: include/linux/skbuff.h:3028
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/skbuff.h:3028
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f9502)
Location: include/linux/skbuff.h:3028
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:3028
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8182452d)
Location: include/linux/skbuff.h:3028
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:3028
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81865ee6)
Location: include/linux/skbuff.h:3028
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/skbuff.h:3028
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:3028
Inline: True
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:3093
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bd468)
Location: include/linux/skbuff.h:3093
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3093
Inline: True
```
```
In net/core/netpoll.c (ffffffff817f2f18)
Location: include/linux/skbuff.h:3093
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/skbuff.h:3093
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81819956)
Location: include/linux/skbuff.h:3093
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:3093
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8184524d)
Location: include/linux/skbuff.h:3093
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:3093
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8188a694)
Location: include/linux/skbuff.h:3093
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/skbuff.h:3093
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/skbuff.h:3093
Inline: True
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:3210
Inline: True
```
```
In net/core/skbuff.c (ffffffff8183583b)
Location: include/linux/skbuff.h:3210
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3210
Inline: True
```
```
In net/core/netpoll.c (ffffffff8186e314)
Location: include/linux/skbuff.h:3210
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/skbuff.h:3210
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81897f86)
Location: include/linux/skbuff.h:3210
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:3210
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c4cdd)
Location: include/linux/skbuff.h:3210
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv6/ip6_output.c (ffffffff8190b894)
Location: include/linux/skbuff.h:3210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/skbuff.h:3210
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff81748048)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8187fbbf)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/dev.c (ffffffff81895c1f)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff818bf4a4)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_fragment.c (ffffffff818e97d3)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff818ec298)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff818f853c)
Location: include/linux/skbuff.h:3221
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81917aca)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8191a9b7)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv6/ip6_output.c (ffffffff81962c6c)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff81990ffb)
Location: include/linux/skbuff.h:3221
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In drivers/net/xen-netfront.c (ffffffff8176c115)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818a0830)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/dev.c (ffffffff818b798f)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff818e82c3)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_fragment.c (ffffffff81916880)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81919435)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff819250f8)
Location: include/linux/skbuff.h:3298
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819461fe)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81949184)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv6/ip6_output.c (ffffffff81997c5e)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff819c7754)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/strparser/strparser.c (ffffffff819eb5d5)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff817a9f28)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818eb274)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81903792)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81937afd)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff8197b7ab)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81988631)
Location: include/linux/skbuff.h:3385
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa844)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819ad7dd)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf3ae)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81a03d8c)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81a4861d)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81a5a7d3)
Location: include/linux/skbuff.h:3385
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff817cd990)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8191d3d4)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81936545)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff8196a9bd)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff819b1e6a)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff819bfb0a)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1488)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819e448d)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05f40)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a972)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81a7f1de)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81a91423)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff8189953a)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819efb19)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81a0b08d)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81a3e5c0)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81a9c6ff)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81aa9bf7)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81aceb54)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ad1cbd)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5650)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ff47)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81b79e97)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81b8c893)
Location: include/linux/skbuff.h:3474
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff818a7a5d)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819ef7c2)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81a0c2e6)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81a41360)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81aa6565)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81ab7027)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81adab74)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81adddfd)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02410)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e9e7)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81b88de7)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81b9c4e3)
Location: include/linux/skbuff.h:3500
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff8188b2f2)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819d7f7a)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff819f2481)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81a25fbe)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81a916e5)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81aa2231)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac5bd8)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ac8e0d)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedd20)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b7c2)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81b77c07)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81b8b5a3)
Location: include/linux/skbuff.h:3564
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff8191db65)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81a87dca)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81aa4351)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81adad2e)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81b4cab5)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81b59037)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84332)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81b8769d)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae0d0)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1875)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81c42727)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81c57843)
Location: include/linux/skbuff.h:3601
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff81a752c9)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81bfd208)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81c19051)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/gro.c (ffffffff81c54341)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/netpoll.c (ffffffff81c5b513)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81cda1d0)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81ce7147)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14af1)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81d184ed)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41203)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a23a)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81de11d6)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81df8e7f)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff81c06d1a)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81dac17e)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81dca027)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/gro.c (ffffffff81e0991e)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/netpoll.c (ffffffff81e117dd)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81e9a990)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81eaa857)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_offload.c (ffffffff81edac31)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81edee3d)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7636)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09fb3)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81f581ca)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/udp_offload.c (ffffffff81fa659e)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81fb3636)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81fcd46f)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff81c6c41b)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1bfe7)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81e3ab9f)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gro.c (ffffffff81e7c0f5)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/gso.c (ffffffff81e7d809)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81e850ed)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81ef930b)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81f09047)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_offload.c (ffffffff81f39d13)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81f3e27d)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81f46483)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69ac2)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7da2)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff82013d1c)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff82048d96)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff81d20dce)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81ed96e7)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81ef8f43)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gro.c (ffffffff81f3c445)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/gso.c (ffffffff81f3e786)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81f470dd)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81fbd228)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81fcd4a7)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffe03)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8200451d)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8200c5c3)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff82030142)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff820853df)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff820e2e76)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff8211b116)
Location: include/linux/skbuff.h:3933
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffff800010a094f4)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffff800010bb7dc0)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffff800010bd4c24)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffff800010c10d24)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffff800010c63b64)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffff800010c73c0c)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffff800010c954dc)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffff800010c98ec4)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffff800010cbeef0)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffff800010cfbabc)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffff800010d4a470)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffff800010d5efb8)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In net/core/skbuff.c (c0cd49b0)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (c0cef154)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (c0d27ff8)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (c0d72094)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (c0d82230)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (c0da3c34)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c0da6e9c)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (c0dca674)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (c0e02a3c)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (c0e4ba78)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (c0e5ebb8)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In net/core/skbuff.c (c000000000c8fbd8)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (c000000000cb3d30)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (c000000000cfc624)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (c000000000d65cf4)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (c000000000d79cec)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (c000000000da6560)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c000000000daa840)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (c000000000dd970c)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (c000000000e23134)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (c000000000e804e4)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (c000000000e99a60)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In net/core/skbuff.c (ffffffe000747736)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffe00075e8f8)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffe00078c6ea)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffe0007ca3fe)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffe0007d5ad4)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f47b4)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffe0007f6ee6)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffe000814ca2)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffe0008463a2)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffe00088396a)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffe000894770)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff817925b0)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818bd3d4)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff818d6515)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff8190a98d)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff81951cda)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff8195f97a)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819812f8)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819842fd)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5ce0)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff819da002)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81a1e86e)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81a30ab3)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In net/core/skbuff.c (ffffffff81877314)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81890355)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff818c3db6)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff8190b7ca)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff8191946a)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8193adb8)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff8193ddbd)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f7a0)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81996dc2)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff819db62e)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff819edca3)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff817c2810)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8190e3d4)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81927545)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff8195b9bd)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff819bc4aa)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff819ca14a)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebac8)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819eeacd)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10580)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81a44a82)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81a892ee)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81a9c663)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In drivers/net/xen-netfront.c (ffffffff817dcad0)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8192f504)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffffffff81948bb3)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff8197dda9)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/ipv4/ip_output.c (ffffffff819c5dba)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff819d3cc8)
Location: include/linux/skbuff.h:3450
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5978)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff819f8c3d)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1add0)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81a50742)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81a95f4e)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/strparser/strparser.c (ffffffff81aa8843)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
</details>
</li>
</ul>

## Differences
