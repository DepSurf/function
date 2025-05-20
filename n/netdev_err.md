# Function: <code>netdev_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81719e70)
Location: net/core/dev.c:7619
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - net/core/dev.c:__netdev_update_features
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81719e70-ffffffff81719ef3: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81782350)
Location: net/core/dev.c:8137
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/net-sysfs.c:change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81782350-ffffffff817823d3: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817afc40)
Location: net/core/dev.c:8302
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/net-sysfs.c:change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff817afc40-ffffffff817afcc3: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ce4c0)
Location: net/core/dev.c:8503
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/net-sysfs.c:change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff817ce4c0-ffffffff817ce540: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847d40)
Location: net/core/dev.c:8686
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/net-sysfs.c:change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81847d40-ffffffff81847dc0: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890b40)
Location: net/core/dev.c:8937
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff81890b40-ffffffff81890bc3: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b1e50)
Location: net/core/dev.c:9570
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff818b1e50-ffffffff818b1ed3: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81906fbe)
Location: net/core/dev.c:9675
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81906fbe-ffffffff81907041: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819396a3)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff819396a3-ffffffff81939726: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0eb9e)
Location: net/core/dev.c:10486
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81a0eb9e-ffffffff81a0ec21: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c30e92)
Location: net/core/dev.c:11195
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_create_page_pool
  - drivers/net/xen-netfront.c:xennet_create_page_pool
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81c30e92-ffffffff81c30f15: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c23198)
Location: net/core/dev.c:11473
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/selftests.c:net_selftest
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81c23198-ffffffff81c2321b: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81d35c5d)
Location: net/core/dev.c:11480
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/selftests.c:net_selftest
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81d35c5d-ffffffff81d35ce0: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81f0232c)
Location: net/core/dev.c:11262
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:netdev_rx_csum_fault
  - net/core/dev.c:dev_change_name
  - net/core/selftests.c:net_selftest
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81f0232c-ffffffff81f023d3: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc3cc0)
Location: net/core/dev.c:11266
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:netdev_rx_csum_fault
  - net/core/dev.c:dev_change_name
  - net/core/selftests.c:net_selftest
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81dc3cc0-ffffffff81dc3d60: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e33160)
Location: net/core/dev.c:11283
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_tx_timeout
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_pre_register
  - drivers/net/net_failover.c:net_failover_slave_pre_register
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_change_name
  - net/core/dev_ioctl.c:dev_set_hwtstamp
  - net/core/selftests.c:net_selftest
  - net/core/failover.c:failover_slave_register
  - net/core/failover.c:failover_slave_register
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81e33160-ffffffff81e33200: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef1290)
Location: net/core/dev.c:11511
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_tx_timeout
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_pre_register
  - drivers/net/net_failover.c:net_failover_slave_pre_register
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_change_name
  - net/core/dev_ioctl.c:dev_set_hwtstamp
  - net/core/dev_ioctl.c:dev_set_hwtstamp_phylib
  - net/core/selftests.c:net_selftest
  - net/core/failover.c:failover_slave_register
  - net/core/failover.c:failover_slave_register
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_kill_vid
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81ef1290-ffffffff81ef1330: netdev_err (STB_GLOBAL)
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
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd8780)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_nicpm_speed_set
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/of/of_mdio.c:of_phy_get_and_connect
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffff800010bd8780-ffff800010bd8814: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf3064)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/of/of_mdio.c:of_phy_get_and_connect
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
c0cf3064-c0cf30e4: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb81e4)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/of/of_mdio.c:of_phy_get_and_connect
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
c000000000cb81e4-c000000000cb8288: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000761464)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/of/of_mdio.c:of_phy_get_and_connect
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffe000761464-ffffffe0007614c0: netdev_err (STB_GLOBAL)
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
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d9673)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff818d9673-ffffffff818d96f6: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818934b3)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff818934b3-ffffffff81893536: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a6a3)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff8192a6a3-ffffffff8192a726: netdev_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netdev_err(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194bdc7)
Location: net/core/dev.c:10026
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
  - net/switchdev/switchdev.c:switchdev_port_attr_set_deferred
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-netlink.c:ncsi_unregister_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff8194bdc7-ffffffff8194be4a: netdev_err (STB_GLOBAL)
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
