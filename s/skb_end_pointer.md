# Function: <code>skb_end_pointer</code>

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
In drivers/net/tun.c (ffffffff815ee348)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff815f26f5)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f6aaa)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff815fabc8)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/socket.c (ffffffff816fcc8f)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/core/skbuff.c (ffffffff817052c5)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/datagram.c (ffffffff8170d1b6)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff81713810)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8173240d)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81734065)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/core/tso.c:tso_count_descs
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81738b21)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81740c28)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817490c8)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff8174c4d5)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/netfilter/core.c (ffffffff81750ffe)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff81758879)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff81759fe2)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff8175a77a)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175c79f)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81765d81)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8176d757)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81774465)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81783147)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff8178514d)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8178b320)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4a54)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff817a94a3)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv4/inet_lro.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817aef10)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff817b004c)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c5c32)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff817ee49d)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff817f32e2)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817fa057)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/ip6_checksum.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81800b45)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818012c3)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/udp_offload.c (ffffffff818015ce)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/packet/af_packet.c (ffffffff81802d8d)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:packet_direct_xmit
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8180973d)
Location: include/linux/skbuff.h:1092
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/skbuff.h:1092
Inline: True
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
In drivers/net/tun.c (ffffffff8164ddf2)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81651caa)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81656c2d)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8165bd26)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff81764c78)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81767ccb)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8176ef2c)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb
```
```
In net/core/datagram.c (ffffffff81774f86)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81783a56)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_csum_offload_chk
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8179d814)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/tso.c (ffffffff8179fdaf)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff817a515a)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff817a8a01)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff817ada4d)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817b608e)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff817b81e9)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/netfilter/core.c (ffffffff817bd02a)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff817c5331)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff817c63e3)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff817c6b38)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817cb2f4)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ce05c)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff817d320a)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff817d79f5)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff817e1315)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebcff)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec753)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efbff)
Location: include/linux/skbuff.h:1183
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0749)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff817f2749)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f3a77)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff817f8461)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81800b05)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ping.c (ffffffff818104d8)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812861)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81812983)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81816ce3)
Location: include/linux/skbuff.h:1183
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181c048)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cf7c)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_output.c (ffffffff818294b3)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/ip6_output.c (ffffffff81834f04)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81835e84)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff81850061)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/reassembly.c (ffffffff8185ccd9)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860861)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81862787)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81864037)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff8186692e)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818698bd)
Location: include/linux/skbuff.h:1183
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186c9b1)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/calipso.c (ffffffff81870013)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/ip6_checksum.c (ffffffff8187179c)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/output_core.c (ffffffff81871fb2)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff818721b5)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872b02)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff818786a7)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_snd_vnet_gso
  - net/packet/af_packet.c:packet_snd_vnet_gso
  - net/packet/af_packet.c:packet_snd_vnet_gso
  - net/packet/af_packet.c:packet_snd_vnet_gso
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:packet_direct_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8187b23e)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff8187b9bc)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
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
In drivers/net/tun.c (ffffffff8167fb17)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8168490d)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81689b56)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff81791cf8)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81794ceb)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff817a130e)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb
```
```
In net/core/datagram.c (ffffffff817a2286)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff817b11c7)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cb745)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff817ce77f)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff817d3bca)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff817d753f)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff817dd089)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817e5a2b)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff817e7cc9)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/netfilter/core.c (ffffffff817ec96a)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff817f4e41)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5ee3)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff817f6638)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817faf54)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fddc3)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81804aec)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81807995)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff818117e5)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ca79)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d043)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8182060f)
Location: include/linux/skbuff.h:1198
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff818214b9)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff818235b0)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81824867)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81829311)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81831a55)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ping.c (ffffffff818419d8)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843d61)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81843e83)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818484b2)
Location: include/linux/skbuff.h:1198
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d908)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e83c)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ae83)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/ip6_output.c (ffffffff81866a3a)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff818679a4)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff81881e61)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/reassembly.c (ffffffff8188ec17)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892c73)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8189482a)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff818966e7)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff8189902e)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8189c70d)
Location: include/linux/skbuff.h:1198
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f7a1)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/calipso.c (ffffffff818a2f83)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5cfc)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/output_core.c (ffffffff818a6592)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6795)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a7122)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff818acef9)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/8021q/vlan_core.c (ffffffff818afafe)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff818b027c)
Location: include/linux/skbuff.h:1198
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
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
In drivers/net/loopback.c (ffffffff8168d85e)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81694ea2)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699d6a)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8169ef9b)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff817af2d8)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff817b2ed7)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff817be232)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb
```
```
In net/core/datagram.c (ffffffff817bfaeb)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff817d15a4)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817eaf37)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/tso.c (ffffffff817edc2f)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff817f2f18)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff817f6b9e)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/gro_cells.c (ffffffff817f98bb)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff817fc6ca)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8180555b)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff818079d3)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/netfilter/core.c (ffffffff8180cd8a)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff818152ab)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff818164ab)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff81816a4a)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8181b348)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e19d)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81824e32)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81827e55)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81831a55)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183d057)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d867)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840b1f)
Location: include/linux/skbuff.h:1191
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81842199)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff8184427c)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81845507)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8184a5b0)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81852fd5)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ping.c (ffffffff818630be)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818655f1)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff818656fe)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81869bba)
Location: include/linux/skbuff.h:1191
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81871369)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff8187230c)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff818724f3)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ef7a)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8187f651)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff818801b6)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff8188b167)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff8188c14f)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818a865d)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/reassembly.c (ffffffff818b5149)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b9258)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bac0f)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff818bcc45)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff818bf4a6)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818c2ae2)
Location: include/linux/skbuff.h:1191
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5d50)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/calipso.c (ffffffff818c9553)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818caee1)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc75c)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/output_core.c (ffffffff818ccfe9)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd1f5)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdb92)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff818d542a)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/8021q/vlan_core.c (ffffffff818d62c6)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff818d6c3d)
Location: include/linux/skbuff.h:1191
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
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
In kernel/bpf/cpumap.c (ffffffff811afc50)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In kernel/bpf/sockmap.c (ffffffff811b0a01)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_parse_func_strparser
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In drivers/net/loopback.c (ffffffff816f73de)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff816feff6)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81704519)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8170a132)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff81827418)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8182b1c7)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81837942)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:copy_skb_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb
```
```
In net/core/datagram.c (ffffffff8183969b)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff8184b579)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818665a7)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81869e6f)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff8186e314)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff81873181)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff8187674e)
Location: include/linux/skbuff.h:1249
Inline: True
```
```
In net/core/gro_cells.c (ffffffff818771db)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8187a12a)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8188426b)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81886543)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff8188ba0c)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff8188bf6a)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff8189447b)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff81895644)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff81895c0a)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8189a278)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189d0ad)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff818a37a4)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff818a7405)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff818b47d4)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc803)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bcf77)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c028f)
Location: include/linux/skbuff.h:1249
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a79)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff818c3bae)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c5008)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff818ca257)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818d2e15)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ping.c (ffffffff818e31ee)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5741)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff818e584e)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818ea270)
Location: include/linux/skbuff.h:1249
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1d59)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2cec)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2ee9)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff819000a5)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8190077f)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819012d9)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff8190c387)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff8190d43f)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff8192b10d)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/reassembly.c (ffffffff81937ebf)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c1a0)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff8193dc1f)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff8193fd65)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81942445)
Location: include/linux/skbuff.h:1249
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81944efb)
Location: include/linux/skbuff.h:1249
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff819490e2)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/calipso.c (ffffffff8194cbf3)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e821)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194fd2b)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ip6_checksum.c (ffffffff8195150c)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81951fd5)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952992)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81959eda)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff8195af49)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff8195be60)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff8195c80d)
Location: include/linux/skbuff.h:1249
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
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
In kernel/bpf/cpumap.c (ffffffff811cac01)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffff81734579)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8173fda4)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742967)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81748d32)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff818707fa)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818751ce)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81881e12)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb
```
```
In net/core/datagram.c (ffffffff81883dca)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81895941)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b5f63)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff818b9b53)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff818bf4a4)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff818c4907)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff818c7e92)
Location: include/linux/skbuff.h:1260
Inline: True
```
```
In net/core/gro_cells.c (ffffffff818c890b)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818cc14f)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff818d7cd7)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff818d9e50)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff818df444)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff818dfc33)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff818e86c3)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9821)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff818e9ebe)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ee74f)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f146a)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff818f8a73)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff818fc685)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81909e29)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912328)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912ddc)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915ddf)
Location: include/linux/skbuff.h:1260
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81917749)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819197d3)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191aabc)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81920ce5)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819293ea)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ping.c (ffffffff81939bd6)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bfe4)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff8193c112)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8194095b)
Location: include/linux/skbuff.h:1260
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81948658)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81949617)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff81949827)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff81956b27)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8195725b)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8195819e)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81963801)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff81964798)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff819833cf)
Location: include/linux/skbuff.h:1260
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff8199104d)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81995340)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81996b0e)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81998ae4)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff8199b265)
Location: include/linux/skbuff.h:1260
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199e235)
Location: include/linux/skbuff.h:1260
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a2171)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/calipso.c (ffffffff819a5fd3)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7b0b)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a8f16)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aaabb)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab56a)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abf42)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff819af17e)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff819b45af)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff819b56a5)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff819b5fea)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff819cc2bc)
Location: include/linux/skbuff.h:1260
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff811de4f8)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffff817576c9)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817637bf)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817671e1)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8176cdd0)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff8189130a)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81895a9b)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff818a291c)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb
```
```
In net/core/datagram.c (ffffffff818a449a)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff818a9953)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818b7627)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818dafd5)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff818e090d)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff818e82c3)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff818ed987)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff818f0ff2)
Location: include/linux/skbuff.h:1298
Inline: True
```
```
In net/core/gro_cells.c (ffffffff818f3835)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818f6b8f)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff819044c7)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81906950)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff8190c02f)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff8190c7b6)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/ip_input.c (ffffffff81914e2a)
Location: include/linux/skbuff.h:1298
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819168b3)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff819172ee)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191beff)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191efc7)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff8192679a)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff8192a6c5)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff819380da)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940b05)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941597)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194458f)
Location: include/linux/skbuff.h:1298
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e86)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819480aa)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194bbe1)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8194ef22)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8195904a)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ping.c (ffffffff81969863)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bcf9)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff8196be22)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81970812)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197a335)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b2de)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b4e7)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b75c)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198beb1)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8198caf1)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff819987c1)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff81999141)
Location: include/linux/skbuff.h:1298
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819b9701)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819be5f2)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff819c77a6)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbc26)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff819cd405)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff819cf431)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff819d1ba2)
Location: include/linux/skbuff.h:1298
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d4cef)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8dce)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/calipso.c (ffffffff819dc980)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de658)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819dfed1)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e15ab)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819e21ba)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2b1f)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff819e5b48)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff819eb5d5)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff819ec96a)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff819ed2aa)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81a0549e)
Location: include/linux/skbuff.h:1298
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff811f3d99)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffff81793e79)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817a14ca)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a357f)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff817aaab5)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff818daffa)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818dffbd)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff818ed56c)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff818efaeb)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81903459)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81924a78)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff8192ef9d)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff81937afd)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff8193e2cd)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81943604)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff819526dc)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8195631b)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81965857)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81967bf0)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff8196d719)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff819772fe)
Location: include/linux/skbuff.h:1386
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8197921e)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197e21a)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981906)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff8198765d)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff8198d935)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff8199b531)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a50cd)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5b8f)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8b7f)
Location: include/linux/skbuff.h:1386
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa4b7)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819ac377)
Location: include/linux/skbuff.h:1386
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b0307)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819b370c)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819bdb1a)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf3d1)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff819d04b0)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a49)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff819d2b72)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819da064)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3e75)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e4812)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4a0b)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4b23)
Location: include/linux/skbuff.h:1386
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6c81)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff819f7447)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819f80e3)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a04615)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81a0504f)
Location: include/linux/skbuff.h:1386
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a28301)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2d041)
Location: include/linux/skbuff.h:1386
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a71f)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c4c1)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a3e17e)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a40954)
Location: include/linux/skbuff.h:1386
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a43b45)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47645)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a4861d)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a4b3c0)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d1ce)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4eada)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a50377)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51795)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a51861)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81a55577)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff81a5a7d3)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81a5bb25)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81a5c496)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81a74b03)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff81200b39)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffff817b79a9)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817c648a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c6fcf)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff817ce4f8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff8190d14a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8191216d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8191f66c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff81921b0b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81936209)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81956ea8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff8196120d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff8196a9bd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff8197115d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819785d8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:handle_gso_type
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81988a2c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8198c7bb)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8199c2e7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff8199e690)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff819a4184)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff819adc8e)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819afb8e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b4bca)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b8146)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819bde1d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819cc54f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff819d1f51)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbdcd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc94f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df81f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1187)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819e2e0f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e6fbd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819ea43c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819f472a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05f63)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81a07000)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a095b9)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a096e2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a10f53)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ae65)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b822)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1ba2b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b7d3)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d8f1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a2e097)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ed33)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b205)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bc1f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a5ed8d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a63b82)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a712c0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81a73141)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a74dee)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a775d4)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a7c7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e1c5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a7f1de)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a81f90)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83d9e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8577a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a86f97)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a883b5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a88461)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81a8c647)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff81a91423)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81a9271c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81a930c3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81aaa614)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff81227dd3)
Location: include/linux/skbuff.h:1389
Inline: True
```
```
In drivers/net/loopback.c (ffffffff8187eae9)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8188dace)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892c5f)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81896dad)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff819dfeaa)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819e4c7d)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff819f2be1)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_gro_receive_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff819f53ff)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81a012f3)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2d3fc)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81a3471f)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff81a3e5c0)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff81a45565)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a4d4f4)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81a606ba)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81a64820)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81a75027)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81a782b0)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81a7ede4)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
```
```
In net/ipv4/ip_input.c (ffffffff81a97ec2)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a99a5e)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9eda6)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2a66)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81aa8ff2)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81aba4e2)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_measure_rcv_mss
```
```
In net/ipv4/tcp_output.c (ffffffff81abec19)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac90ac)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9a1f)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acccc1)
Location: include/linux/skbuff.h:1389
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace777)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ad06f8)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ad6b22)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad824f)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae243a)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5676)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81af7600)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8dd0)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81af9e52)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b027a0)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0bec9)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c8c2)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d647)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f03d)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b20fc3)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21824)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b307c1)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81b310a2)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b578f3)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5c61a)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6ad3a)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d55d)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b6f03e)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b71837)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b76096)
Location: include/linux/skbuff.h:1389
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78c62)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78e91)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/netfilter.c (ffffffff81b79e97)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81b7d0c0)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7eb6a)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b80710)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82247)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83885)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83934)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81b879ec)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:__packet_set_timestamp
```
```
In net/strparser/strparser.c (ffffffff81b8c893)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81b8dbc4)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81b8e3d4)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81ba79bd)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff8122eb33)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In drivers/net/loopback.c (ffffffff8188d069)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8189c00e)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a0cff)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff818a6b9d)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff819df66a)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819e453d)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff819f2bee)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_gro_receive_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff819f4ed6)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81a01ae3)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a2ec9c)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81a36979)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff81a41360)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff81a49839)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a531b1)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81a68f49)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff81a6c960)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_frag.c (ffffffff81a6f389)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_fifo.c (ffffffff81a7df27)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81a80ee8)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81a887d7)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
```
```
In net/ipv4/ip_input.c (ffffffff81aa1e1b)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81aa39ae)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa8ce6)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacd76)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81ab34e2)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5922)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_measure_rcv_mss
```
```
In net/ipv4/tcp_output.c (ffffffff81aca579)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad504c)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad596f)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8cc1)
Location: include/linux/skbuff.h:1410
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada797)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81adc708)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ae3102)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae48ef)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aef2da)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02436)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81b044e0)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06b96)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81b075a4)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b10b67)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1a259)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1abf2)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2be61)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d8fd)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b2f997)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b301f4)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f3f1)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fccb)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b65e03)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6ae5a)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b797cd)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c00d)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b7db6e)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b804d7)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b84e16)
Location: include/linux/skbuff.h:1410
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87be2)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87e11)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/netfilter.c (ffffffff81b88de7)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81b8c170)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8db77)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ff90)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91937)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92f45)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b92ff4)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81b974cc)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:__packet_set_timestamp
```
```
In net/strparser/strparser.c (ffffffff81b9c4e3)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81b9d893)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81b9e074)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81bb7103)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_destruct_skb
```
```
In net/mptcp/protocol.c (ffffffff81bbb95f)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In drivers/net/loopback.c (ffffffff8186f9a9)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8187e587)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8188338f)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8188a3eb)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff819c6095)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819ca5e6)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff819d8e01)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_gro_receive_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff819db05e)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff819f25c0)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a162fd)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81a1daf5)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/xdp.c (ffffffff81a1f9a9)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/netpoll.c (ffffffff81a25fbe)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff81a2e789)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81a3648d)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81a389e4)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81a4c309)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/skmsg.c (ffffffff81a4e6f7)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81a5517f)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_frag.c (ffffffff81a57c5f)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_fifo.c (ffffffff81a66d77)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81a696a1)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81a71a37)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
```
```
In net/ipv4/ip_input.c (ffffffff81a8cd52)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ea6e)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a93e06)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97fcf)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81a9e665)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b32)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81ab53f9)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac00d2)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac09cf)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3d31)
Location: include/linux/skbuff.h:1417
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac5817)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ac7753)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81acce1f)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81acfb3c)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adaa2a)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedd43)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81aef4f9)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af22bb)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81af2d52)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81afe771)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07f05)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b088af)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19ad7)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b95c)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b1d69c)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1df30)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d289)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81b2db02)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b53ead)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b59160)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b682eb)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81b6aaf1)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b6c767)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f0e8)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b73aca)
Location: include/linux/skbuff.h:1417
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7689f)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76adb)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/netfilter.c (ffffffff81b77c07)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81b7aff0)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ca4a)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0c2)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80b8a)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b82095)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b82147)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81b864cb)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/strparser/strparser.c (ffffffff81b8b5a3)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81b8c9bc)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81b8d174)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81ba6028)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_destruct_skb
```
```
In net/mptcp/protocol.c (ffffffff81bab56f)
Location: include/linux/skbuff.h:1417
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In drivers/net/loopback.c (ffffffff818fff49)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8190fd94)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914d2f)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8191ce54)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff81a74ce5)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81a79b86)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81a88da1)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_gro_receive_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff81a8b70e)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81aa4490)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81ac725d)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81ad1595)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/xdp.c (ffffffff81ad3969)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/netpoll.c (ffffffff81adad2e)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff81ae3d69)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81aec15d)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81aee8c4)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81b047b9)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/skmsg.c (ffffffff81b07433)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/sched/sch_generic.c (ffffffff81b0e3af)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_frag.c (ffffffff81b10bff)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_fifo.c (ffffffff81b20237)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81b22c5d)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81b2b14e)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
```
```
In net/ipv4/ip_input.c (ffffffff81b47e8a)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81b49c6e)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4f246)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b5345f)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81b5a425)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:skb_advance_to_frag
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d974)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81b723f1)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7dd42)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e38f)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b823c1)
Location: include/linux/skbuff.h:1430
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84027)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81b85f9c)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81b8b7a2)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e55c)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b99c6a)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae0f3)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81bb0a79)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb27cb)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3262)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bbff87)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc72fe)
Location: include/linux/skbuff.h:1430
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bcae05)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb7af)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81bddda7)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be01e8)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81be24fd)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2a20)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3442)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3d56)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81c1d35c)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c20752)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2ffeb)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81c32951)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81c34656)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81c371a8)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e0d5)
Location: include/linux/skbuff.h:1430
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c4131f)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41543)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/netfilter.c (ffffffff81c42727)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81c45cb0)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47b79)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a912)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c179)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cbaa)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4e145)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e1f7)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81c5288b)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/strparser/strparser.c (ffffffff81c57843)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81c58d7c)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81c59536)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81c739b7)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_destruct_skb
```
```
In net/mptcp/protocol.c (ffffffff81c78a8f)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In drivers/net/loopback.c (ffffffff81a519b9)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81a669de)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6a36f)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81a72cba)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff81be79a5)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81bec928)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81bfd114)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff81c00d46)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81c1a13a)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c42a56)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81c4ee89)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/xdp.c (ffffffff81c51368)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81c54466)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/netpoll.c (ffffffff81c5b513)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/net-traces.c (ffffffff81c68a6f)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81c6eb0e)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81c71824)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81c8a052)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/skmsg.c (ffffffff81c8bd7c)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81c94830)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_frag.c (ffffffff81c97d9e)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_fifo.c (ffffffff81ca8487)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81cab858)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81cb53a3)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
```
```
In net/ipv4/ip_input.c (ffffffff81cd5139)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81cd71de)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cdcbd5)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfb83)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81ce8f37)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:skb_advance_to_frag
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81cfcde2)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81d01b5e)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0dd4d)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e30a)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d128c1)
Location: include/linux/skbuff.h:1737
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81d147e5)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81d168e5)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81d1c139)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f78e)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2bc2a)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4122e)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81d4400f)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45f99)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81d46a72)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d54ac2)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d60771)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61269)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74f37)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d770ff)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81d795f3)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79b7b)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c053)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff81d8ca71)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81db99bb)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbd4d7)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd396)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81dd013e)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81dd1fa1)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81dd4d51)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc7bb)
Location: include/linux/skbuff.h:1737
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfaa9)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfcde)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/netfilter.c (ffffffff81de11d6)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81de4e50)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6fd3)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81dea236)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec1a8)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81decfed)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee9c5)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeaaf)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81df5897)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/strparser/strparser.c (ffffffff81df8e7f)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81dfa427)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81dfaccf)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81e1813a)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_destruct_skb
```
```
In net/mptcp/protocol.c (ffffffff81e1efc4)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mctp/route.c (ffffffff81e38c67)
Location: include/linux/skbuff.h:1737
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_frag_queue
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
In io_uring/net.c (ffffffff81795b85)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter_iovec
```
```
In drivers/net/loopback.c (ffffffff81bdabf9)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81bf2304)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfd0ba)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81c0543a)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff81d93e65)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81d9b3b8)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81dac087)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/datagram.c (ffffffff81db0174)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81dcb1ca)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81df7a46)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81e03f39)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81e06b04)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81e09bb6)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/netpoll.c (ffffffff81e117dd)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/net-traces.c (ffffffff81e2011b)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81e2684e)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e29914)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81e44c32)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/skmsg.c (ffffffff81e482c9)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/sched/sch_generic.c (ffffffff81e502f0)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_frag.c (ffffffff81e53d3e)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_fifo.c (ffffffff81e652a7)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81e6866b)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81e7398c)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:convert_skb_to___skb
  - net/bpf/test_run.c:convert_skb_to___skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
