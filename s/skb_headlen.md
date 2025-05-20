# Function: <code>skb_headlen</code>

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
In kernel/bpf/core.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In security/lsm_audit.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In drivers/net/tun.c (ffffffff815ee35f)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f648f)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff815fabeb)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81704e7a)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/core/dev.c (ffffffff81716f68)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/core/tso.c (ffffffff81734374)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff8174012b)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/core.c (ffffffff8175102c)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81758edc)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817599e7)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81766c7e)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e24e)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_offload.c (ffffffff81783242)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/raw.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81789fe4)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/udp_offload.c (ffffffff8178ae5c)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff8178d267)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178eda2)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81793d73)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81797dea)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4b2d)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff817a4e7a)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff817a8430)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af891)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff817affe9)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb89f)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c6e64)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff817c85d7)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff817e14e5)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4970)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e843b)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817ecdcf)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/reassembly.c (ffffffff817edd66)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f048e)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f34dc)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
```
```
In net/ipv6/ip6mr.c (ffffffff817f8cc8)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc4e1)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81800bb7)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818014ca)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818016ba)
Location: include/linux/skbuff.h:1688
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff8180271d)
Location: include/linux/skbuff.h:1688
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/skbuff.h:1688
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
In kernel/bpf/core.c (ffffffff81180457)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In security/selinux/hooks.c (ffffffff8137e023)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81397f98)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In security/lsm_audit.c (ffffffff8139c487)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8164eb1f)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81651d29)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81656912)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8165b83e)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8176eeac)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/datagram.c (ffffffff81774f12)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff8177a99e)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81783f7e)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:__skb_csum_offload_chk
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff8179d5a5)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff8179fe2b)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff817a0067)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ethernet/eth.c (ffffffff817acea6)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/netfilter/core.c (ffffffff817bd059)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/route.c (ffffffff817c225a)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff817c527c)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5dc6)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817c95d9)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff817d3129)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff817e1505)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb7f4)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0eb2)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff817f32dd)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817f7f3d)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff817f8ee6)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff817fa82e)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff817fc82a)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8180150e)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8180578e)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818128a4)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81812ecb)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81815b10)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c7cd)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cf19)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff818287cf)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff818349ff)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81835a3a)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8184d383)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81852890)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81855464)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff8185704a)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8185bd3c)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8185c766)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860364)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81862b13)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff81866e4f)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818684b8)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186bded)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/exthdrs_core.c (ffffffff81871671)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81871f42)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff818725f5)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872cfa)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873a37)
Location: include/linux/skbuff.h:1789
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818786c1)
Location: include/linux/skbuff.h:1789
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In kernel/bpf/core.c (ffffffff8118c2c7)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In security/selinux/hooks.c (ffffffff81394ab3)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813aeb78)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In security/lsm_audit.c (ffffffff813b3037)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81680831)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816845f2)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81689616)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8179c39c)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/datagram.c (ffffffff817a2212)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff817a7fa6)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff817b158e)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff817cb3b5)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff817ce7f8)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff817cea37)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff817d9dbf)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In net/ethernet/eth.c (ffffffff817dc4f6)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/netfilter/core.c (ffffffff817ec999)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/route.c (ffffffff817f27cc)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/ip_input.c (ffffffff817f4d8c)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f58c6)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817f9563)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81804a0d)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818119d5)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c164)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81821c42)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff818240bd)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81828ddd)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81829db6)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8182b6fe)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8182d78d)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8183231e)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81836bde)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843da4)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff818443db)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818472c0)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184e05f)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e7d9)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a1af)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81866497)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8186756a)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8187f23c)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81884590)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff818871d4)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81888e4a)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8188dc3c)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8188e676)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818922f4)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81895123)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff8189954f)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8189b308)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189ec2e)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/exthdrs_core.c (ffffffff818a5bbe)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff818a6522)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6be5)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a731a)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a80b7)
Location: include/linux/skbuff.h:1804
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818acf13)
Location: include/linux/skbuff.h:1804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In kernel/bpf/core.c (ffffffff8118ff61)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In security/selinux/hooks.c (ffffffff813aab5d)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813c3589)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In security/lsm_audit.c (ffffffff813c99eb)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81695c25)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816999ae)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8169ec91)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff817bd2f1)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/datagram.c (ffffffff817bfa6f)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff817c65bd)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff817d1a3a)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff817ea595)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff817edca9)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff817eded3)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff817f8e6e)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In net/ethernet/eth.c (ffffffff817fbb90)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff8180cab8)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff8180cdb3)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/route.c (ffffffff8180fbd2)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/ip_input.c (ffffffff81815220)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81815cd2)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff818199c3)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81824d5f)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81831d44)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c934)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff8184296d)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81844dec)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8184a0b0)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8184b093)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8184cb02)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8184ece5)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81854bde)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff818583ed)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865634)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81865cf0)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81868cb0)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81871c1b)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff818722a9)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e01f)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8188a901)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8188bcfd)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff818a52dc)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff818aa1c0)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff818ad70b)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff818af530)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b42ed)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff818b4cbd)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8953)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb4a3)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff818bf7d9)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818c10a8)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c516c)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/exthdrs_core.c (ffffffff818cc621)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff818ccf7c)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd656)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdd6a)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce8f7)
Location: include/linux/skbuff.h:1797
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d5444)
Location: include/linux/skbuff.h:1797
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
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
In kernel/bpf/sockmap.c (ffffffff811b0dbb)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In security/selinux/hooks.c (ffffffff813d0bbd)
Location: include/linux/skbuff.h:1879
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813e9849)
Location: include/linux/skbuff.h:1879
Inline: True
```
```
In security/lsm_audit.c (ffffffff813efe7b)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff816ff5a0)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8170414e)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81709e31)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818356b1)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/datagram.c (ffffffff8183961f)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff818401bd)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff8184bc8d)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81865d15)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81869ee9)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff8186a117)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81876767)
Location: include/linux/skbuff.h:1879
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81879552)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff8188ba25)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff8188bf93)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/route.c (ffffffff8188f102)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/ip_input.c (ffffffff818943f0)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81894ec3)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81897fd3)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff818a36cf)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:1879
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b0f37)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc085)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff818c22cd)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff818c4852)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c9c60)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff818cacf3)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff818cc7c2)
Location: include/linux/skbuff.h:1879
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff818cea6b)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff818d4a7e)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff818d82bd)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5784)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff818e5e22)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818e91f0)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818f25db)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2c89)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff818fef4f)
Location: include/linux/skbuff.h:1879
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8190badc)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8190cfe8)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/route.c (ffffffff8191a6bd)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81927ccc)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff8192cc31)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff819303eb)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81932246)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8193705d)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81937a2d)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b805)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e4c2)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff819428a9)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819442d8)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8194843c)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/seg6_local.c (ffffffff8194f9e6)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff819513d1)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81951d67)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81952448)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952b86)
Location: include/linux/skbuff.h:1879
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819537a7)
Location: include/linux/skbuff.h:1879
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81959ef4)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff8195b289)
Location: include/linux/skbuff.h:1879
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In kernel/bpf/sockmap.c (ffffffff811cc40a)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_parse_func_strparser
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In security/selinux/hooks.c (ffffffff813fde3d)
Location: include/linux/skbuff.h:1890
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8141a76b)
Location: include/linux/skbuff.h:1890
Inline: True
```
```
In security/lsm_audit.c (ffffffff814213f3)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8173fdb6)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742b8a)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81748bfc)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8187fa55)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/datagram.c (ffffffff81883d78)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff8188a6c3)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff8189601d)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818b5fee)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff818b9bc8)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff818b9dff)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818c7eb0)
Location: include/linux/skbuff.h:1890
Inline: True
```
```
In net/ethernet/eth.c (ffffffff818caf50)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff818df464)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff818dfc04)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/route.c (ffffffff818e498b)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/ip_input.c (ffffffff818e8707)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8f62)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff818ec29d)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef232)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff818f8a42)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:1890
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819065d5)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911a9f)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81917f1e)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff8191a506)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191fd19)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81920c1a)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81922c67)
Location: include/linux/skbuff.h:1890
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81924e45)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8192b19f)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8192dd60)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193c02d)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff8193c68c)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8193fcf0)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948f1f)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff819495ce)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81955a15)
Location: include/linux/skbuff.h:1890
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81963257)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819643ea)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/route.c (ffffffff81975f63)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/ndisc.c (ffffffff8198007a)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81985336)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81989079)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff8198ab98)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198fda2)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819908a8)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994a9b)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819973f8)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81998ea3)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff8199b682)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff8199cd98)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1590)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/seg6_local.c (ffffffff819a8f34)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff819aa97c)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff819ab301)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab9c6)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819ac12c)
Location: include/linux/skbuff.h:1890
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad1d3)
Location: include/linux/skbuff.h:1890
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af192)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff819b49b5)
Location: include/linux/skbuff.h:1890
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
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
In kernel/bpf/cgroup.c (ffffffff811e18b6)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81419cea)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81436b4b)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In security/lsm_audit.c (ffffffff8143da89)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81763dd4)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817673e3)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8176cc9a)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818a06d5)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/datagram.c (ffffffff818a4585)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff818ab6a3)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff818b7e46)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818d7cad)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff818e0979)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff818e0b6c)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffffffff818e5c7b)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/lwt_bpf.c (ffffffff818f100a)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In net/ethernet/eth.c (ffffffff818f60e7)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff8190c049)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/core.c (ffffffff8190c787)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
  - net/netfilter/core.c:skb_make_writable
