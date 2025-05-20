# Function: <code>netdev_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171a020)
Location: net/core/dev.c:7622
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8171a020-ffffffff8171a0a3: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81782500)
Location: net/core/dev.c:8140
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81782500-ffffffff81782583: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817afdf0)
Location: net/core/dev.c:8305
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff817afdf0-ffffffff817afe73: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ce640)
Location: net/core/dev.c:8506
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff817ce640-ffffffff817ce6c0: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847ec0)
Location: net/core/dev.c:8689
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
**Symbols:**

```
ffffffff81847ec0-ffffffff81847f40: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890cf0)
Location: net/core/dev.c:8940
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81890cf0-ffffffff81890d73: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b2000)
Location: net/core/dev.c:9573
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff818b2000-ffffffff818b2083: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81907147)
Location: net/core/dev.c:9678
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81907147-ffffffff819071ca: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193982c)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff8193982c-ffffffff819398af: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0ed3c)
Location: net/core/dev.c:10489
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81a0ed3c-ffffffff81a0edbf: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c31030)
Location: net/core/dev.c:11198
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81c31030-ffffffff81c310b3: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c23336)
Location: net/core/dev.c:11476
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81c23336-ffffffff81c233b9: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81d35dfb)
Location: net/core/dev.c:11483
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81d35dfb-ffffffff81d35e7e: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81f0257f)
Location: net/core/dev.c:11265
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81f0257f-ffffffff81f02626: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc4300)
Location: net/core/dev.c:11269
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81dc4300-ffffffff81dc43a0: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e337e0)
Location: net/core/dev.c:11286
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/net_failover.c:net_failover_slave_unregister
  - drivers/net/net_failover.c:net_failover_slave_register
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/failover.c:failover_unregister
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81e337e0-ffffffff81e33880: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef1910)
Location: net/core/dev.c:11514
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/net_failover.c:net_failover_slave_unregister
  - drivers/net/net_failover.c:net_failover_slave_register
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/failover.c:failover_unregister
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gmcma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gmcma
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81ef1910-ffffffff81ef19b0: netdev_info (STB_GLOBAL)
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
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd893c)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffff800010bd893c-ffff800010bd89d0: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf31e4)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_timeout
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
c0cf31e4-c0cf3264: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb83d0)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
c000000000cb83d0-c000000000cb8474: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000761578)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffe000761578-ffffffe0007615d4: netdev_info (STB_GLOBAL)
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
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d97fc)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff818d97fc-ffffffff818d987f: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8189363c)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_snoop
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff8189363c-ffffffff818936bf: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a82c)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff8192a82c-ffffffff8192a8af: netdev_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netdev_info(const struct net_device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194bf50)
Location: net/core/dev.c:10029
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/sched/sch_api.c:qdisc_create
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_update_tx_channel
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff8194bf50-ffffffff8194bfd3: netdev_info (STB_GLOBAL)
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
