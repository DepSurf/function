# Function: <code>csum_block_add</code>

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
In lib/iov_iter.c (ffffffff813fd1fd)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
```
In net/core/skbuff.c (ffffffff81704d71)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_block_add_ext
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
```
```
In net/core/datagram.c (ffffffff8170da00)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/ipv4/ip_output.c (ffffffff8175c421)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81769f3d)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff817787c7)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/raw.c (ffffffff81784720)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8178dd8d)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/inet_lro.c (ffffffff817ac049)
Location: include/net/checksum.h:88
Inline: True
```
```
In net/ipv6/raw.c (ffffffff817e5360)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff817e7182)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
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
In lib/iov_iter.c (ffffffff8144429f)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81770bbd)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff81775058)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff8177fe84)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8179dadf)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff817c86c1)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff817d6a7e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff817e5810)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/raw.c (ffffffff817f1cda)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff817fb37d)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81835b2b)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8185364a)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81855562)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff8185d29e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In lib/iov_iter.c (ffffffff81462493)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8179dc3e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff817a234d)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff817ad553)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cc53f)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff817f8251)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81806b44)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff81815c84)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/raw.c (ffffffff81822afa)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8182c22d)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff8186765b)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8188535a)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818872d2)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff8188f207)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818950ac)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a42cb)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In lib/iov_iter.c (ffffffff81468189)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff817bbadf)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff817bfbde)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff817cc103)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817eb104)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff81818651)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818270f2)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff8183602e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/raw.c (ffffffff818437ce)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8184d6ed)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff8188bd89)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff818ab79e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818ad882)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff818b5768)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb3d2)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cac35)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In lib/iov_iter.c (ffffffff8149441f)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81834b93)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff8183978e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff818457c9)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81866f54)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff818977b1)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818a530b)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff818b55ee)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/raw.c (ffffffff818c31ae)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff818cd42d)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff8190d074)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8192e33e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81930512)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff819384de)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e3e8)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948f02)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e3bb)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194f98e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff814c985f)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8187f95b)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/datagram.c (ffffffff81883eca)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff8188eda9)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b5e58)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff818ebac1)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818fae26)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff81918cb1)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8192380d)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81964444)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81986fe1)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819891a2)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81991448)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8199731b)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1f7f)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7352)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a8961)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff814de84d)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8189fbb3)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (ffffffff818afe49)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818d730c)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_output.c (ffffffff81918e71)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81928d8e)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff81947481)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff819525fd)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81999ccd)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819bd901)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819bfad2)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff819c7b92)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cdbfa)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8be0)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819ddea9)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819df495)
Location: include/net/checksum.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff8150a3f2)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff818eca2d)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff818fbc9f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81924dfe)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81943a5b)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffffffff8197af81)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198bd13)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819abb0f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff819b6ebd)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81a05c37)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a2c3df)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a2e772)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81a35ee1)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c205)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a47441)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c9fa)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e00e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff8152852c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8191eb59)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8192e26f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8195722e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81978a4c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffffffff819b18f1)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c25f8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819e27df)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff819edbbd)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c79f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a62f3f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a652c2)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81a6ca01)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a72e85)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7dff1)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a835ca)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a84c38)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff815883b9)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
```
```
In net/core/skbuff.c (ffffffff819f142c)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a023fc)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2f8a9)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a4d578)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffffffff81a9b9d1)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81aac621)
Location: include/net/checksum.h:78
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81acfddf)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81adb9bd)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81b31e65)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b5b7ff)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5dc22)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81b65c01)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d35b)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78b4b)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e3e5)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fcea)
Location: include/net/checksum.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff815a806d)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
```
```
In net/core/skbuff.c (ffffffff819f13c3)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a02bfc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a31bb9)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a5323d)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81a6f4ed)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81aa582f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ab3f74)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81adbd59)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81ae848a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81b40a65)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b6a029)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6c3ef)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81b74372)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81b7be09)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87aca)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d3fc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f01a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff815b34f8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff819d6665)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff819e720f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a18a25)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a38a6b)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81a57dc9)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81a908ef)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81a9f0e4)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ac6b99)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81ad371a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e2fb)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81b58319)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5a73f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81b62dd2)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a8ee)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7677a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c2a5)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e050)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff816194b4)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81a86cb5)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a97bbf)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81ac9f15)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81aee94b)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81b10d90)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81b4b96f)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81b5a234)
Location: include/net/checksum.h:92
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b853d9)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81b9236a)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81bf45f1)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81c1f6c9)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c2200f)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81c2a867)
Location: include/net/checksum.h:92
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c3274e)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41205)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c471a5)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c48ec0)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c073)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/mptcp/protocol.c (ffffffff81c77917)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81c8098c)
Location: include/net/checksum.h:92
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffffffff816e685e)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81bfab3b)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81c45b30)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81c71b4a)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81c97f2b)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81cd902f)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ce8586)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81d1611f)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81d23c7a)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/raw.c (ffffffff81dbc2bf)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81dbecef)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81dc7d45)
Location: include/net/checksum.h:94
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfc63)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf9a2)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de64e9)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec020)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/mptcp/protocol.c (ffffffff81e1cb87)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81e25bae)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffffffff817d61a6)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81da99cc)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81df9d90)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81e29c3a)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81e53ebe)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81e9963f)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81eabed6)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81edc64f)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81eeb20a)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff81f0bae6)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (ffffffff81f8c79f)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81f8f27f)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81f98ab5)
Location: include/net/checksum.h:94
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0fa4)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1c6c)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb91cf)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfc6e)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/mptcp/protocol.c (ffffffff81ff4017)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81ffd83e)
Location: include/net/checksum.h:94
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffffffff81813948)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81e14cd1)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81e6bb80)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81e9f259)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81eaf738)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81ef7f3f)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81f0a696)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81f3b7a6)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81f4ab2a)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff81f6b6b6)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (ffffffff81fed026)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81fefa7f)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81ff9495)
Location: include/net/checksum.h:96
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff82001967)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012354)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201992f)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201d30f)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020bfe)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/mptcp/protocol.c (ffffffff82070627)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff82079b0e)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In net/core/skbuff.c (ffffffff81ece250)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/datagram.c (ffffffff81edd67e)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In net/core/filter.c (ffffffff81f2ac60)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81f619c6)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81f721b8)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81fbbf8f)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81fce695)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff820018c6)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff82010c3a)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff8203171a)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (ffffffff820bac26)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff820bd64f)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff820c7113)
Location: include/net/checksum.h:96
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820d076a)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e14c4)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e88ff)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820ec2ef)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efd2e)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/mptcp/protocol.c (ffffffff82144587)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff8214ef6e)
Location: include/net/checksum.h:96
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffff800010632bd4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffff800010bb934c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (ffff800010bcd71c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010c009bc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffff800010c1f674)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffff800010c61e08)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c752f0)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffff800010c96658)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffff800010ca36e4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffff800010cfdac8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffff800010d28188)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2b284)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffff800010d353dc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffff800010d3b9b4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffff800010d493a8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f3cc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d50d24)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (c07d8d24)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (c0cd5dfc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (c0ce7974)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d126a8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (c0d37248)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (c0d71820)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c0d839d0)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (c0da4cb4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (c0db03d4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (c0e052f0)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c0e2cbe4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e2f0fc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (c0e374c8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (c0e3e120)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (c0e4a77c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c0e5011c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e51878)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (c0000000007d5fb4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_memcpy
```
```
In net/core/skbuff.c (c000000000c918f4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (c000000000ca7524)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000ce3b18)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (c000000000d115ec)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (c000000000d65934)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d7c900)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (c000000000da804c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (c000000000db6ed0)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (c000000000e25bcc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (c000000000e5940c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5c608)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (c000000000e67218)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (c000000000e6f23c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e93c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86c58)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e88b5c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffe000461034)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffe0007488f0)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (ffffffe000756e5e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe00077a6e0)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffe000798d02)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffffffe0007ca30e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d85f6)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffe0007f57d4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffe0007ff570)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffe000847f56)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffe000869948)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086b6b4)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffe00087275c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffe0008782aa)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffe00088289a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887ed2)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe000889062)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff81520b0c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff818beb59)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff818ce26f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818f71fe)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff819188bc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffffffff81951761)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81962468)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff8198264f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8198d95d)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff819dbe2f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a025cf)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a04952)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81a0c091)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a12515)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d681)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22c5a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a242c8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff81510dfc)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In drivers/net/vxlan.c (ffffffff81772efe)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff81878a99)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8188838f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b102e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff818d266c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffffffff8190b251)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191bf58)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff8193c10f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff8194741d)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967f8a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81998bef)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff819bf38f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c1712)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff819c8e51)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff819cf2d5)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da441)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfa1a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e1088)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff8151cb9c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff8190fb59)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8191f26f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8194822e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81969a4c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffffffff819bbf31)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819ccc38)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819ece1f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff819f81fd)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81a468af)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a6d04f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a6f3d2)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81a76b11)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cf95)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a88101)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d6da)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ed48)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In lib/iov_iter.c (ffffffff815363f7)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81930c89)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81940fcf)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81969b3e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff8198be2c)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_output.c (ffffffff819c5841)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d67c8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819f6d0f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81a024fd)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (ffffffff81a525df)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/raw.c (ffffffff81a7966f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7ba02)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (ffffffff81a83259)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a897e5)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94d32)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a3ca)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bab8)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
</details>
</li>
</ul>

## Differences
