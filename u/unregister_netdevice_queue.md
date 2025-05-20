# Function: <code>unregister_netdevice_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817178d0)
Location: net/core/dev.c:7242
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff817178d0-ffffffff81717984: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177f8a0)
Location: net/core/dev.c:7760
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8177f8a0-ffffffff8177f9ab: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817acad0)
Location: net/core/dev.c:7931
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff817acad0-ffffffff817acbdb: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cb250)
Location: net/core/dev.c:8125
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff817cb250-ffffffff817cb354: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81844ae0)
Location: net/core/dev.c:8304
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81844ae0-ffffffff81844be4: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818981b0)
Location: net/core/dev.c:8554
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff818981b0-ffffffff818982c5: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ba610)
Location: net/core/dev.c:9184
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff818ba610-ffffffff818ba725: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fcad0)
Location: net/core/dev.c:9289
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff818fcad0-ffffffff818fcbe5: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192f0e0)
Location: net/core/dev.c:9633
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8192f0e0-ffffffff8192f1f2: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e200)
Location: net/core/dev.c:10088
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a0e200-ffffffff81a0e312: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05d70)
Location: net/core/dev.c:10797
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a05d70-ffffffff81a05e82: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ec6f0)
Location: net/core/dev.c:10978
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdevice
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff819ec6f0-ffffffff819ec7b2: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10985
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdevice
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81d361bb-ffffffff81d361d0: unregister_netdevice_queue.cold (STB_LOCAL)
ffffffff81a9d610-ffffffff81a9d6e5: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10765
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdevice
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81f02a29-ffffffff81f02a3e: unregister_netdevice_queue.cold (STB_LOCAL)
ffffffff81c16e50-ffffffff81c16f37: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10760
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdevice
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff820ab9f0-ffffffff820aba05: unregister_netdevice_queue.cold (STB_LOCAL)
ffffffff81dd11f0-ffffffff81dd12db: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10776
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdevice
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8212d12d-ffffffff8212d142: unregister_netdevice_queue.cold (STB_LOCAL)
ffffffff81e41de0-ffffffff81e41ecf: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10987
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_del_link
  - drivers/net/netkit.c:netkit_del_link
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdevice
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8220ee5a-ffffffff8220ee6f: unregister_netdevice_queue.cold (STB_LOCAL)
ffffffff81f00820-ffffffff81f0092f: unregister_netdevice_queue (STB_GLOBAL)
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
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcbf28)
Location: net/core/dev.c:9633
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffff800010bcbf28-ffff800010bcc03c: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce9f98)
Location: net/core/dev.c:9633
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
c0ce9f98-c0cea0cc: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca8950)
Location: net/core/dev.c:9633
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
c000000000ca8950-c000000000ca8aa8: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007597fa)
Location: net/core/dev.c:9633
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffe0007597fa-ffffffe0007598de: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cf0e0)
Location: net/core/dev.c:9633
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff818cf0e0-ffffffff818cf1f2: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889200)
Location: net/core/dev.c:9633
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/vxlan.c:vxlan_exit_batch_net
  - drivers/net/vxlan.c:vxlan_exit_batch_net
  - drivers/net/vxlan.c:vxlan_dellink
  - drivers/net/vxlan.c:__vxlan_dev_create
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ip_tunnel.c:ip_tunnel_newlink
  - net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets
  - net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets
  - net/ipv4/ip_tunnel.c:ip_tunnel_dellink
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81889200-ffffffff81889312: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819200e0)
Location: net/core/dev.c:9633
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff819200e0-ffffffff819201f2: unregister_netdevice_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_queue(struct net_device *dev, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81941e40)
Location: net/core/dev.c:9633
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_nl_dellink
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81941e40-ffffffff81941f52: unregister_netdevice_queue (STB_GLOBAL)
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
