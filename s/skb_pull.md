# Function: <code>skb_pull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned char *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81706a70)
Location: net/core/skbuff.c:1466
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81706a70-ffffffff81706aae: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned char *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176cd80)
Location: net/core/skbuff.c:1471
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8176cd80-ffffffff8176cdbe: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned char *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a200)
Location: net/core/skbuff.c:1471
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8179a200-ffffffff8179a23e: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b98a0)
Location: net/core/skbuff.c:1484
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff817b98a0-ffffffff817b98de: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818327d0)
Location: net/core/skbuff.c:1729
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818327d0-ffffffff8183280c: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187cab0)
Location: net/core/skbuff.c:1731
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8187cab0-ffffffff8187caec: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d920)
Location: net/core/skbuff.c:1741
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8189d920-ffffffff8189d953: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e8900)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff818e8900-ffffffff818e8935: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919d90)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81919d90-ffffffff81919dc5: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f27b5)
Location: net/core/skbuff.c:1899
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive_list
Direct callers:
  - lib/kobject_uevent.c:uevent_net_broadcast
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819eaa20-ffffffff819eaa52: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f27a5)
Location: net/core/skbuff.c:1910
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive_list
Direct callers:
  - lib/kobject_uevent.c:uevent_net_broadcast
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/sched/sch_frag.c:sch_frag_prepare_frag
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819ea760-ffffffff819ea792: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d89d9)
Location: net/core/skbuff.c:1952
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive_list
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/sched/sch_frag.c:sch_frag_prepare_frag
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819d0d20-ffffffff819d0d52: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a88969)
Location: net/core/skbuff.c:2024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive_list
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/sched/sch_frag.c:sch_frag_prepare_frag
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a7fb40-ffffffff81a7fb72: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4d7b)
Location: net/core/skbuff.c:2049
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull_data
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/sched/sch_frag.c:sch_frag_prepare_frag
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81bf4030-ffffffff81bf4072: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2dab)
Location: net/core/skbuff.c:2252
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull_data
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/sched/sch_frag.c:sch_frag_prepare_frag
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_route_input
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81da1e30-ffffffff81da1e72: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1188b)
Location: net/core/skbuff.c:2416
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull_data
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/sched/sch_frag.c:sch_frag_prepare_frag
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_route_input
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81e10680-ffffffff81e106c2: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eceb2b)
Location: net/core/skbuff.c:2504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pull_data
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/sched/sch_frag.c:sch_frag_prepare_frag
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_route_input
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81ecd1a0-ffffffff81ecd1e2: skb_pull (STB_GLOBAL)
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
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb2de0)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffff800010bb2de0-ffff800010bb2e48: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd10dc)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
c0cd10dc-c0cd1130: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8b0a0)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
c000000000c8b0a0-c000000000c8b0f8: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744e5e)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffe000744e5e-ffffffe000744eb2: skb_pull (STB_GLOBAL)
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
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9d90)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff818b9d90-ffffffff818b9dc5: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81873ce0)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81873ce0-ffffffff81873d15: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190ad90)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/netfilter/nfnetlink.c:nfnetlink_rcv
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8190ad90-ffffffff8190adc5: skb_pull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *skb_pull(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192be90)
Location: net/core/skbuff.c:1900
Inline: False
Direct callers:
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/802/fddi.c:fddi_type_trans
  - net/802/fddi.c:fddi_type_trans
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/8021q/vlan_core.c:vlan_do_receive
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8192be90-ffffffff8192bec5: skb_pull (STB_GLOBAL)
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
