# Function: <code>call_netdevice_notifiers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817147f0)
Location: net/core/dev.c:1653
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff817147f0-ffffffff8171482b: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817877a2)
Location: net/core/dev.c:1657
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_tx_queue_len
```
**Symbols:**

```
ffffffff8177c780-ffffffff8177c7bb: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b4d62)
Location: net/core/dev.c:1656
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_tx_queue_len
```
**Symbols:**

```
ffffffff817a9ef0-ffffffff817a9f2b: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d38f7)
Location: net/core/dev.c:1690
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_tx_queue_len
```
**Symbols:**

```
ffffffff817c8540-ffffffff817c857b: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184ddd0)
Location: net/core/dev.c:1703
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_tx_queue_len
```
**Symbols:**

```
ffffffff81842170-ffffffff818421b7: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188fd7b)
Location: net/core/dev.c:1747
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8188c580-ffffffff8188c5c7: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b06e2)
Location: net/core/dev.c:1763
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff818ad760-ffffffff818ad7a7: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fd438)
Location: net/core/dev.c:1773
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff818f9070-ffffffff818f90b7: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192fa53)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8192b1d0-ffffffff8192b217: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04bf1)
Location: net/core/dev.c:2051
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff819feeb0-ffffffff819feef7: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05211)
Location: net/core/dev.c:2076
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff819feb60-ffffffff819feba7: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ed4bd)
Location: net/core/dev.c:2145
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff819e5400-ffffffff819e5447: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9e6dd)
Location: net/core/dev.c:2020
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81a97130-ffffffff81a97177: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c173bb)
Location: net/core/dev.c:1995
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81c0e060-ffffffff81c0e0b1: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc83bb)
Location: net/core/dev.c:1986
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81dbe000-ffffffff81dbe051: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e38770)
Location: net/core/dev.c:2012
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/xdp.c:xdp_features_clear_redirect_target
  - net/core/xdp.c:xdp_features_set_redirect_target
```
**Symbols:**

```
ffffffff81e37ee0-ffffffff81e37f31: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef688b)
Location: net/core/dev.c:2016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/dev_addr_lists.c:dev_addr_add
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/xdp.c:xdp_features_clear_redirect_target
  - net/core/xdp.c:xdp_features_set_redirect_target
```
**Symbols:**

```
ffffffff81ef5f30-ffffffff81ef5f81: call_netdevice_notifiers (STB_GLOBAL)
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
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bccf40)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffff800010bc7af0-ffff800010bc7b54: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce8974)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
c0ce3148-c0ce31b0: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caad08)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
c000000000ca32f0-c000000000ca335c: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075764a)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffe000754086-ffffffe0007540c2: call_netdevice_notifiers (STB_GLOBAL)
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
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cfa53)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff818cb1d0-ffffffff818cb217: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889b73)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81885110-ffffffff81885157: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81920a53)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8191c1d0-ffffffff8191c217: call_netdevice_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int call_netdevice_notifiers(long unsigned int val, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819427e3)
Location: net/core/dev.c:1691
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_del
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8193d6b0-ffffffff8193d6f7: call_netdevice_notifiers (STB_GLOBAL)
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
