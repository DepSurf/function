# Function: <code>synchronize_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716450)
Location: net/core/dev.c:7219
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_remove_pack
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_del_offload
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81716450-ffffffff81716475: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e330)
Location: net/core/dev.c:7737
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff8177e330-ffffffff8177e355: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817abb30)
Location: net/core/dev.c:7908
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff817abb30-ffffffff817abb55: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ca0c0)
Location: net/core/dev.c:8102
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
```
**Symbols:**

```
ffffffff817ca0c0-ffffffff817ca0e5: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818439e0)
Location: net/core/dev.c:8281
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_register_net_hook
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
```
**Symbols:**

```
ffffffff818439e0-ffffffff81843a05: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188dd90)
Location: net/core/dev.c:8531
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
```
**Symbols:**

```
ffffffff8188dd90-ffffffff8188ddb5: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818aec80)
Location: net/core/dev.c:9161
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff818aec80-ffffffff818aeca5: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fa830)
Location: net/core/dev.c:9266
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff818fa830-ffffffff818fa855: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192c970)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff8192c970-ffffffff8192c995: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04bce)
Location: net/core/dev.c:10065
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81a00140-ffffffff81a00165: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a051ee)
Location: net/core/dev.c:10774
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:free_netdev
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_set_data
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81a00230-ffffffff81a00255: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ed49e)
Location: net/core/dev.c:10955
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff819e66b0-ffffffff819e66d5: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9e6be)
Location: net/core/dev.c:10962
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81a96c30-ffffffff81a96c55: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1739c)
Location: net/core/dev.c:10742
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_pack
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/gro.c:dev_remove_offload
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81c0da20-ffffffff81c0da51: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc839c)
Location: net/core/dev.c:10737
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_pack
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/gro.c:dev_remove_offload
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81dbd600-ffffffff81dbd631: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e38751)
Location: net/core/dev.c:10753
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_pack
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_free_queues
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/gro.c:dev_remove_offload
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81e2de30-ffffffff81e2de61: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef6865)
Location: net/core/dev.c:10964
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_pack
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_free_queues
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/gro.c:dev_remove_offload
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81eec1a0-ffffffff81eec1d1: synchronize_net (STB_GLOBAL)
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
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc8f48)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffff800010bc8f48-ffff800010bc8f7c: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce51a0)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
c0ce51a0-c0ce51d4: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca5af0)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
c000000000ca5af0-c000000000ca5b58: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007556c6)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffe0007556c6-ffffffe00075570a: synchronize_net (STB_GLOBAL)
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
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cc970)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff818cc970-ffffffff818cc995: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81886a00)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/vxlan.c:vxlan_sock_release
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/ip_tunnel.c:ip_tunnel_encap_del_ops
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff81886a00-ffffffff81886a25: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191d970)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netfilter/nfnetlink.c:nfnetlink_net_exit_batch
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_cleanup_net_list
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_destroy
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff8191d970-ffffffff8191d995: synchronize_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void synchronize_net();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193ee80)
Location: net/core/dev.c:9610
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_free
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__unregister_prot_hook
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff8193ee80-ffffffff8193eea0: synchronize_net (STB_GLOBAL)
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
