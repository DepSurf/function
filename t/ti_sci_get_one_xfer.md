# Function: <code>ti_sci_get_one_xfer</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct ti_sci_xfer *ti_sci_get_one_xfer(struct ti_sci_info *info, u16 msg_type, u32 msg_flags, size_t tx_message_size, size_t rx_message_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/ti_sci.c (ffff800010b50df0)
Location: drivers/firmware/ti_sci.c:320
Inline: True
Direct callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_get_status
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_control
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_handover
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_release
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_request
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_flow_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_tx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_unpair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_pair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_get_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_config
  - drivers/firmware/ti_sci.c:ti_sci_get_resource_range
  - drivers/firmware/ti_sci.c:ti_sci_cmd_core_reboot
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_match_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_num_parents
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_get_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_set_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_cmd_set_device_resets
  - drivers/firmware/ti_sci.c:ti_sci_get_device_state
  - drivers/firmware/ti_sci.c:ti_sci_set_device_state
```
**Symbols:**

```
ffff800010b50df0-ffff800010b50f90: ti_sci_get_one_xfer (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
