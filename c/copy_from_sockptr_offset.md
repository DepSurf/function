# Function: <code>copy_from_sockptr_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e8af7)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
```
```
In net/core/filter.c (ffffffff81a2f092)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/netlink/af_netlink.c (ffffffff81a826ad)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_options.c (ffffffff81aa518c)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa1ce)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81ab3dd9)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_repair_options_est
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0bcf)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffffffff81add3a7)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seticmpfilter
```
```
In net/ipv4/udp.c (ffffffff81adff35)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff81b12fe0)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81b26292)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fe37)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv6/raw.c (ffffffff81b6aa8a)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b758dc)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7fd14)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81b85e52)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b9b990)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:fanout_set_data
```
```
In net/xdp/xsk.c (ffffffff81bb7a98)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
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
In net/core/sock.c (ffffffff819cec24)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
```
```
In net/core/filter.c (ffffffff81a156f2)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/netlink/af_netlink.c (ffffffff81a6b78d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_options.c (ffffffff81a9027c)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9538e)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81a9ef49)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_repair_options_est
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abbbcf)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffffffff81ac70c2)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_setsockopt
```
```
In net/ipv4/udp.c (ffffffff81acabf5)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff81b00e30)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13e32)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e11b)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv6/raw.c (ffffffff81b58a9a)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6430c)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6e828)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81b74b05)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b89e48)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xsk.c (ffffffff81ba6c18)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff81bbc4c5)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
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
In kernel/bpf/syscall.c (ffffffff8123373c)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff8123bc8f)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/bpf_iter.c (ffffffff81252120)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff8126868b)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
```
```
In net/core/sock.c (ffffffff81a7e2c6)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
```
```
In net/core/filter.c (ffffffff81ac7142)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/netlink/af_netlink.c (ffffffff81b24dbd)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_options.c (ffffffff81b4b4ec)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b5070e)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81b6088d)
Location: include/linux/sockptr.h:44
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78da1)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffffffff81b858e2)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_setsockopt
```
```
In net/ipv4/udp.c (ffffffff81b89175)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff81bc2af0)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd7f32)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c15454)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv6/raw.c (ffffffff81c1fd48)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2bbfe)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c36888)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81c3f405)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81c55f58)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xsk.c (ffffffff81c74788)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff81c8c44a)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
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
In net/core/sock.c (ffffffff81bf1e30)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_copy_user_timeval
  - net/core/sock.c:sock_copy_user_timeval
  - net/core/sock.c:sock_copy_user_timeval
```
```
In net/core/filter.c (ffffffff81c42b34)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/netlink/af_netlink.c (ffffffff81cad137)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_options.c (ffffffff81cd89ef)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdece0)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81ce8946)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_repair_options_est
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08f13)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffffffff81d1666a)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_setsockopt
```
```
In net/ipv4/udp.c (ffffffff81d1b7ed)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff81d5785e)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6edfe)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0c50)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv6/raw.c (ffffffff81dbcb5e)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc92c1)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd438d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd9e9)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81df7feb)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xsk.c (ffffffff81e18913)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff81e34283)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
```
In net/mctp/af_mctp.c (ffffffff81e37d0d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_setsockopt
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
In net/core/sock.c (ffffffff81d9ff04)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_copy_user_timeval
  - net/core/sock.c:sock_copy_user_timeval
  - net/core/sock.c:sock_copy_user_timeval
```
```
In net/core/filter.c (ffffffff81dfa0a6)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/netlink/af_netlink.c (ffffffff81e69857)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_options.c (ffffffff81e990df)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1b70)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81eb4299)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_repair_options_est
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece1f3)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffffffff81edca05)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seticmpfilter
```
```
In net/ipv4/udp.c (ffffffff81ee2652)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff81f2214d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a6fe)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f81c3b)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv6/raw.c (ffffffff81f8d3be)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a061)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa59bd)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81fb007d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81fcc64c)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:fanout_set_data
```
```
In net/xdp/xsk.c (ffffffff81fefb73)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff8200d335)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
```
In net/mctp/af_mctp.c (ffffffff82010b5d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int copy_from_sockptr_offset(void *dst, sockptr_t src, size_t offset, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81e0e6c4)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_copy_user_timeval
  - net/core/sock.c:sock_copy_user_timeval
  - net/core/sock.c:sock_copy_user_timeval
```
```
In net/core/filter.c (ffffffff81e6d486)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/netlink/af_netlink.c (ffffffff81ec3870)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_options.c (ffffffff81ef792d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get
```
```
In net/ipv4/ip_sockglue.c (ffffffff81f002f3)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81f12a82)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_repair_options_est
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c9f0)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffffffff81f3b9e5)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seticmpfilter
```
```
In net/ipv4/udp.c (ffffffff81f3f5b0)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff81f81cf2)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a11e)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1f4d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv6/raw.c (ffffffff81feddfa)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffaa00)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8200621d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff820107e2)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff8202d5cf)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:fanout_set_data
```
```
In net/xdp/xsk.c (ffffffff8206bd13)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff82089d1a)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
```
In net/mctp/af_mctp.c (ffffffff8208d350)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/mctp/af_mctp.c:mctp_setsockopt
```
**Symbols:**

