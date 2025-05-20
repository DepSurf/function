# Function: <code>to_ctrl</code>

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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81550325)
Location: drivers/pci/hotplug/pciehp.h:209
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815510b3)
Location: drivers/pci/hotplug/pciehp.h:209
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815527b5)
Location: drivers/pci/hotplug/pciehp.h:209
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815801a5)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81580b42)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582675)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815a1c05)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a2772)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a4055)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8164a615)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164b2c9)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164cc45)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
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
In drivers/pci/hotplug/pciehp_core.c (ffffffff8166ee75)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8166fa59)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670f95)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
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
In drivers/pci/hotplug/pciehp_core.c (ffffffff816513b5)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81651f59)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816534c5)
Location: drivers/pci/hotplug/pciehp.h:194
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
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
In drivers/pci/hotplug/pciehp_core.c (ffffffff816c30f5)
Location: drivers/pci/hotplug/pciehp.h:200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816c3cc2)
Location: drivers/pci/hotplug/pciehp.h:200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c5235)
Location: drivers/pci/hotplug/pciehp.h:200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
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
In drivers/pci/hotplug/pciehp_core.c (ffffffff817e8b35)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e97c2)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eb005)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
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
In drivers/pci/hotplug/pciehp_core.c (ffffffff8190e525)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f749)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81911395)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
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
In drivers/pci/hotplug/pciehp_core.c (ffffffff81951ba5)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952e39)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954a35)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
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
In drivers/pci/hotplug/pciehp_core.c (ffffffff8199b005)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199c2c9)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199dec5)
Location: drivers/pci/hotplug/pciehp.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
</details>
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
In drivers/pci/hotplug/pciehp_core.c (ffff80001070a3e8)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070b380)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070ccbc)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
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
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffe0004d73ce)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d8010)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d94e0)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595415)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595f82)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597865)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815845a5)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81585112)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815869f5)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff81595955)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815964c2)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597da5)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_core.c (ffffffff815afdd5)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0942)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b21e5)
Location: drivers/pci/hotplug/pciehp.h:195
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
</details>
</li>
</ul>

## Differences
