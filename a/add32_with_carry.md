# Function: <code>add32_with_carry</code>

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
In arch/x86/lib/csum-partial_64.c (ffffffff813f62e3)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
```
```
In lib/iov_iter.c (ffffffff813fd1fd)
Location: arch/x86/include/asm/checksum_64.h:182
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
In net/core/skbuff.c (ffffffff81704d8e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_block_add_ext
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/datagram.c (ffffffff8170d7f2)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff81717c84)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:__skb_gro_checksum_complete
```
```
In net/core/utils.c (ffffffff8172fdf7)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/core/filter.c (ffffffff817323ad)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff817400fb)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a2db)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175c442)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/ip_sockglue.c (ffffffff8175fb2d)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81769f75)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff817754ae)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e84a)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81783aed)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81784735)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81786580)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8178b546)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/icmp.c (ffffffff8178dcde)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff817976a3)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff817a4e3c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/inet_lro.c (ffffffff817abab5)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c64f3)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff817c88d0)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff817e1c0c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff817e5375)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e71a5)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817ee766)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f202e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/netfilter.c (ffffffff817fddea)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
```
In net/ipv6/ip6_checksum.c (ffffffff818003ac)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81800df3)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81801380)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818019ee)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff8180268a)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817b3f)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
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
In arch/x86/lib/csum-partial_64.c (ffffffff8143cf6e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In lib/iov_iter.c (ffffffff814442ae)
Location: arch/x86/include/asm/checksum_64.h:182
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
Location: arch/x86/include/asm/checksum_64.h:182
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
In net/core/datagram.c (ffffffff81774e50)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff817803a8)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff8179a54e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/core/filter.c (ffffffff8179dadf)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff817ace41)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_fragment.c (ffffffff817c670c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817cbad3)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cbdd6)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff817d6a8a)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff817e581c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebd49)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff817f10a6)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff817f1cde)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff817f781e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff817f8de2)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff817fca2c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81806067)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81812fad)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff818335e7)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81835b2b)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8185007c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81854a03)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8185711f)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff8185cfa3)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818608ed)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81866d4e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/netfilter.c (ffffffff8186d846)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871a60)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff8187258f)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872bc0)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff8187398c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818915fc)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In arch/x86/lib/csum-partial_64.c (ffffffff81459f0e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In lib/iov_iter.c (ffffffff814624a2)
Location: arch/x86/include/asm/checksum_64.h:182
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
Location: arch/x86/include/asm/checksum_64.h:182
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
In net/core/datagram.c (ffffffff817a2150)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff817adcf8)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff817c82ee)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/core/filter.c (ffffffff817cc53f)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff817dc491)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_fragment.c (ffffffff817f620c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817fb74e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fbacd)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81806b50)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff81815c90)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c6cd)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81821e36)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81822afe)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81828722)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81829cb2)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8182d991)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff818370e7)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff818444bd)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff81865077)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8186765b)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff81881e7c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81886735)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888f1f)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff8188eeff)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818928c7)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818950ac)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8189944e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/netfilter.c (ffffffff818a0646)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a42cb)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5fc0)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6b7f)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a71e0)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a800c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818c5f0c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff814681af)
Location: arch/x86/include/asm/checksum_64.h:182
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
Location: arch/x86/include/asm/checksum_64.h:182
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
In net/core/datagram.c (ffffffff817bf9b0)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff817cc858)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff817e6c3e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/core/filter.c (ffffffff817eb104)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff817fbbdf)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_fragment.c (ffffffff81816641)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8181bb17)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181beaa)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff818270fe)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff8183603a)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cf93)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81842abe)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff818437d2)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81849a33)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8184afde)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8184edf5)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff8185873d)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff81865d9f)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff81888828)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8188bd89)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff818a8680)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff818accb1)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af464)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff818b53aa)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8feb)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb3d2)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff818bf76d)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/netfilter.c (ffffffff818c6c8a)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cac35)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cca4a)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd645)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdc53)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce87c)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff818fba5e)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818fbadc)
Location: arch/x86/include/asm/checksum_64.h:182
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff81494440)
Location: arch/x86/include/asm/checksum_64.h:183
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
Location: arch/x86/include/asm/checksum_64.h:183
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
In net/core/datagram.c (ffffffff81839560)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff81845f28)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff81861b7e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff81866f54)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff818795a1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_fragment.c (ffffffff818957d7)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8189aa50)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189ade3)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff818a5317)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff818b55fa)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc701)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff818c241e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff818c31b2)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff818c9582)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff818cac3e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff818ceb7b)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff818d8613)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff818e5ed1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff8190ab6e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8190d074)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8192b130)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff8192f639)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8193217a)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81938120)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bf00)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e3e8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8194283d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948f02)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/netfilter.c (ffffffff8194a14a)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e3bb)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194f98e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81951836)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81952437)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952a53)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff8195372c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff819828ae)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8198292c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff814c987a)
Location: arch/x86/include/asm/checksum_64.h:183
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
Location: arch/x86/include/asm/checksum_64.h:183
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
In net/core/datagram.c (ffffffff81883c90)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff8188e478)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff818ad79c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff818b5e58)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff818caf31)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_fragment.c (ffffffff818e99c2)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff818eef14)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef3b4)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff818fae35)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911c74)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8191806e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81918cc5)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff8191f411)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81920b70)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81924f89)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff8192edde)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff8193c82a)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff81961fc3)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81964444)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8198346b)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819882e1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198acca)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff819912cc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994c90)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8199731b)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8199b60b)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1f7f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/netfilter.c (ffffffff819a3125)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7352)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a8961)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aac44)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819abadc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819ac003)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad147)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff819dedde)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff819dee4f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff814de860)
Location: arch/x86/include/asm/checksum_64.h:183
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
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:csum_block_add_ext
```
```
In net/core/dev.c (ffffffff818af425)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff818d19fc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff818d730c)
Location: arch/x86/include/asm/checksum_64.h:183
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
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff818f60cb)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff8190ea90)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_fragment.c (ffffffff81916ac7)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8191c704)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191cc18)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81928da0)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940445)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819467bb)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81947495)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff8194e07c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8194ff43)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81953dd0)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff8195e239)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff8196c50e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff819969ef)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81999ccd)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819b996e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819becef)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c15bc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff819c7a0a)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb57d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cdbfa)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d2022)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8be0)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819ddea9)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819df495)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e1744)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff819e267e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2be0)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3af8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff819ec1ae)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81a19d0e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a19d7f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff8150a402)
Location: arch/x86/include/asm/checksum_64.h:183
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
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff818fb265)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff8191ec8c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff81924b10)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81943a5b)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81955731)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81970651)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff8197ea2f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197ef78)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff8198bd22)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4981)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819aae1c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819abb27)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff819b2888)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819b4804)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819b86ed)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff819c3601)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf1d1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff819d3266)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4f9c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a02f38)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a05c37)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a285b0)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2dbf6)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a30399)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81a365f0)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39ff1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c205)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a40e03)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a47441)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c9fa)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e00e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a50502)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51346)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a5192e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52868)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81a5b33b)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81a89a2e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a89a9f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff8152853c)
Location: arch/x86/include/asm/checksum_64.h:183
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
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8192d3b5)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff81950ecc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff81956f40)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81978a4c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff8198bbd1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff819a7041)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff819b53c1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b6378)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819c2607)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db681)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1aec)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819e27f7)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff819e9628)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819eb534)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819ef3ed)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff819fa1a1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05d71)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81a09dd6)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bc4c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a39b0d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c79f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a5f022)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a64761)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66ee9)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81a6d110)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70b81)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a72e85)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a77a83)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7dff1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a835ca)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a84c38)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a87122)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87f66)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a8852e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89448)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81a91f6b)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81ac0cce)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ac0d3f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff815883c5)
Location: arch/x86/include/asm/checksum_64.h:175
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
In arch/x86/lib/csum-partial_64.c (ffffffff815fd11e)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd18f)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In net/core/skbuff.c (ffffffff819f142c)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a02445)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff81a21bfc)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a2f8a9)
Location: arch/x86/include/asm/checksum_64.h:175
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
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/lwt_bpf.c (ffffffff81a4d578)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81a637d1)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81a903a1)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81a9f622)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa0be5)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81aac630)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac874b)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf15c)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81acfdf7)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81ad33d6)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad91f2)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81add33f)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81ae8b1a)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5481)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81afa44e)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1de1b)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f2d1)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b31e65)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b579fc)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b5b817)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f8ce)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81b65c01)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a37b)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d35b)
Location: arch/x86/include/asm/checksum_64.h:175
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
In net/ipv6/udp_offload.c (ffffffff81b71cf9)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78b4b)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e3e5)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fcea)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82554)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83423)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83ace)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84892)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81b8d12b)
Location: arch/x86/include/asm/checksum_64.h:175
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In lib/iov_iter.c (ffffffff815a807d)
Location: arch/x86/include/asm/checksum_64.h:169
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
In arch/x86/lib/csum-partial_64.c (ffffffff81621f1e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621f7f)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff819f13c3)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a02c45)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff81a21f7c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a31bb9)
Location: arch/x86/include/asm/checksum_64.h:169
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
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/lwt_bpf.c (ffffffff81a5323d)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81a6b926)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/sched/sch_frag.c (ffffffff81a6f4ed)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/utils.c (ffffffff81a9a271)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81aa9562)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa055)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81ab3f80)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad46eb)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb167)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81adbd71)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81adf7d2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5c09)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81aea08f)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81af5a1f)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81b021e1)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81b07bf8)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c6e9)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dd1e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b40a65)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b65f0c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b6a041)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6e06e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81b74372)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78e54)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b7be09)
Location: arch/x86/include/asm/checksum_64.h:169
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
In net/ipv6/udp_offload.c (ffffffff81b80a2e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87aca)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d3fc)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f01a)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91c48)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92acd)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b93186)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b941f2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81b9cd90)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In lib/iov_iter.c (ffffffff815b3503)
Location: arch/x86/include/asm/checksum_64.h:169
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
In arch/x86/lib/csum-partial_64.c (ffffffff8160582e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81605890)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff819d6665)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff819e94c5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/utils.c (ffffffff81a092ac)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a18a25)
Location: arch/x86/include/asm/checksum_64.h:169
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
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/lwt_bpf.c (ffffffff81a38a6b)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81a54092)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/sched/sch_frag.c (ffffffff81a57dc9)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/utils.c (ffffffff81a85564)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81a9472f)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a951e5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81a9f0f0)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf7dd)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac61b6)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81ac6bb1)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81aca6d7)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0ef9)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81ad57d3)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81ae1186)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedaef)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81af3404)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a33d)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b1d9)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e2fb)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b53f79)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b58331)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c472)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81b62dd2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b679c4)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a8ee)
Location: arch/x86/include/asm/checksum_64.h:169
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
In net/ipv6/udp_offload.c (ffffffff81b6f64f)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7677a)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c2a5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e050)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80e96)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81c2b)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b82220)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b83300)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81b8be80)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In lib/iov_iter.c (ffffffff816194cc)
Location: arch/x86/include/asm/checksum_64.h:169
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
In arch/x86/lib/csum-partial_64.c (ffffffff8167411e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81674180)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff81a86cb5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_pull_rcsum
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff81a97582)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/utils.c (ffffffff81abb77c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81ac9f15)
Location: arch/x86/include/asm/checksum_64.h:169
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
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/lwt_bpf.c (ffffffff81aee94b)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81b0cda2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/sched/sch_frag.c (ffffffff81b10d90)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/utils.c (ffffffff81b3fc54)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81b4fbaf)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b50645)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81b5a240)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d346)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81b849c6)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81b853f1)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81b88fb4)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f916)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81b94542)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81ba0826)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81badea5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3914)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde95d)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81bf12fc)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81bf45f1)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81c1d428)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81c1f6e1)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23d33)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81c2a867)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f610)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c3274e)
Location: arch/x86/include/asm/checksum_64.h:169
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
In net/ipv6/udp_offload.c (ffffffff81c3770c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41205)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c471a5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c48ec0)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c073)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4ceb3)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dc7b)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e2d0)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f3d0)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81c58160)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mptcp/protocol.c (ffffffff81c77923)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81c8099b)
Location: arch/x86/include/asm/checksum_64.h:169
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
In lib/iov_iter.c (ffffffff816e686e)
Location: arch/x86/include/asm/checksum_64.h:169
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
In arch/x86/lib/csum-partial_64.c (ffffffff8178e6ad)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e830)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
```
In net/core/skbuff.c (ffffffff81bfab3b)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/utils.c (ffffffff81c3605c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81c45b30)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/gro.c (ffffffff81c53662)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
```
```
In net/core/lwt_bpf.c (ffffffff81c71b4a)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81c97f2b)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/utils.c (ffffffff81ccc487)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81cdd625)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdebe0)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81ce8592)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d26e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81d1522c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81d16133)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81d1aa23)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81d20c0b)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81d25dde)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81d32d12)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40f33)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81d47145)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81d757c5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81d89b19)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db9a72)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81dbc2d3)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81dc0c5e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81dc7d45)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc99a)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfc63)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd530c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf9a2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de64e9)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec020)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded325)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeb80)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defe39)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1cb93)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81e25bbd)
Location: arch/x86/include/asm/checksum_64.h:169
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
Location: arch/x86/include/asm/checksum_64.h:169
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
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/utils.c (ffffffff81de96ec)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81df9d90)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/gro.c (ffffffff81e08d02)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
```
```
In net/core/lwt_bpf.c (ffffffff81e29c3a)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81e53ebe)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/utils.c (ffffffff81e8c387)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81e9e0e1)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9eb00)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81eabee2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2cd0)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb40c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81edc663)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81ee1753)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7e85)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81eed657)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81efafa2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09cc3)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81f0baf2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv4/gre_offload.c (ffffffff81f1006a)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41de2)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81f579ce)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f89b02)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81f8c7b3)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81f912e8)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81f98ab5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9db0e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0fa4)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6a15)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1c6c)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb91cf)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfc6e)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc1135)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2bd0)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3f49)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff4023)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81ffd84d)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff8204bfd5)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c140)
Location: arch/x86/include/asm/checksum_64.h:169
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
Location: arch/x86/include/asm/checksum_64.h:168
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
In net/core/skbuff.c (ffffffff81e14ce5)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/utils.c (ffffffff81e5aefb)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81e6bb80)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/gro.c (ffffffff81e7b422)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
```
```
In net/core/lwt_bpf.c (ffffffff81e9f259)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81eaf738)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/utils.c (ffffffff81eea497)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81efc8af)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efd2ff)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81f0a6a2)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f319b7)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a4cc)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81f3b7ba)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81f41165)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81f4770e)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81f4d01a)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81f5aa30)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81f697d3)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81f6b6c2)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fd5a)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1673)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7496)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe93b0)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81fed03a)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff81ff1beb)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81ff9495)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe58f)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff82001967)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820071ee)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012354)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201992f)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201d30f)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020bfe)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff8202209b)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023b5f)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024f68)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82070633)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff82079b1d)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff820ca848)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:csum_partial
  - arch/x86/lib/csum-partial_64.c:csum_partial
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820caa30)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
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
Location: arch/x86/include/asm/checksum_64.h:168
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
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/datagram.c (ffffffff81edd689)
Location: arch/x86/include/asm/checksum_64.h:168
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
In net/core/utils.c (ffffffff81f1a2bb)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81f2ac60)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/gro.c (ffffffff81f3b6b2)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
```
```
In net/core/lwt_bpf.c (ffffffff81f619c6)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/sched/sch_frag.c (ffffffff81f721b8)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/utils.c (ffffffff81fae247)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81fc07ef)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc126f)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81fce6a1)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7ba3)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff820005bc)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff820018da)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff82006db5)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8200d84e)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8201312a)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff82020f70)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff8202fe53)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff82031726)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv4/gre_offload.c (ffffffff8203648a)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e993)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff82084af6)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b5ec2)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff820bac3a)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/icmp.c (ffffffff820bf7ea)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff820c7113)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd462)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d076a)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820d604e)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e14c4)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e88ff)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820ec2ef)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efd2e)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f11bb)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2cbf)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4248)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82144593)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff8214ef7d)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a5270)
Location: arch/x86/include/asm/checksum_64.h:168
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In lib/iov_iter.c (ffffffff81520b1c)
Location: arch/x86/include/asm/checksum_64.h:183
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
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff818cd3b5)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff818f0e9c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff818f6f10)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff819188bc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff8192ba41)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81946eb1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81955231)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff819561e8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81962477)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b4f1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8198195c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81982667)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81989498)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8198b3a4)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8198f18d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81999f41)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5b11)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff819a9b76)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb2dc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d919d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819dbe2f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819fe6b2)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a03df1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a06579)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81a0c7a0)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10211)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12515)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a17113)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d681)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22c5a)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a242c8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a267b2)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81a275f6)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27bbe)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28ad8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81a315fb)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81a5fb1e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a5fb8f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff81510e0c)
Location: arch/x86/include/asm/checksum_64.h:183
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
In drivers/net/vxlan.c (ffffffff81772e3a)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/core/skbuff.c (ffffffff81878a99)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff818874d5)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff818aacdc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff818b0d40)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff818d266c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff818e57f1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff819009a1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff8190ed21)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190fcd8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff8191bf67)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934fb1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b41c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff8193c127)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff81942f58)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81944e64)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81948c4d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81953a01)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f5d1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81963636)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967e5d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819880cc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81995f5d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81998bef)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bb472)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819c0bb1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c3339)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff819c9560)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccfd1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf2d5)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d3ed3)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da441)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfa1a)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e1088)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e3572)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff819e43b6)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e497e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5cc8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff819ee7eb)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81a1cbee)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a1cc5f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff8151cbac)
Location: arch/x86/include/asm/checksum_64.h:183
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
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8191e3b5)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff81941ecc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff81947f40)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81969a4c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff8197cbd1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81998041)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff819bfa01)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c09b8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819ccc47)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5cc1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819ec12c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819ece37)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff819f3c68)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819f5b74)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819f9a2d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81a047e1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81a103b1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81a14416)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35d5c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a43c1d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a468af)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a69132)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6e871)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70ff9)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81a77220)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7ac91)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cf95)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a81b93)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a88101)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d6da)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ed48)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90c65)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a92362)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81a931a6)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9376e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94688)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81a9d1ab)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81acbf0e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81acbf7f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In lib/iov_iter.c (ffffffff81536403)
Location: arch/x86/include/asm/checksum_64.h:183
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
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (ffffffff8193fa45)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff819637cc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/core/filter.c (ffffffff81969850)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_update
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff8198be2c)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff8199f13f)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff819bad21)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff819c9380)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff819ca398)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819d67d7)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef981)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5fdc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819f6d27)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/udp.c (ffffffff819fde28)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819ffd74)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81a03d1d)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/igmp.c (ffffffff81a0ed61)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1ac01)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ee18)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81a416cc)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f8bd)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a525df)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a75712)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7ae9b)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_getfrag
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d609)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_getfrag
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81a8383e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a874d1)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a897e5)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e493)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94d32)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a3ca)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bab8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e412)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f2f3)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f8be)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa07e8)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81aa93a9)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In arch/x86/lib/csum-partial_64.c (ffffffff81ad845e)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-partial_64.c:ip_compute_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
  - arch/x86/lib/csum-partial_64.c:do_csum
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ad84cf)
Location: arch/x86/include/asm/checksum_64.h:183
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
</details>
</li>
</ul>

## Differences