```
```
In net/ipv4/route.c (ffffffff8191188a)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/ip_input.c (ffffffff81915134)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81916130)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8191943a)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191ca59)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81926772)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819347cf)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940279)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81946662)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81948d5e)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194e983)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8194fe80)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81951a61)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81953c57)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81958e1b)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8195d62a)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bd3c)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff8196c38e)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196f58d)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197abe9)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b298)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a4ef)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81998228)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81999db3)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819abbab)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/ndisc.c (ffffffff819b6660)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff819bbab0)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff819bf9b1)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c1466)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c663c)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c6fef)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb395)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cdcd2)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819cf98b)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff819d1f46)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d45bf)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d81cb)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/seg6_local.c (ffffffff819dfee9)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff819e1467)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff819e1e1b)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff819e254f)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2d06)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3b7d)
Location: include/linux/skbuff.h:1968
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e5b5c)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff819eb9be)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff819ec0bc)
Location: include/linux/skbuff.h:1968
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffff811f8999)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81447747)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8146480d)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In security/lsm_audit.c (ffffffff8146b681)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff817a1e90)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a4bea)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff817aa978)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818eb115)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff818efbc5)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff818f6f2f)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81903cd7)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff819275ed)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff8192f008)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff8192f20e)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffffffff819359c7)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81943710)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81955758)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff8196d733)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81971c35)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff81977648)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978293)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff8197ace5)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197edb9)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81987632)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8199849f)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a47a0)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819aacc3)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819ad3d7)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b316c)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff819b4733)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819b632d)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b854f)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819bd8e6)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819c229a)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a8c)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff819d31a4)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819d8ccd)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e47c8)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e8937)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4746)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff819f83c3)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a021b5)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a05d09)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a14758)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81a250f5)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81a2a6f0)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a2e654)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a3023f)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a3544f)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a362a7)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39ddc)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c8e2)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a3e6a2)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81a40d33)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a4343d)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a4eaf7)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a50225)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a50bba)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51210)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a51a76)
Location: include/linux/skbuff.h:2058
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52907)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81a5558b)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81a5ab50)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81a5b25b)
Location: include/linux/skbuff.h:2058
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffff812059c9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814612d7)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8147e5dd)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/lsm_audit.c (ffffffff81485461)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff817c2b60)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c8cea)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff817ce3a5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8191d275)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81921be5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81928caf)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81936aa9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81959cad)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff8196127c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff8196147e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffffffff819687d7)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81978707)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff8198bbf8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff819a419e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff819a8705)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff819adfd8)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819aec03)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff819b1655)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b61b9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819bddf2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819cf08f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db4a0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1993)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819e4097)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e9eec)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff819eb463)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819ed04d)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819ef24f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819f44f6)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819f8e3a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a095fc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a09d14)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a0fa2e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b7d8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1f947)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b3f6)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f023)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a381c5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c871)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a4b348)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81a5bb75)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81a61240)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a651ba)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a66d8f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a6bf8f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a6cdc7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7096c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a73562)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a75312)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81a779b3)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a79fad)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a85797)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a86e5f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a877aa)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87e30)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a88676)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a894e7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81a8c65b)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81a917a4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81a91e8b)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffff8122cbe5)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814b42c8)
Location: include/linux/skbuff.h:2095
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814d3e7b)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814db5e9)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8188e099)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893651)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff818997fd)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f33b9)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff819f5525)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff819fcc2f)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81a02201)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81a2ce9d)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a3479e)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81a34af5)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/skmsg.c (ffffffff81a3ccc7)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/core/lwt_bpf.c (ffffffff81a4d6a8)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81a637f4)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:2095
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81a7ee78)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81a91db5)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81a97e72)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9901e)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81a9c704)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa0a1d)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81aa8fb2)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/tcp_input.c (ffffffff81ab597f)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81abbf85)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac853b)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf031)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ad1754)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad7aca)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81ad92a4)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81adafa7)
Location: include/linux/skbuff.h:2095
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81add197)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81ae2db7)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ae6d09)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8f16)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81afa4d4)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b032ee)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c878)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11df5)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1dcdf)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21bea)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81b228b9)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ff50)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
```
```
In net/ipv6/ip6_input.c (ffffffff81b31f0f)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b411c8)
Location: include/linux/skbuff.h:2095
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81b548b0)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81b5a690)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b5dacd)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5f812)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b64efc)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b662cd)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a0df)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d9c2)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6f54e)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81b71daa)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b75d98)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78c18)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81b79ea0)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (ffffffff81b80720)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b8210f)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81b82c03)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81b833c5)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83c0a)
Location: include/linux/skbuff.h:2095
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84971)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/packet/af_packet.c (ffffffff81b87a08)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81b8cbd0)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81b8d045)
Location: include/linux/skbuff.h:2095
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
In kernel/bpf/cgroup.c (ffffffff81235061)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814d1a28)
Location: include/linux/skbuff.h:2116
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814f134b)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814f8a79)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8189c5b5)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a1ae1)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff818a7d2d)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f33e9)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff819f4fe5)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff819fc86f)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81a02a01)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81a2e44d)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a36af8)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81a36e35)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/skmsg.c (ffffffff81a3f65b)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
```
In net/core/lwt_bpf.c (ffffffff81a5336f)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81a6b949)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81a6f885)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:2116
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81a886a8)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81a9bc47)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81aa1dd2)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2f8e)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81aa656a)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa9e8d)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81ab34a2)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/tcp_input.c (ffffffff81ac0cdf)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ac76c8)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad44db)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb007)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81add7d4)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae411a)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5cc3)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81ae7a62)
Location: include/linux/skbuff.h:2116
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae8b65)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81aefc88)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81af3bd9)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06ddd)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81b07c78)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b1144e)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1aba8)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b204f5)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c5af)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff81b305ba)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81b31569)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e9f0)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
```
```
In net/ipv6/ip6_input.c (ffffffff81b40b0f)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b4fc88)
Location: include/linux/skbuff.h:2116
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81b62ed0)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81b68d90)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b6c27f)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b6dfb2)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b7369c)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b74a4d)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78bc0)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c472)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b7e07e)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81b80ae4)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b84b08)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87b98)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81b88df0)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ffa0)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b917ff)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81b92283)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81b9299d)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b932ba)
Location: include/linux/skbuff.h:2116
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b942d1)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/packet/af_packet.c (ffffffff81b974e8)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81b9c820)
Location: include/linux/skbuff.h:2116
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81b9cca5)
Location: include/linux/skbuff.h:2116
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
In kernel/bpf/cgroup.c (ffffffff81239750)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814d7ed8)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814f7feb)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814ff843)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8187eb19)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883fbe)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8188c60a)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819d9649)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff819db175)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff819e30df)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff819f25c8)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81a159d0)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a1dc73)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81a1dec1)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/selftests.c (ffffffff81a364eb)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81a38b9c)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81a540b3)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81a58139)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81a71908)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81a86cb7)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81a8cd02)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8df9e)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81a916ea)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95059)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81a9e636)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
```
In net/ipv4/tcp_input.c (ffffffff81aabc8f)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab26d8)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf59e)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6080)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ac88a4)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81acf30a)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0fb0)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81ad2d22)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad41ba)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81adb3d1)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81adf275)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2527)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81af3486)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81aff07e)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b08865)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e3ba)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a20f)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e42e)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81b1f1db)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b7c7)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e3a5)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b3daea)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81b511e0)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81b56e24)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b5a5df)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5c37b)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5edf9)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81b63570)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67713)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6af82)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6cc82)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f705)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b73796)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b76855)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81b77c10)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0d2)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b809ed)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81b813d5)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81bcd)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b8235a)
Location: include/linux/skbuff.h:2132
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b833d8)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81b864e7)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81b8b8e0)
Location: include/linux/skbuff.h:2132
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81b8bd89)
Location: include/linux/skbuff.h:2132
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
In kernel/bpf/cgroup.c (ffffffff81273f6b)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81530e98)
Location: include/linux/skbuff.h:2161
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81552bdb)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff8155a8b3)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8191031b)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191597e)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8191f8c2)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81a89609)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81a8b8f5)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81a9389f)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81aa4498)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81ac6c40)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81ad1713)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81ad1951)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/selftests.c (ffffffff81aec1bb)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81aeea78)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81b0cdc3)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81b1111b)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:2161
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81b2b01f)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81b41477)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81b47e3a)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81b4918e)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81b4caba)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b504b9)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81b5a3f6)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81b680cf)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f578)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d0e6)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84890)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81b8710e)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8dd2a)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f9cd)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81b91972)
Location: include/linux/skbuff.h:2161
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b92eaa)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81b9a781)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81b9e755)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2a37)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3996)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bc225e)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb765)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd18a1)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde82f)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2f1e)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81be3d1b)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1881)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf469b)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81c0434a)
Location: include/linux/skbuff.h:2161
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81c18640)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81c1d044)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81c21c5f)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81c23ab0)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c2659e)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81c2b030)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f343)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c32de2)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81c34b3c)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81c377c2)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff81c38124)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81c3dd66)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c412d5)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81c42730)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a922)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/exthdrs_core.c (ffffffff81c4ca0d)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81c4d3f5)
Location: include/linux/skbuff.h:2161
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dc1d)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e40a)
Location: include/linux/skbuff.h:2161
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f4a8)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81c528a7)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81c57b80)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81c58069)
Location: include/linux/skbuff.h:2161
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffff812c2194)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff815c8388)
Location: include/linux/skbuff.h:2512
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff815ec73d)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff815f5661)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81a67169)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6baed)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81a749b0)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81bfe942)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81c00ff5)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81c09aec)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81c19df1)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81c4269c)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81c4efe1)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81c4f5e7)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81c5446c)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/selftests.c (ffffffff81c6eb54)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81c7192f)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81c936e2)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81c98215)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:2512
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81cb5244)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81ccde77)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81cd50f0)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6f57)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81cda1d5)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdea7c)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81ce8f37)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81cf722f)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81cfec38)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d063)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81d150d4)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81d17dea)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1ee51)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81d20c84)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81d22e61)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81d250de)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81d2cb20)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81d30ac5)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d461fe)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81d470b4)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d52b6d)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61223)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d67a07)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7567f)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a0ce)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81d7ad7d)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a23f)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d439)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81d9e70e)
Location: include/linux/skbuff.h:2512
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81db46c9)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81dbbb94)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81dbea7f)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81dc09dc)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc41f6)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81dc82d9)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd625)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81dd05c2)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81dd24e0)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5354)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff81dd5d44)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81ddad28)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfa63)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81de11dc)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (ffffffff81dea245)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/exthdrs_core.c (ffffffff81dece70)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81ded948)
Location: include/linux/skbuff.h:2512
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee2db)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeccb)
Location: include/linux/skbuff.h:2512
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defee8)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81df58b3)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_parse_headers
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff81df9204)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81df9759)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff81e3aa8d)
Location: include/linux/skbuff.h:2512
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
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
In kernel/bpf/cgroup.c (ffffffff81326994)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff816754a8)
Location: include/linux/skbuff.h:2370
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8169c43d)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff816a6146)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81bf266d)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfea0d)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c08c10)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81dad372)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81db0395)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81db985c)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81dcae71)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81df7cec)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e04091)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81e0458c)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81e09bbc)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/selftests.c (ffffffff81e26894)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e29a1f)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81e4ede9)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81e541c5)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:2370
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81e737a2)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81e8de17)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81e955c0)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81e974f7)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81e9a995)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9e99c)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81eac4b7)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81ebbcbf)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3c28)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2ae1)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb1fb)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ede66a)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee5f61)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7efe)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81eea361)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81eec6be)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81ef43e9)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ef8bd5)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f5de)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81f101a2)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f1cebd)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bb23)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f32a67)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41c9f)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46f19)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81f4809d)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81f581cf)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b520)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81f6d5fe)
Location: include/linux/skbuff.h:2370
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81f84240)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81f8bcb4)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81f8ef6f)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81f91160)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f94356)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81f99069)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e738)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1972)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81fa3960)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6a5d)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff81fa7544)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff81faca38)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1d53)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff81fb363c)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (ffffffff81fbdb05)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/exthdrs_core.c (ffffffff81fc0c60)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81fc1858)
Location: include/linux/skbuff.h:2370
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2860)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2d2b)
Location: include/linux/skbuff.h:2370
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc4008)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81fc9728)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_parse_headers
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff81fcd7e5)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81fcdeb1)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff8201405d)
Location: include/linux/skbuff.h:2370
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
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
In kernel/bpf/helpers.c (ffffffff813217be)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
```
```
In kernel/bpf/cgroup.c (ffffffff81356cde)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff816ad828)
Location: include/linux/skbuff.h:2406
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff816d516d)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff816deb1b)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81c4b327)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81c50bc5)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6406d)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e380)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1d272)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
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
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81e20845)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81e29f0c)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81e3b9fa)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81e6a32c)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:__bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e76870)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81e76ddc)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81e7c382)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/gso.c (ffffffff81e7d671)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_gso_validate_network_len
```
```
In net/core/selftests.c (ffffffff81e9be34)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e9f060)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81eaa489)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81eaf9df)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:2406
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81ecf467)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/utils.c (ffffffff81eea5a5)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
```
```
In net/ipv4/route.c (ffffffff81eec557)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81ef3dc0)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5d27)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81ef9314)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efd19b)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81f0abb7)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81f1a13f)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81f22889)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f317c8)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a316)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81f3d9b8)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81f45761)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81f4778c)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81f49c91)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81f4c4ae)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81f53ce0)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81f58645)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f2ce)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fe92)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7c99d)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b563)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93be6)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa152e)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6919)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff81fa7b9d)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7db6)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb2ee)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81fcd71e)
Location: include/linux/skbuff.h:2406
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81fe4539)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81fec454)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81fef7e3)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81ff1a23)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff4cd6)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff9a39)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff1f4)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820021e2)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/datagram.c (ffffffff8200423f)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff8200726a)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff82007da4)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff8200d448)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012461)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff82013d22)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (ffffffff8201eb25)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/exthdrs_core.c (ffffffff82021bef)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff820227d8)
Location: include/linux/skbuff.h:2406
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff820237de)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023cab)
Location: include/linux/skbuff.h:2406
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff82025028)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff8202bd01)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_parse_headers
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff82049115)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff820497e1)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff82090edd)
Location: include/linux/skbuff.h:2406
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
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
In kernel/bpf/helpers.c (ffffffff81343f57)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
```
```
In kernel/bpf/cgroup.c (ffffffff8137f80e)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff816ea8b8)
Location: include/linux/skbuff.h:2413
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8171151d)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff8171b6eb)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/netkit.c (ffffffff81ce51ef)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81d00ada)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d06c05)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1aa8d)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81d22e1e)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81eda962)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_partial_csum_set
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
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy_headlen
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_trim_rcsum_slow
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81ede715)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81ee7f7c)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81ef9f3a)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81f2924c)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_generic_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:__bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81f36833)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81f36d9c)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81f3c6d2)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_reuse_skb
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/gso.c (ffffffff81f3e5f1)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_gso_validate_network_len
```
```
In net/core/selftests.c (ffffffff81f5e594)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81f617d0)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff81f6cf39)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81f7244e)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:2413
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81f92db7)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/utils.c (ffffffff81fae355)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
```
```
In net/ipv4/route.c (ffffffff81fb05a7)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
```
```
In net/ipv4/ip_input.c (ffffffff81fb7d50)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9cd7)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81fbd231)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc1195)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81fcd4a0)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_advance_to_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81fde90f)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81fe6279)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff79bf)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff82000406)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff82003add)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff8200b8b1)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8200d8cc)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8200fdb1)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff820125be)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8201a0a0)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8201eb05)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820359fe)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff820365c2)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8204309d)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052e95)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e84e)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_device.c (ffffffff82073c09)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/xfrm/espintcp.c (ffffffff82074e5d)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff820853f3)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff820886fe)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff8209af6e)
Location: include/linux/skbuff.h:2413
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff820b2439)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff820ba064)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff820bd3b3)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff820bf622)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c28a6)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c76a9)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdf04)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d0fe2)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/datagram.c (ffffffff820d2fff)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff820d60ca)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/seg6.c (ffffffff820d6cc4)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6.c:seg6_get_srh
```
```
In net/ipv6/ip6mr.c (ffffffff820dc415)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1647)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff820e2e7c)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (ffffffff820edc55)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/exthdrs_core.c (ffffffff820f0d0f)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff820f18f8)
Location: include/linux/skbuff.h:2413
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2932)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2e0b)
Location: include/linux/skbuff.h:2413
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4308)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff820fb7b2)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_parse_headers
  - net/packet/af_packet.c:packet_parse_headers
