# Function: <code>netdev_warn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81719f00)
Location: net/core/dev.c:7620
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81719f00-ffffffff81719f83: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817823e0)
Location: net/core/dev.c:8138
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff817823e0-ffffffff81782463: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817afcd0)
Location: net/core/dev.c:8303
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff817afcd0-ffffffff817afd53: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ce540)
Location: net/core/dev.c:8504
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff817ce540-ffffffff817ce5c0: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847dc0)
Location: net/core/dev.c:8687
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff81847dc0-ffffffff81847e40: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890bd0)
Location: net/core/dev.c:8938
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff81890bd0-ffffffff81890c53: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b1ee0)
Location: net/core/dev.c:9571
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff818b1ee0-ffffffff818b1f63: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81907041)
Location: net/core/dev.c:9676
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff81907041-ffffffff819070c4: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81939726)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff81939726-ffffffff819397a9: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0ec21)
Location: net/core/dev.c:10487
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:netdev_fix_features
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff81a0ec21-ffffffff81a0eca4: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c30f15)
Location: net/core/dev.c:11196
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - drivers/net/xen-netfront.c:xennet_xdp
  - net/core/dev.c:netdev_fix_features
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff81c30f15-ffffffff81c30f98: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c2321b)
Location: net/core/dev.c:11474
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - drivers/net/xen-netfront.c:xennet_xdp
  - net/core/dev.c:netdev_fix_features
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81c2321b-ffffffff81c2329e: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81d35ce0)
Location: net/core/dev.c:11481
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:netdev_fix_features
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81d35ce0-ffffffff81d35d63: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81f0241c)
Location: net/core/dev.c:11263
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:netdev_fix_features
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/mctp/device.c:mctp_dev_notify
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff81f0241c-ffffffff81f024c3: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc3e00)
Location: net/core/dev.c:11267
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:netdev_fix_features
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81dc3e00-ffffffff81dc3ea0: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e332a0)
Location: net/core/dev.c:11284
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_register
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - net/core/dev.c:netdev_fix_features
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81e332a0-ffffffff81e33340: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef13d0)
Location: net/core/dev.c:11512
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_register
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - net/core/dev.c:netdev_fix_features
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/core/dev_addr_lists.c:dev_addr_check
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gmcma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gmcma
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81ef13d0-ffffffff81ef1470: netdev_warn (STB_GLOBAL)
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
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd8814)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffff800010bd8814-ffff800010bd88a8: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf30e4)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
c0cf30e4-c0cf3164: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb8288)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
c000000000cb8288-c000000000cb832c: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007614c0)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffe0007614c0-ffffffe00076151c: netdev_warn (STB_GLOBAL)
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
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d96f6)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff818d96f6-ffffffff818d9779: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81893536)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff81893536-ffffffff818935b9: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a726)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff8192a726-ffffffff8192a7a9: netdev_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netdev_warn(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194be4a)
Location: net/core/dev.c:10027
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - net/core/dev.c:__netdev_update_features
  - net/ethernet/eth.c:eth_change_mtu
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
```
**Symbols:**

```
ffffffff8194be4a-ffffffff8194becd: netdev_warn (STB_GLOBAL)
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
