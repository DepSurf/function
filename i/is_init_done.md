# Function: <code>is_init_done</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109f0388)
Location: drivers/net/ethernet/freescale/fman/fman.c:1206
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
```
```
In drivers/net/ethernet/freescale/fman/fman_port.c (ffff8000109f1748)
Location: drivers/net/ethernet/freescale/fman/fman_port.c:842
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_cfg_buf_prefix_content
```
```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f5e40)
Location: drivers/net/ethernet/freescale/fman/fman_dtsec.c:664
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_get_version
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_restart_autoneg
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tstamp
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_modify_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_disable
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_enable
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_cfg_pad_and_crc
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_cfg_max_frame_len
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (ffff8000109f736c)
Location: drivers/net/ethernet/freescale/fman/fman_memac.c:706
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_exception
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_modify_mac_address
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_cfg_fixed_link
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_cfg_reset_on_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_cfg_max_frame_len
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_disable
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_enable
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (ffff8000109f8634)
Location: drivers/net/ethernet/freescale/fman/fman_tgec.c:417
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_get_version
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_tstamp
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_modify_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_cfg_max_frame_len
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_disable
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_enable
```
</details>
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
