# Function: <code>skb_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81706830)
Location: net/core/skbuff.c:1009
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:flush_stack
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:flush_stack
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81706830-ffffffff817068ce: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176ec10)
Location: net/core/skbuff.c:1014
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8176ec10-ffffffff8176ecae: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179c0d0)
Location: net/core/skbuff.c:1014
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8179c0d0-ffffffff8179c16e: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817ba3a0)
Location: net/core/skbuff.c:1016
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff817ba3a0-ffffffff817ba43b: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81834fb0)
Location: net/core/skbuff.c:1261
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81834fb0-ffffffff81835067: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187f240)
Location: net/core/skbuff.c:1262
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8187f240-ffffffff8187f2f8: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a0010)
Location: net/core/skbuff.c:1271
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818a0010-ffffffff818a00c2: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818eaa30)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818eaa30-ffffffff818eaaf4: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191cba0)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8191cba0-ffffffff8191cc64: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eee70)
Location: net/core/skbuff.c:1429
Inline: False
Direct callers:
  - kernel/taskstats.c:send_cpu_listeners
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
  - net/netlink/genetlink.c:genlmsg_mcast
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819eee70-ffffffff819eef30: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eeb10)
Location: net/core/skbuff.c:1440
Inline: False
Direct callers:
  - kernel/taskstats.c:send_cpu_listeners
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
  - net/netlink/genetlink.c:genlmsg_mcast
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819eeb10-ffffffff819eebd0: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d4510)
Location: net/core/skbuff.c:1482
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819d4510-ffffffff819d45cf: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a84260)
Location: net/core/skbuff.c:1503
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a84260-ffffffff81a8431f: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf9c30)
Location: net/core/skbuff.c:1497
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81bf9c30-ffffffff81bf9cf1: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da8ae0)
Location: net/core/skbuff.c:1695
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81da8ae0-ffffffff81da8bae: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e17960)
Location: net/core/skbuff.c:1847
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81e17960-ffffffff81e17a2e: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed4d50)
Location: net/core/skbuff.c:1935
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81ed4d50-ffffffff81ed4e1e: skb_clone (STB_GLOBAL)
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
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb7188)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffff800010bb7188-ffff800010bb7354: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd3f80)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
c0cd3f80-c0cd4064: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8ecc0)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
c000000000c8ecc0-c000000000c8edfc: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000746d0c)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffe000746d0c-ffffffe000746e9c: skb_clone (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bcba0)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818bcba0-ffffffff818bcc64: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81876ae0)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - drivers/net/vxlan.c:vxlan_xmit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81876ae0-ffffffff81876ba4: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190dba0)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8190dba0-ffffffff8190dc64: skb_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *skb_clone(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192ecd0)
Location: net/core/skbuff.c:1430
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:bpf_clone_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8192ecd0-ffffffff8192ed94: skb_clone (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