```
```
In net/strparser/strparser.c (ffffffff8211b495)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff8211bb51)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
```
In net/mctp/route.c (ffffffff821673fd)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_input
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
In kernel/bpf/cgroup.c (ffff80001028e940)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffff80001054e9dc)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (ffff80001056f7ec)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/lsm_audit.c (ffff8000105779a8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffff8000109dd6fc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e3628)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e7c18)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a03108)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffff800010a08c88)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffff800010bb7c90)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffff800010bbc25c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffff800010bc503c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffff800010bd51d4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffff800010bfb920)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffff800010c04b5c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffff800010c04cf8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffff800010c0f2b4)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/core/lwt_bpf.c (ffff800010c1f340)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffff800010c36c68)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffff800010c53730)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffff800010c58014)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffff800010c5e01c)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f804)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffff800010c621f8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffff800010c65e5c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffff800010c6fa78)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c81ec8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e88c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffff800010c95994)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffff800010c98aa8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9f6ec)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffff800010ca0fc4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffff800010ca2ac4)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca5094)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffff800010caa498)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffff800010cae608)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc29a8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffff800010cc2f9c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffff800010ccca2c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7a3c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdb5b4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9c04)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffff800010cedd7c)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cf831c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfdfb8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffff800010d0e3ac)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffff800010d20ec8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffff800010d2449c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffff800010d2b024)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffff800010d2cd00)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d339f8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffff800010d358f4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38e5c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffff800010d3c028)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffff800010d3dce4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffff800010d41014)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffff800010d45be0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/seg6_local.c (ffff800010d51828)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffff800010d534d4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffff800010d54088)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffff800010d549fc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d55224)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffff800010d56310)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffff800010d57e18)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffff800010d5f31c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffff800010d5fb38)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (c04bdb2c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (c0708388)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (c0722e58)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (c072a7cc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (c0ac5ae0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accfe8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ppp/ppp_generic.c (c0addf44)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (c0cd4878)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (c0cd86c8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (c0ce0688)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (c0cef5a8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (c0d15b9c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (c0d1df94)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (c0d1e1bc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (c0d267ac)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
```
```
In net/core/lwt_bpf.c (c0d36f00)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (c0d495a8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (c0d631ec)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (c0d67f50)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (c0d6d904)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c0d6e858)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (c0d7209c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (c0d75a74)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (c0d7ee9c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (c0d89fcc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (c0d90a8c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (c0d9d7d4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (c0da4118)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (c0da6914)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0daca10)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (c0dad3fc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (c0daf928)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (c0db1998)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (c0db6c4c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c0dbc90c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (c0dce1d0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (c0dce8bc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c0dd7034)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (c0de1548)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (c0de6360)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (c0df22b8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_device.c (c0df5fb4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (c0e02a40)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e05538)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c0e14d84)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (c0e27b50)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (c0e2b300)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (c0e2efd4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c0e30d58)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e3668c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c0e37b9c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c0e3b9f4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (c0e3f248)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c0e40f88)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (c0e438f4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c0e465cc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (c0e4ba7c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/seg6_local.c (c0e51fac)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (c0e53e7c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (c0e54854)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (c0e54ff0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (c0e557b4)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (c0e568f4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (c0e59d8c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (c0e5ef90)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (c0e5f6ac)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (c00000000033b1b4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (c0000000006afaa4)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (c0000000006d4d64)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/lsm_audit.c (c0000000006e1080)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (c000000000aa3e10)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa90d8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (c000000000c8fa6c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (c000000000c954f4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (c000000000c9f954)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (c000000000cb45d8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (c000000000ce3dc8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (c000000000ceeb34)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (c000000000ceeec0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (c000000000cf9e00)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
```
```
In net/core/lwt_bpf.c (c000000000d11218)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (c000000000d2f248)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (c000000000d52ea0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (c000000000d5992c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (c000000000d60c48)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c000000000d61dac)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (c000000000d65210)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (c000000000d6a6c4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (c000000000d765b4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8cc74)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d2bc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (c000000000da6c18)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (c000000000daa2b8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db21bc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (c000000000db3ef8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (c000000000db6214)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (c000000000db8ddc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (c000000000dc0568)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c000000000dc69e4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde230)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (c000000000dde688)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c000000000de762c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (c000000000df798c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (c000000000e008f8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (c000000000e0d7a0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/xfrm/xfrm_device.c (c000000000e12978)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (c000000000e2029c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e25d70)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c000000000e3a4dc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (c000000000e501c0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (c000000000e56d20)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (c000000000e5c3d8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c000000000e5e7e0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e660fc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c000000000e679c8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c33c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (c000000000e6fb3c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c000000000e72218)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (c000000000e758a8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c000000000e78e84)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/seg6_local.c (c000000000e89aa4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (c000000000e8bcfc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (c000000000e8cb10)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (c000000000e8d56c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dfac)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f4dc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (c000000000e92f44)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (c000000000e99f08)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (c000000000e9a888)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffe0001c1ad0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffe0003a8ac6)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffe0003c57dc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffe0003c9e96)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffe0006288d4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d530)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffe000747648)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffe00074afd4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffe000751a2c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffe00075ec4c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffe00077d842)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffe00078373e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffe00078395a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffffffe00078ae72)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
```
```
In net/core/lwt_bpf.c (ffffffe000798a9c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffe0007a8644)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffe0007bde84)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffe0007c2294)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffe0007c6bce)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c768e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffe0007c9c18)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd512)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffe0007d4d6c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e39e6)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eeba8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4bec)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffe0007f6b90)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fc22a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd51c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffe0007fea4a)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (ffffffe0008009cc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffe0008052dc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffe0008099d2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817e00)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffe0008184b4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffe00081e2b2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffe0008280dc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082cfe0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffe000837b56)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b3c2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffe000844bae)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe000848052)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffe000855e90)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffe000862e18)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffe000867fdc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffe00086b592)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffe00086cf58)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe000871c38)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffe000872dac)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876250)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffe000878a5e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffe00087a30e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffe00087c6b4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffe00087ed22)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffe000889a02)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffe00088b1c8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffe00088bb94)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c388)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088ca48)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088dbb6)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffe00088fabc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffe000894a2c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffe0008950f2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffff811fdfe9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814598b7)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81476bbd)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/lsm_audit.c (ffffffff8147da41)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81787630)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178d7ca)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81792fc5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818bd275)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff818c1be5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff818c8caf)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff818d6a79)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818f9c7d)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff8190124c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff8190144e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffffffff819087a7)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81918577)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff8192ba68)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff8194400e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81948575)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff8194de48)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ea73)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff819514c5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff81956029)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff8195dc62)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8196eeff)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b310)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff81981803)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81983f07)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989d5c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff8198b2d3)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8198cdf8)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198efef)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81994296)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81998bda)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a939c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff819a9ab4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819af45d)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bae68)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff819befd7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff819caa86)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce6b3)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d7855)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819dbf01)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819ea9d8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff819fb205)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81a008d0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a0484a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a0641f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a0b61f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a0c457)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0fffc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a12bf2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a149a2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81a17043)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a1963d)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a24e27)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a264ef)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a26e3a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a274c0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27d06)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28b77)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81a2bceb)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81a30e34)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81a3151b)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffff811f0d39)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff8144a2e7)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814675dd)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/lsm_audit.c (ffffffff8146e461)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81766f80)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/vxlan.c (ffffffff81773eee)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_err_lookup
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8177659a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In net/core/skbuff.c (ffffffff818771b5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff8187bb25)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81882bef)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff818908b9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818b3aad)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff818bb07c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff818bb27e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffffffff818c25b7)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818d2327)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff818e5818)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff818fdafe)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81902065)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff81907938)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81908563)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff8190afb5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190fb19)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81917752)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819289ef)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934dd0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b2c3)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff8193d9c7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194381c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff81944d93)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819468b8)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81948aaf)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8194dd56)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8195269a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e5c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81963574)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196ba8d)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977c58)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197bdc7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff81987876)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b493)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81994615)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81998cc1)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819a7798)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff819b7fc5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff819bd690)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff819c160a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c31df)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c83df)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c9217)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccdbc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cf9b2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819d1762)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff819d3e03)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d63fd)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819e1be7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff819e32af)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff819e3bfa)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4280)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4ac6)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5d67)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff819e8edb)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff819ee024)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff819ee70b)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffff811fbdb9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81455957)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81472c5d)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/lsm_audit.c (ffffffff81479ae1)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff817b79e0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bdb6a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff817c3225)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8190e275)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81912be5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81919caf)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81927aa9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff8194acad)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff8195227c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff8195247e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffffffff819597d7)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81969707)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff8197cbf8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff8199519e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199d322)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:get_l4proto
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a61d2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_in_window
```
```
In net/netfilter/nf_conntrack_proto_udp.c (ffffffff819a71f2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a7a75)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_pkt_to_tuple
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a8925)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_pkt_to_tuple
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9bd7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819ab0c6)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819ab971)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple
```
```
In net/ipv4/route.c (ffffffff819b2d45)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff819b8618)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9243)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff819bbc95)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c07f9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819c8432)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d96cf)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5ae0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebfd3)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819ee6d7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f452c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff819f5aa3)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff819f768d)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f988f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819feb36)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a0347a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13c3c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a14354)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a19cfd)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a258e8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a29a57)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35506)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39133)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a422d5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a46981)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a55458)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81a65c85)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81a6b350)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a6f2ca)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a70e9f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7609f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a76ed7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7aa7c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d672)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a7f422)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81a81ac3)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a840bd)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f8a7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a91231)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a9209f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a929ea)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a93070)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a938b6)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94727)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81a9789b)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81a9c9e4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81a9d0cb)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In kernel/bpf/cgroup.c (ffffffff8120a999)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81470c47)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8148a54d)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In security/lsm_audit.c (ffffffff81491591)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff817d207c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d839a)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff817dd4e5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8192f3a5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81933d65)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff8193aeef)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81949179)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_network_protocol
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff8196c5bd)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_net_hdr_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/tso.c (ffffffff81973cbc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/sock_reuseport.c (ffffffff81973ec8)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (ffffffff8197b9b7)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff8198bae7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (ffffffff8199f166)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/bpf/test_run.c (ffffffff819b7d1e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff819bc407)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_link_failure
```
```
In net/ipv4/ip_input.c (ffffffff819c1e78)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2b33)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff819c55a5)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/ip_sockglue.c (ffffffff819ca1d9)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819d1f82)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e332f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef7a0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5e83)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819f872d)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fe6ec)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/udp_offload.c (ffffffff819ffca3)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff81a018b1)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a03b7f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81a0a6b0)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a0d9ca)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e61c)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ed58)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a24b1e)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30d78)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a34fe7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40de6)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44b63)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4df65)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a526b1)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a61458)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81a72225)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
```
```
In net/ipv6/udp.c (ffffffff81a77960)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a7b8ef)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a7d4af)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a827cf)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a834f7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a872bc)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a89ec2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a8bce2)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e3c3)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a909ed)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c630)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a9e14f)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a9eaea)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f1c7)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_pull_exthdrs
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9fa06)
Location: include/linux/skbuff.h:2072
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0887)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81aa41bb)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/strparser/strparser.c (ffffffff81aa8bc4)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff81aa92bb)
Location: include/linux/skbuff.h:2072
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
