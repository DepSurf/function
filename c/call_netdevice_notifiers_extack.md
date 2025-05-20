# Function: <code>call_netdevice_notifiers_extack</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b06e2)
Location: net/core/dev.c:1742
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fd438)
Location: net/core/dev.c:1752
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192fa53)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04bf1)
Location: net/core/dev.c:2030
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05211)
Location: net/core/dev.c:2055
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ed4bd)
Location: net/core/dev.c:2124
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9e6dd)
Location: net/core/dev.c:1999
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c173bb)
Location: net/core/dev.c:1974
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc83bb)
Location: net/core/dev.c:1965
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e38770)
Location: net/core/dev.c:1991
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef688b)
Location: net/core/dev.c:1995
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:__netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bccf40)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce8974)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caad08)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075764a)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cfa53)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889b73)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81920a53)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819427e3)
Location: net/core/dev.c:1670
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
  - net/core/dev.c:__dev_open
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:dev_change_name
```
</details>
</li>
</ul>

## Differences
