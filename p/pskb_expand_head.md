# Function: <code>pskb_expand_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817088d0)
Location: net/core/skbuff.c:1190
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_string
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:__skb_gso_segment
  - net/core/netpoll.c:netpoll_start_xmit
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff817088d0-ffffffff81708b15: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81770280)
Location: net/core/skbuff.c:1195
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81770280-ffffffff817704c6: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179d3f0)
Location: net/core/skbuff.c:1195
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8179d3f0-ffffffff8179d636: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bb680)
Location: net/core/skbuff.c:1197
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff817bb680-ffffffff817bb8d5: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818346c0)
Location: net/core/skbuff.c:1441
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818346c0-ffffffff8183498b: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187e5a0)
Location: net/core/skbuff.c:1443
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8187e5a0-ffffffff8187e887: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189f760)
Location: net/core/skbuff.c:1453
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8189f760-ffffffff8189fa38: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e9fa0)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818e9fa0-ffffffff818ea270: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191c120)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8191c120-ffffffff8191c3f0: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eff10)
Location: net/core/skbuff.c:1611
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819eff10-ffffffff819f0275: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819efbc0)
Location: net/core/skbuff.c:1622
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819efbc0-ffffffff819eff25: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d3820)
Location: net/core/skbuff.c:1664
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819d3820-ffffffff819d3b73: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a83590)
Location: net/core/skbuff.c:1685
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:validate_xmit_vlan
  - net/core/dev.c:__skb_gso_segment
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a83590-ffffffff81a838c3: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf8c90)
Location: net/core/skbuff.c:1679
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81bf8c90-ffffffff81bf8fe6: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da7ba0)
Location: net/core/skbuff.c:1878
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__skb_gso_segment
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81da7ba0-ffffffff81da7f0b: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e16630)
Location: net/core/skbuff.c:2030
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/gso.c:__skb_gso_segment
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81e16630-ffffffff81e169f3: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed3a50)
Location: net/core/skbuff.c:2118
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_ensure_writable_head_tail
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:__skb_unclone_keeptruesize
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/gso.c:__skb_gso_segment
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_xmit
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/sched/sch_frag.c:sch_frag_xmit
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81ed3a50-ffffffff81ed3e10: pskb_expand_head (STB_GLOBAL)
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
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb66d8)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffff800010bb66d8-ffff800010bb69b0: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd3578)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
c0cd3578-c0cd382c: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8deb0)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
c000000000c8deb0-c000000000c8e264: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000746430)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffe000746430-ffffffe000746676: pskb_expand_head (STB_GLOBAL)
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
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bc120)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818bc120-ffffffff818bc3f0: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81876060)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/vxlan.c:vxlan_build_skb
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81876060-ffffffff81876330: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190d120)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8190d120-ffffffff8190d3f0: pskb_expand_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pskb_expand_head(struct sk_buff *skb, int nhead, int ntail, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192e250)
Location: net/core/skbuff.c:1612
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_realloc_headroom
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
  - net/core/dev.c:skb_checksum_help
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_grow_rcsum
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netlink/af_netlink.c:netlink_trim
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff8192e250-ffffffff8192e520: pskb_expand_head (STB_GLOBAL)
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
