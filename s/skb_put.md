# Function: <code>skb_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817059a0)
Location: net/core/skbuff.c:1425
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_string
  - ipc/mqueue.c:SyS_mq_notify
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:__nla_reserve_nohdr
  - lib/nlattr.c:nla_append
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/netpoll.c:netpoll_send_udp
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ndisc.c:ndisc_fill_addr_option
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff817059a0-ffffffff817059ed: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c670)
Location: net/core/skbuff.c:1430
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:SyS_mq_notify
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
```
**Symbols:**

```
ffffffff8176c670-ffffffff8176c6bd: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799840)
Location: net/core/skbuff.c:1430
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:SyS_mq_notify
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
```
**Symbols:**

```
ffffffff81799840-ffffffff8179988d: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b8820)
Location: net/core/skbuff.c:1443
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff817b8820-ffffffff817b886d: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818311e0)
Location: net/core/skbuff.c:1688
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818311e0-ffffffff8183122d: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1690
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81883494-ffffffff818834a4: skb_put.cold.86 (STB_LOCAL)
ffffffff8187b690-ffffffff8187b6d1: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8189c509)
Location: net/core/skbuff.c:1700
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff818a3ee5-ffffffff818a3ef5: skb_put.cold.87 (STB_LOCAL)
ffffffff8189c4d0-ffffffff8189c50b: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818e6d8d)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff818eed0a-ffffffff818eed27: skb_put.cold (STB_LOCAL)
ffffffff818e6d50-ffffffff818e6d8f: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8191916d)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81920ce6-ffffffff81920d03: skb_put.cold (STB_LOCAL)
ffffffff81919130-ffffffff8191916f: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819ec788)
Location: net/core/skbuff.c:1858
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:pskb_put
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - lib/kobject_uevent.c:uevent_net_broadcast
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff819f4a1f-ffffffff819f4a2f: skb_put.cold (STB_LOCAL)
ffffffff819ea4c0-ffffffff819ea4fe: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819ec448)
Location: net/core/skbuff.c:1869
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:pskb_put
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - lib/kobject_uevent.c:uevent_net_broadcast
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/netlink/af_netlink.c:netlink_dump_done
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81c30998-ffffffff81c309a8: skb_put.cold (STB_LOCAL)
ffffffff819ea1f0-ffffffff819ea22e: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819d2945)
Location: net/core/skbuff.c:1911
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:pskb_put
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/netlink/af_netlink.c:netlink_dump_done
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81c22c7b-ffffffff81c22c8f: skb_put.cold (STB_LOCAL)
ffffffff819d07b0-ffffffff819d07e6: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81a82f66)
Location: net/core/skbuff.c:1983
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/netlink/af_netlink.c:netlink_dump_done
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81d350d3-ffffffff81d350e7: skb_put.cold (STB_LOCAL)
ffffffff81a7fb00-ffffffff81a7fb36: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf7a24)
Location: net/core/skbuff.c:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/xen-netfront.c:bounce_skb
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/netlink/af_netlink.c:netlink_dump_done
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff81f0119c-ffffffff81f011b0: skb_put.cold (STB_LOCAL)
ffffffff81bf3fe0-ffffffff81bf4022: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da6784)
Location: net/core/skbuff.c:2211
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_do_fragment_route
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81da1dc0-ffffffff81da1e12: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e15b79)
Location: net/core/skbuff.c:2375
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_do_fragment_route
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81e10610-ffffffff81e10662: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed2f36)
Location: net/core/skbuff.c:2463
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:xsk_build_skb
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_do_fragment_route
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81ecd130-ffffffff81ecd182: skb_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb2168)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffff800010bb2168-ffff800010bb21f0: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf95c)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
c0ccf95c-c0ccf9bc: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87e00)
Location: net/core/skbuff.c:1859
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
c000000000c87e00-c000000000c87e8c: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007438bc)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:__se_sys_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffe0007438bc-ffffffe00074392a: skb_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818b916d)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff818c0ce6-ffffffff818c0d03: skb_put.cold (STB_LOCAL)
ffffffff818b9130-ffffffff818b916f: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818730bd)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff8187ac26-ffffffff8187ac43: skb_put.cold (STB_LOCAL)
ffffffff81873080-ffffffff818730bf: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8190a16d)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - net/xdp/xsk.c:__xsk_sendmsg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81911ce6-ffffffff81911d03: skb_put.cold (STB_LOCAL)
ffffffff8190a130-ffffffff8190a16f: skb_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *skb_put(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8192b26d)
Location: net/core/skbuff.c:1859
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - ipc/mqueue.c:do_mq_notify
  - lib/nlattr.c:nla_append
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:__nla_reserve
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/netlink/af_netlink.c:__nlmsg_put
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/arp.c:arp_create
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:__ndisc_fill_addr_option
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81932e46-ffffffff81932e63: skb_put.cold (STB_LOCAL)
ffffffff8192b230-ffffffff8192b26f: skb_put (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned char *</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