```
```
In net/ipv4/ip_input.c (ffffffff81e95609)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81e977ae)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9d645)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9ff33)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81eac4b7)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:skb_advance_to_frag
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81ec19a2)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6cce)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed36f7)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3dba)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8701)
Location: include/linux/skbuff.h:1581
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda915)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81edd094)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ee3003)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee696e)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef384a)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09fde)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81f0d4df)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f379)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81f0fea2)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f1ed0d)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2af31)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bb69)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42174)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4397f)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81f46083)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81f4697a)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a013)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff81f5ac81)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81f89a4b)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8da16)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e47a)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81fa14ce)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81fa3401)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6411)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81fad857)
Location: include/linux/skbuff.h:1581
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1d99)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb1ffe)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/netfilter.c (ffffffff81fb3636)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81fb75e0)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9e63)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81fbdaf6)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfdf8)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0ded)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2495)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2aef)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81fc970c)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/strparser/strparser.c (ffffffff81fcd46f)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81fceb48)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81fcf502)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81fef2ea)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_destruct_skb
```
```
In net/mptcp/protocol.c (ffffffff81ff5b7d)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mctp/route.c (ffffffff82011f57)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_frag_queue
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
In io_uring/net.c (ffffffff817d6815)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter_iovec
```
```
In drivers/net/loopback.c (ffffffff81c3169d)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81c4afe6)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81c50eba)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6273a)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c688e2)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
```
```
In drivers/net/xen-netfront.c (ffffffff81c6ab4a)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff81e01a05)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81e09788)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81e14aca)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/datagram.c (ffffffff81e20371)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81e3bd5a)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e69750)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81e76726)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81e783fb)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81e7c37c)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/gso.c (ffffffff81e7d61a)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_gso_validate_network_len
  - net/core/gso.c:skb_gso_transport_seglen
  - net/core/gso.c:__skb_gso_segment
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81e850ed)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/net-traces.c (ffffffff81e948db)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81e9bdee)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e9ef54)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81e9fa32)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/skmsg.c (ffffffff81ea3a8d)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/sched/sch_generic.c (ffffffff81eaba93)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_frag.c (ffffffff81eaf5be)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_fifo.c (ffffffff81ec11e7)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81ec44db)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81ecf6b0)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:convert_skb_to___skb
  - net/bpf/test_run.c:convert_skb_to___skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
