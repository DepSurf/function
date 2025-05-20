# Function: <code>netdev_master_upper_dev_get_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81714140)
Location: net/core/dev.c:5149
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81714140-ffffffff8171419d: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177bf50)
Location: net/core/dev.c:5539
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/l3mdev/l3mdev.c:l3mdev_get_saddr6
  - net/l3mdev/l3mdev.c:l3mdev_get_rt6_dst
```
**Symbols:**

```
ffffffff8177bf50-ffffffff8177bfad: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a96e0)
Location: net/core/dev.c:5786
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff817a96e0-ffffffff817a973d: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c7cf0)
Location: net/core/dev.c:5992
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff817c7cf0-ffffffff817c7d22: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81841860)
Location: net/core/dev.c:6133
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff81841860-ffffffff818418bd: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b7f0)
Location: net/core/dev.c:6263
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff8188b7f0-ffffffff8188b84d: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ac970)
Location: net/core/dev.c:6838
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff818ac970-ffffffff818ac9d0: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f8760)
Location: net/core/dev.c:6848
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff818f8760-ffffffff818f87c4: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a900)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff8192a900-ffffffff8192a964: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe630)
Location: net/core/dev.c:7449
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff819fe630-ffffffff819fe692: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe220)
Location: net/core/dev.c:7623
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff819fe220-ffffffff819fe282: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e4ac0)
Location: net/core/dev.c:7882
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff819e4ac0-ffffffff819e4afc: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7872
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/filter.c:xdp_master_redirect
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff81d357b9-ffffffff81d357ce: netdev_master_upper_dev_get_rcu.cold (STB_LOCAL)
ffffffff81a96c60-ffffffff81a96ca6: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7403
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/filter.c:xdp_master_redirect
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_fib_table_rcu
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
  - net/l3mdev/l3mdev.c:l3mdev_master_ifindex_rcu
```
**Symbols:**

```
ffffffff81f01da5-ffffffff81f01dba: netdev_master_upper_dev_get_rcu.cold (STB_LOCAL)
ffffffff81c0da60-ffffffff81c0dab6: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7389
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/filter.c:xdp_master_redirect
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_fib_table_rcu
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
  - net/l3mdev/l3mdev.c:l3mdev_master_ifindex_rcu
```
**Symbols:**

```
ffffffff820ab104-ffffffff820ab119: netdev_master_upper_dev_get_rcu.cold (STB_LOCAL)
ffffffff81dbd650-ffffffff81dbd6a6: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7394
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/filter.c:xdp_master_redirect
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/output_core.c:__ip6_local_out
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_fib_table_rcu
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
  - net/l3mdev/l3mdev.c:l3mdev_master_ifindex_rcu
```
**Symbols:**

```
ffffffff8212c7ad-ffffffff8212c7c2: netdev_master_upper_dev_get_rcu.cold (STB_LOCAL)
ffffffff81e2de80-ffffffff81e2deea: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7512
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/filter.c:xdp_master_redirect
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/udp.c:udp4_lib_lookup_skb
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/udp.c:udp6_lib_lookup_skb
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/output_core.c:__ip6_local_out
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_fib_table_rcu
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
  - net/l3mdev/l3mdev.c:l3mdev_master_ifindex_rcu
```
**Symbols:**

```
ffffffff8220e4d7-ffffffff8220e4ec: netdev_master_upper_dev_get_rcu.cold (STB_LOCAL)
ffffffff81eec260-ffffffff81eec2ca: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
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
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc7230)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffff800010bc7230-ffff800010bc72b0: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce27ac)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
c0ce27ac-c0ce2828: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca2070)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/8021q/vlan_core.c:__vlan_find_dev_deep_rcu
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
c000000000ca2070-c000000000ca20f8: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075374a)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffe00075374a-ffffffe000753798: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
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
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ca900)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff818ca900-ffffffff818ca964: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884840)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff81884840-ffffffff818848a4: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191b900)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff8191b900-ffffffff8191b964: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193cc50)
Location: net/core/dev.c:7058
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/output_core.c:__ip6_local_out
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff8193cc50-ffffffff8193ccb4: netdev_master_upper_dev_get_rcu (STB_GLOBAL)
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
