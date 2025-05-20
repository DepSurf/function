# Function: <code>ctrl_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81450207)
Location: drivers/pci/hotplug/pciehp_hpc.c:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149dab0)
Location: drivers/pci/hotplug/pciehp_hpc.c:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bf6d0)
Location: drivers/pci/hotplug/pciehp_hpc.c:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c9e50)
Location: drivers/pci/hotplug/pciehp_hpc.c:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8150a400)
Location: drivers/pci/hotplug/pciehp_hpc.c:44
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153b2c5)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815527b5)
Location: drivers/pci/hotplug/pciehp_hpc.c:27
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582675)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a4055)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164cc45)
Location: drivers/pci/hotplug/pciehp_hpc.c:48
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670f95)
Location: drivers/pci/hotplug/pciehp_hpc.c:48
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816534c5)
Location: drivers/pci/hotplug/pciehp_hpc.c:48
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c5235)
Location: drivers/pci/hotplug/pciehp_hpc.c:48
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eb005)
Location: drivers/pci/hotplug/pciehp_hpc.c:48
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81911395)
Location: drivers/pci/hotplug/pciehp_hpc.c:48
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954a35)
Location: drivers/pci/hotplug/pciehp_hpc.c:48
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199dec5)
Location: drivers/pci/hotplug/pciehp_hpc.c:49
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
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
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070ccbc)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
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
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d94e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597865)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815869f5)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597da5)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b21e5)
Location: drivers/pci/hotplug/pciehp_hpc.c:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
</details>
</li>
</ul>

## Differences