```
```
In net/ipv4/ip_input.c (ffffffff81ef3e09)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81ef5fde)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81efbd96)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe783)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81f0abb7)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:skb_advance_to_frag
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81f1ffb0)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81f25458)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f32403)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32dae)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37811)
Location: include/linux/skbuff.h:1610
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399f5)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81f3c2e4)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81f428a4)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81f461ae)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f532fa)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69aed)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81f6d13f)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f069)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fb92)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7e80d)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8ac01)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b5a9)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa195c)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3159)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81fa57f0)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa62ba)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9cc4)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff81fbaa31)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81fe92f9)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fee1f2)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffef22)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff82001dc5)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff82003cad)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff82006c91)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8200e007)
Location: include/linux/skbuff.h:1610
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820124a7)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/xfrm6_output.c (ffffffff82012718)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/netfilter.c (ffffffff82013d1c)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff82017d30)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a596)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201eb16)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020dd0)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021d7d)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff82023415)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023a7f)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff8202bbcc)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/strparser/strparser.c (ffffffff82048d96)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff8204a4fe)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff8204b17e)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff8206b1fd)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_destruct_skb
```
```
In net/mptcp/protocol.c (ffffffff82071c5f)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mctp/route.c (ffffffff8208ed37)
Location: include/linux/skbuff.h:1610
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_frag_queue
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
In io_uring/net.c (ffffffff8181a9e5)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter_iovec
```
```
In drivers/net/loopback.c (ffffffff81ce451d)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/netkit.c (ffffffff81ce5207)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81d0091c)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81d06ef7)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1915a)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f527)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff81ebe3c7)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81ec616f)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81ed20ca)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_ensure_writable_head_tail
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/datagram.c (ffffffff81ede24e)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81efa29a)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tc_run
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f28d30)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81f366e9)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81f383bb)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81f3c6cc)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/gso.c (ffffffff81f3e59a)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_gso_validate_network_len
  - net/core/gso.c:skb_gso_transport_seglen
  - net/core/gso.c:__skb_gso_segment
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/netpoll.c (ffffffff81f470dd)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/net-traces.c (ffffffff81f56df3)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81f5e54e)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81f616c4)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81f622a2)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/skmsg.c (ffffffff81f6638d)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/sched/sch_generic.c (ffffffff81f6e533)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_frag.c (ffffffff81f7203e)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_fifo.c (ffffffff81f844e7)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff81f8789b)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81f93000)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:convert_skb_to___skb
  - net/bpf/test_run.c:convert_skb_to___skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
  - net/bpf/test_run.c:convert___skb_to_skb
