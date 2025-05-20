# Function: <code>zynqmp_pm_invoke_fn</code>

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
int zynqmp_pm_invoke_fn(u32 pm_api_id, u32 arg0, u32 arg1, u32 arg2, u32 arg3, u32 *ret_payload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/xilinx/zynqmp.c (ffff800010b63b48)
Location: drivers/firmware/xilinx/zynqmp.c:154
Inline: True
Inline callers:
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_set_requirement
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_release_node
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_request_node
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_set_suspend_mode
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_init_finalize
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_fpga_get_status
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_fpga_load
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_reset_get_status
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_reset_assert
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_getparent
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_setparent
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_getrate
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_setrate
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_getdivider
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_setdivider
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_getstate
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_disable
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_enable
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_query_data
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_get_chipid
Direct callers:
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_isr
```
**Symbols:**

```
ffff800010b63c00-ffff800010b63c6c: zynqmp_pm_invoke_fn (STB_GLOBAL)
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
