# Function: <code>dev_get_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81713680)
Location: net/core/dev.c:847
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:do_sysctl
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:common_lsm_audit
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81713680-ffffffff817136d1: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177b340)
Location: net/core/dev.c:851
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:do_sysctl
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:common_lsm_audit
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff8177b340-ffffffff8177b38b: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a89a0)
Location: net/core/dev.c:850
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:do_sysctl
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:common_lsm_audit
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff817a89a0-ffffffff817a89eb: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c6ff0)
Location: net/core/dev.c:857
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:common_lsm_audit
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff817c6ff0-ffffffff817c703f: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81840bc0)
Location: net/core/dev.c:860
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:common_lsm_audit
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81840bc0-ffffffff81840c1c: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b1f0)
Location: net/core/dev.c:860
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8188b1f0-ffffffff8188b24b: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ac240)
Location: net/core/dev.c:862
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff818ac240-ffffffff818ac29b: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f7ae0)
Location: net/core/dev.c:858
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff818f7ae0-ffffffff818f7b33: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81929860)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81929860-ffffffff819298b3: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02a90)
Location: net/core/dev.c:974
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid_slow
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:mif6_add
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a02a90-ffffffff81a02ada: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0dd5a)
Location: net/core/dev.c:977
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid_slow
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:mif6_add
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a03310-ffffffff81a0336d: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f4a76)
Location: net/core/dev.c:1025
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid_slow
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:mif6_add
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff819e9a30-ffffffff819e9a8d: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa63a6)
Location: net/core/dev.c:901
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid_slow
  - security/lsm_audit.c:dump_common_audit_data
  - net/core/sock.c:sock_set_timestamping
  - net/sched/sch_api.c:tc_dump_tclass
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:mif6_add
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a9a700-ffffffff81a9a75d: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1e14e)
Location: net/core/dev.c:848
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid_slow
  - security/lsm_audit.c:dump_common_audit_data
  - net/core/sock.c:sock_set_timestamping
  - net/sched/sch_api.c:tc_dump_tclass
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:mif6_add
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81c123c0-ffffffff81c12447: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcf58e)
Location: net/core/dev.c:848
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid_slow
  - security/lsm_audit.c:dump_common_audit_data
  - net/core/sock.c:sock_set_timestamping
  - net/sched/sch_api.c:tc_dump_tclass
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:mif6_add
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81dc2840-ffffffff81dc28c7: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e4019e)
Location: net/core/dev.c:849
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_by_index
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_dev_bound_init
  - security/selinux/netif.c:sel_netif_sid_slow
  - security/lsm_audit.c:dump_common_audit_data
  - net/core/sock.c:sock_set_timestamping
  - net/sched/sch_api.c:tc_dump_tclass
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:mif6_add
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81e31cf0-ffffffff81e31d77: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efeb21)
Location: net/core/dev.c:866
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_by_index
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_dev_bound_init
  - security/selinux/netif.c:sel_netif_sid_slow
  - security/lsm_audit.c:dump_common_audit_data
  - net/core/sock.c:sock_set_timestamping
  - net/sched/sch_api.c:tc_dump_tclass
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:mif6_add
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ef0170-ffffffff81ef01f7: dev_get_by_index (STB_GLOBAL)
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
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcc378)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffff800010bcc378-ffff800010bcc408: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce14dc)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
c0ce14dc-c0ce154c: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca9500)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
c000000000ca9500-c000000000ca95c4: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000752608)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffe000752608-ffffffe000752690: dev_get_by_index (STB_GLOBAL)
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
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818c9860)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff818c9860-ffffffff818c98b3: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818837a0)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff818837a0-ffffffff818837f3: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191a860)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8191a860-ffffffff8191a8b3: dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct net_device *dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193ce40)
Location: net/core/dev.c:776
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/netif.c:sel_netif_sid
  - security/lsm_audit.c:dump_common_audit_data
  - net/sched/sch_api.c:tc_dump_tclass
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:vif_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8193ce40-ffffffff8193ceb8: dev_get_by_index (STB_GLOBAL)
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