```
```
In net/ipv4/ip_input.c (ffffffff81fb7d9a)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_forward.c (ffffffff81fb9f6e)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbfcd6)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc299b)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81fd4173)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:skb_advance_to_frag
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4690)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d19)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff83d1)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8efe)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd8e1)
Location: include/linux/skbuff.h:1617
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffae5)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff8200240e)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff820088a8)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8200c2ee)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff820196aa)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff8203016d)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff820338a7)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035799)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff820362c2)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff82044eb2)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c75d)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82052311)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052cb0)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8206ec7c)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff820707d9)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff82072b40)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff820735bf)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff82087196)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/ip6_input.c (ffffffff82087e61)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff820b5e0b)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bbdbb)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdc60)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff820d0bc5)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff820d2a55)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff820d5af1)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff820dcb94)
Location: include/linux/skbuff.h:1617
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0ec0)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e18e4)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/netfilter.c (ffffffff820e2e76)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff820e6d00)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e9553)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820edc46)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efefd)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f0e9d)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2505)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2bdf)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff820fb67d)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/strparser/strparser.c (ffffffff8211b116)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff8211c96a)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff8211d5fe)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff8213e407)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_consume_skb
  - net/xdp/xsk.c:xsk_destruct_skb
  - net/xdp/xsk.c:xsk_destruct_skb
