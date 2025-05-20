# Function: <code>mc_encode_cmd_header</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/bus/fsl-mc/fsl-mc-bus.c (ffff800010680734)
Location: include/linux/fsl/mc.h:242
Inline: True
```
```
In drivers/bus/fsl-mc/dpbp.c (ffff800010681e2c)
Location: include/linux/fsl/mc.h:242
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dpbp.c:dpbp_get_attributes
  - drivers/bus/fsl-mc/dpbp.c:dpbp_reset
  - drivers/bus/fsl-mc/dpbp.c:dpbp_disable
  - drivers/bus/fsl-mc/dpbp.c:dpbp_enable
  - drivers/bus/fsl-mc/dpbp.c:dpbp_close
  - drivers/bus/fsl-mc/dpbp.c:dpbp_open
```
```
In drivers/bus/fsl-mc/dpcon.c (ffff80001068235c)
Location: include/linux/fsl/mc.h:242
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dpcon.c:dpcon_set_notification
  - drivers/bus/fsl-mc/dpcon.c:dpcon_get_attributes
  - drivers/bus/fsl-mc/dpcon.c:dpcon_reset
  - drivers/bus/fsl-mc/dpcon.c:dpcon_disable
  - drivers/bus/fsl-mc/dpcon.c:dpcon_enable
  - drivers/bus/fsl-mc/dpcon.c:dpcon_close
  - drivers/bus/fsl-mc/dpcon.c:dpcon_open
```
```
In drivers/bus/fsl-mc/dprc.c (ffff800010682fc0)
Location: include/linux/fsl/mc.h:242
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dprc.c:dprc_get_container_id
  - drivers/bus/fsl-mc/dprc.c:dprc_get_api_version
  - drivers/bus/fsl-mc/dprc.c:dprc_get_obj_region
  - drivers/bus/fsl-mc/dprc.c:dprc_get_obj_region
  - drivers/bus/fsl-mc/dprc.c:dprc_set_obj_irq
  - drivers/bus/fsl-mc/dprc.c:dprc_get_obj
  - drivers/bus/fsl-mc/dprc.c:dprc_get_obj_count
  - drivers/bus/fsl-mc/dprc.c:dprc_get_attributes
  - drivers/bus/fsl-mc/dprc.c:dprc_clear_irq_status
  - drivers/bus/fsl-mc/dprc.c:dprc_get_irq_status
  - drivers/bus/fsl-mc/dprc.c:dprc_set_irq_mask
  - drivers/bus/fsl-mc/dprc.c:dprc_set_irq_enable
  - drivers/bus/fsl-mc/dprc.c:dprc_set_irq
  - drivers/bus/fsl-mc/dprc.c:dprc_close
  - drivers/bus/fsl-mc/dprc.c:dprc_open
```
```
In drivers/bus/fsl-mc/dpmcp.c (ffff800010684efc)
Location: include/linux/fsl/mc.h:242
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dpmcp.c:dpmcp_reset
  - drivers/bus/fsl-mc/dpmcp.c:dpmcp_close
  - drivers/bus/fsl-mc/dpmcp.c:dpmcp_open
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
