# Function: <code>skb_reserve</code>

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
In drivers/net/tun.c (ffffffff815eef71)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f698c)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:1905
Inline: True
```
```
In net/core/skbuff.c (ffffffff8170739e)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/dev.c (ffffffff81716f8d)
Location: include/linux/skbuff.h:1905
Inline: True
```
```
In net/core/netpoll.c (ffffffff8173936e)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8174c2b5)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/route.c (ffffffff817572c3)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8175c867)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81768f19)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81774b07)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/raw.c (ffffffff817850c5)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8178bae8)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81796229)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv6/ip6_output.c (ffffffff817c666b)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/route.c (ffffffff817d8d25)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff817de87e)
Location: include/linux/skbuff.h:1905
Inline: True
```
```
In net/ipv6/raw.c (ffffffff817e6104)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff817ea0c6)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eef40)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81807528)
Location: include/linux/skbuff.h:1905
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In drivers/net/tun.c (ffffffff8164da90)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81656b10)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/core/skbuff.c (ffffffff817729e9)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff8177ef9e)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a5626)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff817b7fec)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/route.c (ffffffff817c355c)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff817caf43)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff817d5870)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff817e5335)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff817f26c1)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff817f9122)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81804831)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81834643)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/route.c (ffffffff8184276d)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff8184c79e)
Location: include/linux/skbuff.h:2006
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81854572)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81859578)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185d82b)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81879b02)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8188c3e9)
Location: include/linux/skbuff.h:2006
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff8167f7a1)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816847f0)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/core/skbuff.c (ffffffff8179fb80)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff817ac77e)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/core/netpoll.c (ffffffff817d4096)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff817e7acc)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/route.c (ffffffff817f2b4e)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff817fab89)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81805854)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff818157c5)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81823531)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81829ff2)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81835806)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff8186609c)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/route.c (ffffffff818744eb)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff8187e66e)
Location: include/linux/skbuff.h:2023
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81886294)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8188b3a8)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f87e)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff818ae200)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818c0598)
Location: include/linux/skbuff.h:2023
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In drivers/net/tun.c (ffffffff816949f3)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699e01)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2062
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bea72)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff817caec6)
Location: include/linux/skbuff.h:2062
Inline: True
```
```
In net/core/netpoll.c (ffffffff817f33ef)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818077be)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff8180c98e)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81813523)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8181b0f1)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81825cf7)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81835bcf)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff818441dd)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8184b22b)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81856d3a)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff8188ab69)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff818a46ae)
Location: include/linux/skbuff.h:2062
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818aca01)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff818b1119)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b5ef6)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff818d4b99)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818e6f0a)
Location: include/linux/skbuff.h:2062
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff811afbf4)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In drivers/net/tun.c (ffffffff816fead3)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817045b0)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2149
Inline: True
```
```
In net/core/skbuff.c (ffffffff81838365)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff81844756)
Location: include/linux/skbuff.h:2149
Inline: True
```
```
In net/core/netpoll.c (ffffffff8186e7df)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818862e4)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff8188b975)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/route.c (ffffffff81892b73)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8189a094)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff818a3da7)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff818b51cf)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff818c3b29)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cae9b)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff818d6bea)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff8190bd60)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff8192705e)
Location: include/linux/skbuff.h:2149
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192f260)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81933769)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938c95)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81959618)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8196c3ba)
Location: include/linux/skbuff.h:2149
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff811cabd0)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8173e874)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742ad8)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In net/core/skbuff.c (ffffffff8188286c)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff8188f796)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In net/core/netpoll.c (ffffffff818bf98b)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818d9c0f)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff818df39f)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff818ee4e7)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff818f9b08)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8190a74f)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81919738)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819213a9)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff8192d558)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81962e02)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff8197f42e)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81987c3b)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8198c10a)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81992524)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff819b038b)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819c5e65)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff811de4ca)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8176374e)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81767343)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2238
Inline: True
```
```
In net/core/skbuff.c (ffffffff818a3307)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff818af4d3)
Location: include/linux/skbuff.h:2238
Inline: True
```
```
In net/core/netpoll.c (ffffffff818e87ab)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff819066ae)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff8190bebc)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff8191bcab)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp.c (ffffffff81927a38)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819389ef)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff8194800b)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819501b9)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff8195c9f8)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81997deb)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff819b59fe)
Location: include/linux/skbuff.h:2238
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819be557)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff819c2b8c)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8c64)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff819e7b8c)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819fd590)
Location: include/linux/skbuff.h:2238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff811f3d54)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817a1473)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a4b4d)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2326
Inline: True
```
```
In net/core/skbuff.c (ffffffff818ee0e3)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff818fb31b)
Location: include/linux/skbuff.h:2326
Inline: True
```
```
In net/core/netpoll.c (ffffffff81937fbd)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81967952)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff8196d692)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff8197df98)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff8198a910)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8199b93d)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff819ac2d2)
Location: include/linux/skbuff.h:2326
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819b4a79)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff819c16f9)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81a01366)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81a244db)
Location: include/linux/skbuff.h:2326
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2cfa6)
Location: include/linux/skbuff.h:2326
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a319ab)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a375e4)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81a5472b)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a6c7f8)
Location: include/linux/skbuff.h:2326
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff81200af4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817c6433)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c8c4d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/skbuff.c (ffffffff819201d6)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff8192d46b)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/netpoll.c (ffffffff8196ae7d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8199e3e2)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff819a40ff)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff819b4944)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff819c10d4)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d235d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff819e2d74)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819eb7a9)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff819f8299)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81a37f46)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81a5af5b)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a63adb)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a684fb)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e10e)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81a8b31b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aa31b8)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff81227d5b)
Location: include/linux/skbuff.h:2363
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188de5a)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818932d1)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2363
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f37b6)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff81a012b5)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81a3ebd2)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81a77f95)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81a7ec42)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9eb09)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81aac804)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81abf0b2)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81ad063e)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ad9889)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81ae5296)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81b2df56)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81b538db)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c56b)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b617e1)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67e0e)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81b87143)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9e54c)
Location: include/linux/skbuff.h:2363
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
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
In kernel/bpf/cpumap.c (ffffffff8122eabb)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In drivers/net/tun.c (ffffffff8189c366)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a15c1)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2384
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f37e0)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff81a01aa5)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81a41972)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81a80e48)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81a88579)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa8a50)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81ab4157)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81acaa12)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81adc64e)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ae62d9)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81af2165)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c9a6)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81b61e6b)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/raw.c (ffffffff81b6adab)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b6ff63)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7663d)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81b96c9d)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81badf4c)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
```
```
In net/mptcp/protocol.c (ffffffff81bbb04e)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
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
In drivers/net/tun.c (ffffffff8187e8c9)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883c51)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2400
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d9a0a)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff819e8a55)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/core/xdp.c (ffffffff81a1f930)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/netpoll.c (ffffffff81a26432)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81a69601)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81a717d9)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a93b6d)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81a9f2c7)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5a02)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81ac7699)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ad15b9)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81add955)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81b29e16)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81b500db)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/raw.c (ffffffff81b590be)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81b5e228)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64f76)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81b85c9c)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9d758)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/xdp/xsk.c (ffffffff81ba5fad)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81baa5ee)
Location: include/linux/skbuff.h:2400
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
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
In drivers/net/tun.c (ffffffff81910057)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819155fb)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2429
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a899c5)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff81a961f5)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/core/xdp.c (ffffffff81ad38f0)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/netpoll.c (ffffffff81adb1a9)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81b22bbd)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81b2aefa)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4efad)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81b5b077)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81b72a42)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81b85eb9)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81b901e9)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81b9cdec)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81bef9e6)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81c1743b)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/raw.c (ffffffff81c20697)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81c256d8)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d1b6)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81c52042)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81c6acec)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/xdp/xsk.c (ffffffff81c7393c)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81c787f1)
Location: include/linux/skbuff.h:2429
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
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
In drivers/net/tun.c (ffffffff81a63aa5)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6acda)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (ffffffff81a74f03)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:bounce_skb
```
```
In net/core/skbuff.c (ffffffff81bfec58)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/xdp.c (ffffffff81c512ad)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81c53783)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81c5c6b9)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81cab79b)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81cb5105)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cdc90d)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81ce9ad0)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81d020f6)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81d16811)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81d215f9)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81d2eec2)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81d88546)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81db329e)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/raw.c (ffffffff81dbd431)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81dc2e51)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca5c9)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81df4076)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81e0e449)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/xdp/xsk.c (ffffffff81e181f3)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81e1ef6c)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mctp/af_mctp.c (ffffffff81e3723e)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
```
```
In net/mctp/route.c (ffffffff81e38fc4)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffffffff81bf2c85)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfda8c)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (ffffffff81c06c48)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81dad697)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/xdp.c (ffffffff81e06a4a)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81e08e46)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81e12da9)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81e685ae)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81e73663)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9d36d)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81ead80b)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7296)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81edcfc1)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81ee8a09)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81ef6f22)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81f56206)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81f8289e)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/raw.c (ffffffff81f8d971)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81f938a1)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b603)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81fc8e6c)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81fe4889)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/xdp/xsk.c (ffffffff81fef3a3)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ff5b17)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mctp/af_mctp.c (ffffffff8201007e)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
```
```
In net/mctp/route.c (ffffffff820122e4)
Location: include/linux/skbuff.h:2689
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffffffff81c49e61)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81c555ed)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c62e5e)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c688c1)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c33b)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1d5ba)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/xdp.c (ffffffff81e78366)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81e7b566)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81e866d2)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81ec441e)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81ed0b2e)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81efa76b)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81f0bf24)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81f25b58)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81f3c211)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff81f483c9)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81f5699f)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5be6)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81fe2bae)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/raw.c (ffffffff81fee14d)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81ff4200)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffba22)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff82029801)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82060b99)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/xdp/xsk.c (ffffffff8206b39f)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82071c07)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mctp/af_mctp.c (ffffffff8208cca0)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
```
```
In net/mctp/route.c (ffffffff8208f0d4)
Location: include/linux/skbuff.h:2743
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In drivers/net/tun.c (ffffffff81cff7f1)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81d0bc88)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1987e)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (ffffffff81d20ceb)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81edacbe)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/xdp.c (ffffffff81f38326)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81f3b7f6)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/netpoll.c (ffffffff81f486df)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff81f877de)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81f9448e)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbe6ab)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81fcffe4)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81fea518)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff8200233b)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (ffffffff8200e526)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff8201ce40)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff820832b6)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff820b0acb)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/raw.c (ffffffff820bbd25)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff820c1151)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca161)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff820f92bd)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82133ab6)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/xdp/xsk.c (ffffffff8213ec9a)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82145d99)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mctp/af_mctp.c (ffffffff8216316d)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
```
```
In net/mctp/route.c (ffffffff821655b4)
Location: include/linux/skbuff.h:2750
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In kernel/bpf/cpumap.c (ffff8000102881dc)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffff8000109e1544)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6a74)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fcf5c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a03068)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/skbuff.c (ffff800010bbab00)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffff800010bc950c)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/netpoll.c (ffff800010c114dc)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffff800010c4ba10)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffff800010c53548)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffff800010c65110)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffff800010c74004)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffff800010c84ecc)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffff800010c97b7c)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/arp.c (ffff800010ca1330)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffff800010cafe88)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffff800010cf8724)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffff800010d2032c)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d29bcc)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffff800010d2ff14)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffff800010d59e68)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffff800010d74c78)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (c04b84ac)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (c0ac66b4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acb760)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad2ec0)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In drivers/net/ppp/ppp_generic.c (c0adde98)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In net/core/skbuff.c (c0cd7418)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (c0ce4bb0)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/core/netpoll.c (c0d293ac)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (c0d5c2cc)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (c0d62e78)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (c0d74d00)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (c0d8263c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (c0d941c0)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (c0da5974)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/arp.c (c0dae20c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (c0dbb868)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (c0e00fec)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (c0e24f30)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (c0e2d964)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c0e33790)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (c0e38774)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (c0e588d4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (c0e71734)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (c00000000033386c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (c000000000aa3270)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa900c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In net/core/skbuff.c (c000000000c93844)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (c000000000cab2e0)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/netpoll.c (c000000000cfe1ac)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (c000000000d49b78)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (c000000000d52c00)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (c000000000d694ec)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (c000000000d7afa4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (c000000000d90ea4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (c000000000da8ac8)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/arp.c (c000000000db43fc)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (c000000000dc5dbc)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (c000000000e2075c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (c000000000e4eb54)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5a9d8)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (c000000000e61208)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (c000000000e68ff0)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (c000000000e940c4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (c000000000eb45a8)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffe0001bcea6)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffe00062b07e)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d4a2)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In net/core/skbuff.c (ffffffe000749d0c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffe0007561a6)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/netpoll.c (ffffffe00078d698)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffe0007b8f3a)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffe0007bde20)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffe0007cc986)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffe0007d75a8)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6848)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffe0007f5fde)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fd8d6)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffe000808f80)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffe000844480)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffe00086263a)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086a3fa)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffe00086f696)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873e9c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffe00088fd6e)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4c9c)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff811f9114)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8178af13)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178d72d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/skbuff.c (ffffffff818c01d6)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff818cd46b)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/netpoll.c (ffffffff8190ae4d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8193e252)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff81943f6f)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff819547b4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff81960f44)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819721cd)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff81982be4)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8198b609)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81998039)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff819d75d6)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff819fa5eb)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a0316b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a07b8b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d79e)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81a2a9ab)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a42548)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff811ebe64)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff8176a863)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/vxlan.c (ffffffff81773651)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/vxlan.c:neigh_reduce
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817764fd)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In net/core/skbuff.c (ffffffff8187a116)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff8188758b)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/netpoll.c (ffffffff818c4be8)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff818f7d52)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff818fda5f)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff8190e2a4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff8191aa34)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8192bc9d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff8193c6a4)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819450c9)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81951af9)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81994396)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff819b73ab)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bff2b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff819c494b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca55e)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff819e7b9b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819ff138)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff811f6ee4)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817bb2b3)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bdacd)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/skbuff.c (ffffffff819111d6)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff8191e46b)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/netpoll.c (ffffffff8195be7d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff8198f3e2)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff819950ff)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff819bef84)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff819cb714)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819dc99d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff819ed3b4)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819f5de9)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81a028d9)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81a42056)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81a6506b)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6dbeb)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a7260b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7821e)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81a9655b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aae3f8)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/bpf/cpumap.c (ffffffff812051cc)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In drivers/net/tun.c (ffffffff817d42ee)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d82fd)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/skbuff.c (ffffffff81932336)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
```
In net/core/dev.c (ffffffff8193fafb)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/core/netpoll.c (ffffffff8197e25d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netlink/af_netlink.c (ffffffff819b1cc2)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/bpf/test_run.c (ffffffff819b7c7f)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff819c8907)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/tcp.c (ffffffff819d52a4)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e661d)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
```
```
In net/ipv4/raw.c (ffffffff819f7294)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819fffe9)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/igmp.c (ffffffff81a0ce09)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv6/ip6_output.c (ffffffff81a4dce6)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ndisc.c (ffffffff81a7159b)
Location: include/linux/skbuff.h:2340
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7a20b)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/mcast.c (ffffffff81a7ec8a)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8498e)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/packet/af_packet.c (ffffffff81aa31d5)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aba7a8)
Location: include/linux/skbuff.h:2340
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
</details>
</li>
</ul>

## Differences