```
```
In net/mptcp/protocol.c (ffffffff82145dff)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mctp/route.c (ffffffff82165227)
Location: include/linux/skbuff.h:1617
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_frag_queue
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
In kernel/bpf/cpumap.c (ffff80001028821c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffff8000109d01c8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffff8000109e15a4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e35fc)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e7320)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe1f4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffff800010a08d90)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffff800010ba20ac)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffff800010ba9be4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffff800010bba07c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffff800010bbc16c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffff800010bd488c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010bf8668)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffff800010c04ad0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffff800010c10d24)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffff800010c19bc8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffff800010c1f290)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffff800010c30bb8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffff800010c383cc)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffff800010c49588)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffff800010c4d3d0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffff800010c5371c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffff800010c5e058)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/ip_forward.c (ffff800010c60254)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c65360)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffff800010c694f4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffff800010c6fa78)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffff800010c7f18c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffff800010c84b24)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f084)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f8b8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c933ac)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffff800010c951a4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffff800010c97bf8)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9d4cc)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffff800010c9fff4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffff800010caa0e4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffff800010cbef14)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffff800010cbff68)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc295c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffff800010cc2ab8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffff800010cccc68)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6ec8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7a7c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7cb4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (ffff800010cea254)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010cec688)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffff800010ced050)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffff800010cedb88)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffff800010cfc350)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffff800010cfd1b0)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d2621c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d29c38)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d3968c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffff800010d3bb28)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffff800010d3d838)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffff800010d40c4c)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d4428c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffff800010d495dc)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffff800010d4a470)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffff800010d4d728)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4faec)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d51810)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffff800010d536e0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffff800010d54f04)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d54ff8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffff800010d57e08)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffff800010d5efb8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffff800010d604bc)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffff800010d60ef8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffff800010d7e304)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (c04b84f4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (c0ab8430)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c0ac68a0)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acc11c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0d84)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_tx_timestamp
  - drivers/net/ethernet/ti/cpts.c:cpts_rx_timestamp
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad2998)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (c0adbb48)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/socket.c (c0cc483c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (c0cc82a8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (c0cd4910)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
```
```
In net/core/datagram.c (c0cd8600)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (c0ce4be4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d122b4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (c0d1df38)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (c0d27ff8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (c0d2f824)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (c0d36e3c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (c0d479c8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (c0d49fa8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (c0d5a2d0)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (c0d5b73c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (c0d630b8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (c0d6d95c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_forward.c (c0d6fb04)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d74f90)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (c0d786cc)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (c0d7ee9c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (c0d8e27c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (c0d93dfc)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c0d9dfbc)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c0d9e978)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c0da1ba8)
Location: include/linux/skbuff.h:1393
Inline: True
```
```
In net/ipv4/tcp_offload.c (c0da38f4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (c0da59ec)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0daaa98)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c0dacf8c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c0db6994)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (c0dca69c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (c0dcc3f0)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (c0dce1ac)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (c0dce2d0)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c0dd72b8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (c0de0be0)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (c0de1590)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (c0de17a0)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (c0df22d8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df45b0)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (c0df4e2c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (c0df5c50)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (c0e03738)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (c0e04330)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (c0e28580)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d9d4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (c0e3c214)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (c0e3e69c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (c0e409f8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (c0e43634)
Location: include/linux/skbuff.h:1393
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e467f4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (c0e4a9e0)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (c0e4ba78)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (c0e4ecf4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (c0e50848)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e523c8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c0e53f98)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (c0e55500)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (c0e555b4)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (c0e59d7c)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (c0e5ebb8)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (c0e5ff78)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (c0e79808)
Location: include/linux/skbuff.h:1393
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (c0000000003338c0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (c000000000a8f11c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c000000000aa32e4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa5b84)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/socket.c (c000000000c76db4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (c000000000c7f330)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (c000000000c929c8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (c000000000c95360)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (c000000000cb3978)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000cdf588)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (c000000000ceea84)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (c000000000cfc624)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (c000000000d06600)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (c000000000d11120)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:handle_gso_type
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (c000000000d2991c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (c000000000d3131c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (c000000000d46d60)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (c000000000d49f6c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (c000000000d52e80)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (c000000000d60c88)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_forward.c (c000000000d6314c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d698c8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e134)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (c000000000d765d4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (c000000000d89894)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (c000000000d909b4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9dd44)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e8cc)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c000000000da35ec)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/tcp_offload.c (c000000000da6140)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (c000000000da8b50)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/udp.c (c000000000dac690)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c000000000db2a60)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c000000000dbf978)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (c000000000dd9738)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (c000000000ddb2c0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde1d4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (c000000000dde3d0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c000000000de88b0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (c000000000df6be4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (c000000000df79e0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (c000000000df7d34)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (c000000000e0dd34)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e1088c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (c000000000e113f4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (c000000000e12534)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (c000000000e23e24)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (c000000000e24c6c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (c000000000e53f70)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e5aa50)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cdc0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (c000000000e6f4ec)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (c000000000e71c50)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (c000000000e75394)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7a734)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ec18)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (c000000000e804e4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (c000000000e84700)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e872b8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e89a84)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (c000000000e8be80)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (c000000000e8dc20)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dd00)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (c000000000e92f34)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (c000000000e99a60)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (c000000000e9b480)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (c000000000e9c2f4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (c000000000ebec40)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffe0001bcede)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffe00061cc6a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffe00062b0d4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062bad0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/socket.c (ffffffe00073a16a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffe00073d16c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffe000749444)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
```
In net/core/datagram.c (ffffffe00074af04)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffe00075e686)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe00077a382)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffe0007836c0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffe00078c6ea)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffe0007914ac)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffe000798a08)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:handle_gso_type
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffe0007a6ad8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffe0007a8fb2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffe0007b6ba6)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffe0007b7ef2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffe0007bde80)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffe0007c6c00)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_forward.c (ffffffe0007c850e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007ccb9c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf3d0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffe0007d4d9a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2dca)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffe0007e64be)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef254)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efbe6)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2900)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f43d2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffe0007f603a)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007f94be)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc75a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffe000804be8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffe000814cc2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffe0008169f8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817dc0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffe000817ed2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffe00081ed9e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008277ba)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffe00082810a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffe0008282c2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (ffffffe000837e96)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe000839d70)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffe00083a588)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b11c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffe000846c2e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffe000847558)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffe000865492)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe00086a442)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876996)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffe0008785b2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffe000879f50)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffe00087c474)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe0008801b0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882a76)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffe00088396e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffe000886836)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888222)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe0008899fc)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b3ee)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c7b6)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c86e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffe00088faae)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffe000894770)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffe0008958c8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffe0008ac670)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff811f9159)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffff8177c475)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8178af6a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178baaf)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81793118)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff818ad14a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818b216d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff818bf66c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff818c1b0b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff818d61d9)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818f6e78)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff819011dd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff8190a98d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff8191112d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81918448)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:handle_gso_type
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff8192889c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8192c62b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8193c157)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff8193e500)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81943ff4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff8194dafe)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff8194f9fe)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81954a3a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957fb6)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff8195dc8d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff8196c3bf)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81971dc1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197bc3d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c7bf)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f68f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81980ff7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81982c7f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81986e2d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff8198a2ac)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819944ca)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5d03)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff819a6da0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a9359)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff819a9482)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819b08e3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba4f5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff819baeb2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb0bb)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819cae63)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccf81)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff819cd727)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce3c3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff819da895)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff819db2af)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819fe41d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a03212)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10950)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81a127d1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a1447e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a16c64)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a19e57)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d855)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a1e86e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a21620)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a2342e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a24e0a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26627)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27a45)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27af1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81a2bcd7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff81a30ab3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81a31dac)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81a32753)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81a499a4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff811ebea9)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffff8175c225)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8176a8ba)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/vxlan.c (ffffffff8176be06)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_build_skb
  - drivers/net/vxlan.c:vxlan_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8177487f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In net/socket.c (ffffffff8186709a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8186c0bd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff818795ac)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff8187ba4b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81890019)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b0ca8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff818bb00d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff818c3db6)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff818caeed)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff818d21f8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:handle_gso_type
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff818e264c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff818e612b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff818f5c57)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff818f8000)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff818fdae4)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff819075ee)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819094ee)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190e52a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911aa6)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff8191777d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81925eaf)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff8192b891)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819356fd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8193627f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8193914f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aab7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff8193c73f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819408ed)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff81943d6c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8194df8a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f7c3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81960860)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e19)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81962f42)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ip_tunnel.c (ffffffff819677a8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff8196cf13)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819772e5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977ca2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977eab)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81987c53)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81989d71)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198a517)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b1b3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81997655)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff8199806f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bb1dd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bffd2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd710)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff819cf591)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff819d123e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff819d3a24)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d6c17)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da615)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff819db62e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff819de3e0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e01ee)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e1bca)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e33e7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4805)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e48b1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff819e8ec7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff819edca3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff819eef9c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff819ef943)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81a06594)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff811f6f29)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffff817ac829)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817bb30a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bbe4f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff817c3378)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff818fe14a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8190316d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8191066c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff81912b0b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81927209)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81947ea8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff8195220d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff8195b9bd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff8196215d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819695d8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:handle_gso_type
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81979a2c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8197d7bb)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8198d2e7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff8198f690)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff81995184)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a92b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
```
In net/ipv4/ip_input.c (ffffffff819b82ce)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819ba1ce)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bf20a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2786)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819c845d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819d6b8f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff819dc591)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e640d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6f8f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9e5f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb7c7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819ed44f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f15fd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819f4a7c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819fed6a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a105a3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81a11640)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13bf9)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a13d22)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a1b183)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24f75)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a25932)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25b3b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a358e3)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37a01)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a381a7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38e43)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a45315)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81a45d2f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a68e9d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6dc92)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b3d0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d251)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a7eefe)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a816e4)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a848d7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a882d5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a892ee)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a8c0a0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8deae)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f88a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a921d7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a935f5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a936a1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81a97887)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff81a9c663)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81a9d95c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81a9e303)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81ab5854)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
  - net/xdp/xsk.c:xsk_destruct_skb
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
In kernel/bpf/cpumap.c (ffffffff8120520f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/loopback.c (ffffffff817c67b9)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817d4345)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d609f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff817dd638)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/socket.c (ffffffff8191f1da)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8192414d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff819317cc)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_condense
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_copy_header
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_coalesce_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/datagram.c (ffffffff81933c8b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81948873)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff819697b8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81973c4d)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_count_descs
```
```
In net/core/netpoll.c (ffffffff8197dda9)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffffffff819843cd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_rx_verbose_template
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff8198b9b8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:handle_gso_type
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff8199bf2b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffffffff8199fd2b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff819afb77)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/netlink/af_netlink.c (ffffffff819b1f70)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/bpf/test_run.c (ffffffff819b7d04)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_input.c (ffffffff819c1b2e)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff819c3abe)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c8b8a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc186)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819d1fad)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819e07af)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff819e6211)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:tcp_fragment_tstamp
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f00cd)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0c5f)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3c8f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5677)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819f732f)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fb2d8)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (ffffffff819fec4a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a08e3a)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv4/af_inet.c:ipip_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1adf3)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/ping.c (ffffffff81a1bfb0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e5d9)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e704)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_complete
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a26063)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a303e5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30dc2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a30fdb)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_input.c (ffffffff81a4124e)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a433c1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a4420b)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44863)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a50fe5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffffffff81a51a07)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a75488)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a7a2b2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87c10)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/exthdrs.c (ffffffff81a89aa1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a8b7be)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a8dfe4)
Location: include/linux/skbuff.h:1383
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a91227)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a94f25)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffffffff81a95f4e)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/calipso.c (ffffffff81a98fa0)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9abf2)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c613)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e287)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f745)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gso_segment
  - net/ipv6/ip6_offload.c:sit_gso_segment
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f7f1)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/packet/af_packet.c (ffffffff81aa41a7)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:tpacket_get_timestamp
```
```
In net/strparser/strparser.c (ffffffff81aa8843)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81aa9b5c)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/wireless/wext-core.c (ffffffff81aaa503)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/xdp/xsk.c (ffffffff81ac1ba5)
Location: include/linux/skbuff.h:1383
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct_skb
```
</details>
</li>
</ul>

## Differences
