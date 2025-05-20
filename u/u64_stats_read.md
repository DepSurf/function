# Function: <code>u64_stats_read</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff8187e8de)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81886251)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/tun.c (ffffffff8188a0c9)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
  - drivers/net/tun.c:tun_net_get_stats64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff8188ce5e)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81894701)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff8186f7ae)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81877004)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d345)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122d14b)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In drivers/net/loopback.c (ffffffff818ffcff)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81907cf5)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In net/ipv6/seg6_local.c (ffffffff81c48502)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f5ab)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In drivers/net/loopback.c (ffffffff81a51616)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5adf5)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In net/core/gen_stats.c (ffffffff81c029e5)
Location: include/linux/u64_stats_sync.h:81
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81c0366c)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/ipv6/seg6_local.c (ffffffff81de7a31)
Location: include/linux/u64_stats_sync.h:81
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c5a97)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In drivers/spi/spi.c (ffffffff81bd4c63)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_statistics_bytes_tx_show
  - drivers/spi/spi.c:spi_statistics_bytes_rx_show
  - drivers/spi/spi.c:spi_statistics_bytes_show
  - drivers/spi/spi.c:spi_statistics_spi_async_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_show
  - drivers/spi/spi.c:spi_statistics_timedout_show
  - drivers/spi/spi.c:spi_statistics_errors_show
  - drivers/spi/spi.c:spi_statistics_transfers_show
  - drivers/spi/spi.c:spi_statistics_messages_show
```
```
In drivers/net/loopback.c (ffffffff81bdaad3)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be5725)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In net/core/gen_stats.c (ffffffff81db1ea5)
Location: include/linux/u64_stats_sync.h:77
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81db2c5c)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81dc171f)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
```
```
In net/core/drop_monitor.c (ffffffff81e25ed4)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/devlink.c (ffffffff81e39623)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_read
  - net/core/devlink.c:devlink_trap_stats_read
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbbfd)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ecba7)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In drivers/spi/spi.c (ffffffff81c29b5c)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_emit_pcpu_stats
```
```
In drivers/net/loopback.c (ffffffff81c31573)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3d147)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In net/core/gen_stats.c (ffffffff81e22475)
Location: include/linux/u64_stats_sync.h:77
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81e2322c)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81e30f3f)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
```
```
In net/core/drop_monitor.c (ffffffff81e9b474)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/ipv6/seg6_local.c (ffffffff8201c4fd)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/leftover.c (ffffffff8203bf29)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_trap_stats_read
  - net/devlink/leftover.c:devlink_trap_stats_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130b357)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In drivers/spi/spi.c (ffffffff81cdc3ac)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_emit_pcpu_stats
```
```
In drivers/net/loopback.c (ffffffff81ce43f3)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/loopback.c:dev_lstats_read
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf24f7)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
  - drivers/net/phy/mdio_bus.c:mdio_bus_stat_field_show
```
```
In drivers/net/virtio_net.c (ffffffff81d01353)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_get_ethtool_stats
  - drivers/net/virtio_net.c:virtnet_get_ethtool_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_stats
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
```
```
In net/core/gen_stats.c (ffffffff81ee03b5)
Location: include/linux/u64_stats_sync.h:77
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81ee119a)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_timer
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81eef63f)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_fetch_sw_netstats
```
```
In net/core/drop_monitor.c (ffffffff81f5dbe4)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/ipv6/seg6_local.c (ffffffff820eb4cd)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/devlink/trap.c (ffffffff82115479)
Location: include/linux/u64_stats_sync.h:77
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_trap_stats_read
  - net/devlink/trap.c:devlink_trap_stats_read
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