```
ffffffff81ec3870-ffffffff81ec38a0: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81f09f00-ffffffff81f09f85: copy_from_sockptr_offset (STB_LOCAL)
ffffffff81f2c9f0-ffffffff81f2ca28: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81f3f5b0-ffffffff81f3f5e0: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81ffaa00-ffffffff81ffaa38: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff8208d350-ffffffff8208d380: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int copy_from_sockptr_offset(void *dst, sockptr_t src, size_t offset, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8138403a)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In net/socket.c (ffffffff81ebd980)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/socket.c:do_sock_getsockopt
```
```
In net/core/sock.c (ffffffff81ecb184)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_copy_user_timeval
  - net/core/sock.c:sock_copy_user_timeval
  - net/core/sock.c:sock_copy_user_timeval
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/filter.c (ffffffff81f2ce86)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/netlink/af_netlink.c (ffffffff81f86c90)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_options.c (ffffffff81fbb8ba)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc4818)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:ip_mcast_join_leave
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81fd669d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_repair_options_est
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1900)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffffffff82001b05)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seticmpfilter
```
```
In net/ipv4/udp.c (ffffffff820054e0)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/ipmr.c (ffffffff82048372)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv4/tcp_ao.c (ffffffff820542f0)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/ipv4/tcp_ao.c:tcp_ao_get_repair
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
```
```
In net/xfrm/xfrm_state.c (ffffffff8206747e)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820afe77)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/raw.c (ffffffff820bba0a)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8680)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d507d)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff820df772)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff820fd04f)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:fanout_set_data
```
```
In net/xdp/xsk.c (ffffffff8213f8e3)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff8215f80a)
Location: include/linux/sockptr.h:44
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
```
In net/mctp/af_mctp.c (ffffffff82163810)
Location: include/linux/sockptr.h:44
Inline: True
Direct callers:
  - net/mctp/af_mctp.c:mctp_setsockopt
```
**Symbols:**

```
ffffffff81ebd980-ffffffff81ebd9b2: copy_from_sockptr_offset.constprop.0.isra.0 (STB_LOCAL)
ffffffff81ec4130-ffffffff81ec4201: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81f86c90-ffffffff81f86cc0: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81fc0d00-ffffffff81fc0d7b: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81fce020-ffffffff81fce0a5: copy_from_sockptr_offset (STB_LOCAL)
ffffffff81ff1900-ffffffff81ff1938: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff820054e0-ffffffff82005510: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff820542f0-ffffffff82054320: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff820ac810-ffffffff820ac88b: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff820c8680-ffffffff820c86b8: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff82163810-ffffffff82163840: copy_from_sockptr_offset.constprop.0 (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
