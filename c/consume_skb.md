# Function: <code>consume_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81706480)
Location: net/core/skbuff.c:747
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_skb
  - kernel/audit.c:kauditd_thread
  - ipc/mqueue.c:SyS_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:free_unused_bufs
  - drivers/net/virtio_net.c:free_unused_bufs
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:skb_free_datagram
  - net/core/dev.c:__dev_kfree_skb_any
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81706480-ffffffff81706504: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176e510)
Location: net/core/skbuff.c:748
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_skb
  - ipc/mqueue.c:SyS_mq_notify
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
**Symbols:**

```
ffffffff8176e510-ffffffff8176e58e: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179b9d0)
Location: net/core/skbuff.c:748
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_unicast_skb
  - ipc/mqueue.c:SyS_mq_notify
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
**Symbols:**

```
ffffffff8179b9d0-ffffffff8179ba4e: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bd890)
Location: net/core/skbuff.c:742
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
**Symbols:**

```
ffffffff817bd890-ffffffff817bd90d: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833cb0)
Location: net/core/skbuff.c:695
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81833cb0-ffffffff81833d38: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187e140)
Location: net/core/skbuff.c:695
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:free_sg
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8187e140-ffffffff8187e1c7: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189ed00)
Location: net/core/skbuff.c:699
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8189ed00-ffffffff8189ed87: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e9540)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818e9540-ffffffff818e95c7: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191b6a0)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8191b6a0-ffffffff8191b727: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed540)
Location: net/core/skbuff.c:831
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect_map
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output_gso
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
**Symbols:**

```
ffffffff819ed540-ffffffff819ed5f8: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed210)
Location: net/core/skbuff.c:842
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect_map
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output_gso
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819ed210-ffffffff819ed2b5: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d54a0)
Location: net/core/skbuff.c:890
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:__sk_msg_free
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819d54a0-ffffffff819d5545: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a85130)
Location: net/core/skbuff.c:906
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - ipc/mqueue.c:do_mq_notify
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:msg_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:validate_xmit_vlan
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:run_bpf_filter
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:__sk_msg_free
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81a85130-ffffffff81a851d2: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfb150)
Location: net/core/skbuff.c:911
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - ipc/mqueue.c:do_mq_notify
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/gro.c:napi_reuse_skb
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:__sk_msg_free
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_destructor
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff81bfb150-ffffffff81bfb226: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da9e50)
Location: net/core/skbuff.c:1092
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/gro.c:napi_reuse_skb
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:__sk_msg_free
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp.c:tcp_read_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:queue_oob
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_destructor
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/mctp/route.c:mctp_do_fragment_route
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81da9e50-ffffffff81da9f2b: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e18be0)
Location: net/core/skbuff.c:1232
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/gro.c:napi_reuse_skb
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:__sk_msg_free
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:queue_oob
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_destructor
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/mctp/route.c:mctp_do_fragment_route
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81e18be0-ffffffff81e18cc9: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed6070)
Location: net/core/skbuff.c:1318
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/gro.c:napi_reuse_skb
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:__sk_msg_free
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:queue_oob
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_destructor
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/xdp/xsk.c:xsk_consume_skb
  - net/mctp/route.c:mctp_do_fragment_route
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81ed6070-ffffffff81ed6159: consume_skb (STB_GLOBAL)
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
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb5b98)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff800010bb5b98-ffff800010bb5c5c: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd2b94)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c0cd2b94-c0cd2c64: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8cfc0)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:exit_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000c8cfc0-c000000000c8d104: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000745aa0)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:__se_sys_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe000745aa0-ffffffe000745b52: consume_skb (STB_GLOBAL)
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
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bb6a0)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818bb6a0-ffffffff818bb727: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818755e0)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818755e0-ffffffff81875667: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190c6a0)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8190c6a0-ffffffff8190c727: consume_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void consume_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192d7d0)
Location: net/core/skbuff.c:832
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_kfree_skb_any
  - net/core/neighbour.c:neigh_probe
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/sock_reuseport.c:reuseport_select_sock
  - net/core/skmsg.c:__sk_msg_free
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8192d7d0-ffffffff8192d870: consume_skb (STB_GLOBAL)
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
