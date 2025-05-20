# Function: <code>its_mask_encode</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010671608)
Location: drivers/irqchip/irq-gic-v3-its.c:322
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vinvall_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vinvall_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_invall_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_invall_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_clear_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_clear_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_clear_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_int_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_int_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_int_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_inv_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_inv_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_inv_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_discard_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_discard_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_discard_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapc_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapc_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapc_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapc_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
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
In drivers/irqchip/irq-gic-v3-its.c (c081989c)
Location: drivers/irqchip/irq-gic-v3-its.c:322
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vinvall_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vinvall_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_invall_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_invall_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_clear_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_clear_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_clear_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_int_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_int_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_int_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_inv_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_inv_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_inv_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_discard_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_discard_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_discard_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapc_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapc_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapc_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapc_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
```
</details>
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
