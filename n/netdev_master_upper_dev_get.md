# Function: <code>netdev_master_upper_dev_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81714510)
Location: net/core/dev.c:4961
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81714510-ffffffff8171456a: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177c380)
Location: net/core/dev.c:5305
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff8177c380-ffffffff8177c3e1: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a9af0)
Location: net/core/dev.c:5480
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff817a9af0-ffffffff817a9b51: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c8350)
Location: net/core/dev.c:5686
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff817c8350-ffffffff817c83b1: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81841ef0)
Location: net/core/dev.c:5827
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81841ef0-ffffffff81841f51: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c270)
Location: net/core/dev.c:5957
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff8188c270-ffffffff8188c2de: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ad3d0)
Location: net/core/dev.c:6532
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff818ad3d0-ffffffff818ad43e: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f8cd0)
Location: net/core/dev.c:6542
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff818f8cd0-ffffffff818f8d3e: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192ae70)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff8192ae70-ffffffff8192aede: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819feb00)
Location: net/core/dev.c:6876
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:pneigh_dump_table
  - net/core/neighbour.c:neigh_dump_table
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff819feb00-ffffffff819feb74: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe790)
Location: net/core/dev.c:7033
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/neighbour.c:pneigh_dump_table
  - net/core/neighbour.c:neigh_dump_table
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff819fe790-ffffffff819fe804: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e5000)
Location: net/core/dev.c:7292
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:nh_dump_filtered
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff819e5000-ffffffff819e5074: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7282
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:nh_dump_filtered
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff81d35821-ffffffff81d3584a: netdev_master_upper_dev_get.cold (STB_LOCAL)
ffffffff81a96ef0-ffffffff81a96f82: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6803
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:nh_dump_filtered
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81f01e0e-ffffffff81f01e37: netdev_master_upper_dev_get.cold (STB_LOCAL)
ffffffff81c0dd50-ffffffff81c0ddf9: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6789
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:nh_dump_filtered
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff820ab190-ffffffff820ab1b9: netdev_master_upper_dev_get.cold (STB_LOCAL)
ffffffff81dbdbe0-ffffffff81dbdc89: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6794
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:nh_dump_filtered
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff8212c839-ffffffff8212c862: netdev_master_upper_dev_get.cold (STB_LOCAL)
ffffffff81e2e430-ffffffff81e2e4d9: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6912
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:nh_dump_filtered
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff8220e578-ffffffff8220e5a1: netdev_master_upper_dev_get.cold (STB_LOCAL)
ffffffff81eec950-ffffffff81eec9f9: netdev_master_upper_dev_get (STB_GLOBAL)
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
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc77b0)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffff800010bc77b0-ffff800010bc7844: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce2c94)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
c0ce2c94-c0ce2d2c: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca2d40)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
c000000000ca2d40-c000000000ca2e10: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000753cdc)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffe000753cdc-ffffffe000753d5e: netdev_master_upper_dev_get (STB_GLOBAL)
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
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cae70)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff818cae70-ffffffff818caede: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884db0)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff81884db0-ffffffff81884e1e: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191be70)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff8191be70-ffffffff8191bede: netdev_master_upper_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct net_device *netdev_master_upper_dev_get(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193d350)
Location: net/core/dev.c:6485
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff8193d350-ffffffff8193d3be: netdev_master_upper_dev_get (STB_GLOBAL)
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
