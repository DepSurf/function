# Function: <code>call_netdevice_notifiers_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct net_device *dev, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81714790)
Location: net/core/dev.c:1635
Inline: False
Direct callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
```
**Symbols:**

```
ffffffff81714790-ffffffff817147eb: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct net_device *dev, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177c720)
Location: net/core/dev.c:1639
Inline: False
Direct callers:
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
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8177c720-ffffffff8177c77b: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct net_device *dev, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a9e90)
Location: net/core/dev.c:1638
Inline: False
Direct callers:
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
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff817a9e90-ffffffff817a9eeb: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct net_device *dev, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c84e0)
Location: net/core/dev.c:1672
Inline: False
Direct callers:
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
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff817c84e0-ffffffff817c853b: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81842110)
Location: net/core/dev.c:1687
Inline: False
Direct callers:
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
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81842110-ffffffff81842161: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c520)
Location: net/core/dev.c:1731
Inline: False
Direct callers:
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
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8188c520-ffffffff8188c57e: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ad700)
Location: net/core/dev.c:1735
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff818ad700-ffffffff818ad75e: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f9010)
Location: net/core/dev.c:1745
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff818f9010-ffffffff818f9070: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192b170)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8192b170-ffffffff8192b1d0: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fee20)
Location: net/core/dev.c:2012
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff819fee20-ffffffff819feea3: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fead0)
Location: net/core/dev.c:2037
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff819fead0-ffffffff819feb53: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e5370)
Location: net/core/dev.c:2106
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff819e5370-ffffffff819e53f3: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1981
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81a97090-ffffffff81a97126: call_netdevice_notifiers_info (STB_LOCAL)
ffffffff81d3585f-ffffffff81d35874: call_netdevice_notifiers_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1930
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_get_stats
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81c0dfc0-ffffffff81c0e060: call_netdevice_notifiers_info (STB_LOCAL)
ffffffff81f01e61-ffffffff81f01e76: call_netdevice_notifiers_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1921
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_get_stats
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81dbdf50-ffffffff81dbdff0: call_netdevice_notifiers_info (STB_LOCAL)
ffffffff820ab1e3-ffffffff820ab1f8: call_netdevice_notifiers_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1947
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_get_stats
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8212cbfb-ffffffff8212cc10: call_netdevice_notifiers_info.cold (STB_LOCAL)
ffffffff81e37d80-ffffffff81e37e20: call_netdevice_notifiers_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1951
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_get_stats
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8220e939-ffffffff8220e94e: call_netdevice_notifiers_info.cold (STB_LOCAL)
ffffffff81ef5dd0-ffffffff81ef5e70: call_netdevice_notifiers_info (STB_GLOBAL)
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc7a70)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffff800010bc7a70-ffff800010bc7af0: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce30c0)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
c0ce30c0-c0ce3148: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca3240)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
c000000000ca3240-c000000000ca32f0: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075400e)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffe00075400e-ffffffe000754086: call_netdevice_notifiers_info (STB_LOCAL)
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
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cb170)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff818cb170-ffffffff818cb1d0: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818850b0)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff818850b0-ffffffff81885110: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191c170)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8191c170-ffffffff8191c1d0: call_netdevice_notifiers_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_netdevice_notifiers_info(long unsigned int val, struct netdev_notifier_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193d650)
Location: net/core/dev.c:1663
Inline: False
Direct callers:
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
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:netdev_lower_state_changed
  - net/core/dev.c:netdev_bonding_info_change
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8193d650-ffffffff8193d6b0: call_netdevice_notifiers_info (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>val, dev, info</code> ➡️ <code>val, info</code>
</li>
</ul>
</details>
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
