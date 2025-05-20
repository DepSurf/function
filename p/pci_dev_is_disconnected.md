# Function: <code>pci_dev_is_disconnected</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4355)
Location: drivers/pci/pci.h:284
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/pci.c (ffffffff814ad09c)
Location: drivers/pci/pci.h:284
Inline: True
```
```
In drivers/pci/msi.c (ffffffff814cdab6)
Location: drivers/pci/pci.h:284
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e30e5)
Location: drivers/pci/pci.h:287
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/pci.c (ffffffff814ec46c)
Location: drivers/pci/pci.h:287
Inline: True
```
```
In drivers/pci/msi.c (ffffffff8150dff6)
Location: drivers/pci/pci.h:287
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81512fb5)
Location: drivers/pci/pci.h:299
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_dword
  - drivers/pci/access.c:pci_read_config_word
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/pci.c (ffffffff8151b99c)
Location: drivers/pci/pci.h:299
Inline: True
```
```
In drivers/pci/msi.c (ffffffff81542ed6)
Location: drivers/pci/pci.h:299
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (0)
Location: drivers/pci/pci.h:361
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:361
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: drivers/pci/pci.h:361
Inline: True
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
In drivers/pci/access.c (0)
Location: drivers/pci/pci.h:366
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:366
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: drivers/pci/pci.h:366
Inline: True
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
In drivers/pci/access.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: drivers/pci/pci.h:400
Inline: True
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
In drivers/pci/access.c (ffffffff8161dfd5)
Location: drivers/pci/pci.h:405
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/pci.c (ffffffff8162b761)
Location: drivers/pci/pci.h:405
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
```
```
In drivers/pci/msi.c (ffffffff81654e24)
Location: drivers/pci/pci.h:405
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
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
In drivers/pci/access.c (ffffffff816447f5)
Location: drivers/pci/pci.h:388
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/pci.c (ffffffff81651461)
Location: drivers/pci/pci.h:388
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
```
```
In drivers/pci/msi.c (ffffffff8165e914)
Location: drivers/pci/pci.h:388
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
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
In drivers/pci/access.c (ffffffff81627575)
Location: drivers/pci/pci.h:381
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/pci.c (ffffffff81633ee1)
Location: drivers/pci/pci.h:381
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
```
```
In drivers/pci/msi.c (ffffffff81640db4)
Location: drivers/pci/pci.h:381
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
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
In drivers/pci/access.c (ffffffff81696dc5)
Location: drivers/pci/pci.h:402
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/pci.c (ffffffff816a40c1)
Location: drivers/pci/pci.h:402
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
```
```
In drivers/pci/msi.c (ffffffff816b19e4)
Location: drivers/pci/pci.h:402
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
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
In drivers/pci/access.c (ffffffff817b7de5)
Location: drivers/pci/pci.h:363
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/pci.c (ffffffff817c64b1)
Location: drivers/pci/pci.h:363
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/msi/msi.c (ffffffff817d5074)
Location: drivers/pci/pci.h:363
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
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
In drivers/pci/access.c (ffffffff818d2695)
Location: drivers/pci/pci.h:361
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/pci.c (ffffffff818dc3f3)
Location: drivers/pci/pci.h:361
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/msi/msi.c (ffffffff818f6338)
Location: drivers/pci/pci.h:361
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
```
```
In drivers/pci/pcie/err.c (ffffffff818fd4b6)
Location: drivers/pci/pci.h:361
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_error_detected
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
In drivers/pci/access.c (ffffffff81915695)
Location: drivers/pci/pci.h:360
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/pci.c (ffffffff8191f723)
Location: drivers/pci/pci.h:360
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/msi/msi.c (ffffffff81939798)
Location: drivers/pci/pci.h:360
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
```
```
In drivers/pci/pcie/err.c (ffffffff81940946)
Location: drivers/pci/pci.h:360
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_error_detected
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
In drivers/pci/access.c (ffffffff8195e0e1)
Location: drivers/pci/pci.h:371
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_clear_and_set_config_dword
  - drivers/pci/access.c:pci_clear_and_set_config_dword
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/pci.c (ffffffff81967893)
Location: drivers/pci/pci.h:371
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/msi/msi.c (ffffffff819825f8)
Location: drivers/pci/pci.h:371
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msix_shutdown
  - drivers/pci/msi/msi.c:__pci_write_msi_msg
```
```
In drivers/pci/pcie/err.c (ffffffff81989ba6)
Location: drivers/pci/pci.h:371
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_error_detected
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
In drivers/pci/access.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c08772cc)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/pci.c (c0884128)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/msi.c (c08a00ac)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852930)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
```
```
In drivers/pci/pci.c (c000000000863fa0)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/msi.c (c000000000885618)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3c3c)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_write_config_byte
  - drivers/pci/access.c:pci_read_config_byte
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/pci.c (ffffffe0004bf58a)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/msi.c (ffffffe0004dee66)
Location: drivers/pci/pci.h:400
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
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
In drivers/pci/access.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: drivers/pci/pci.h:400
Inline: True
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
In drivers/pci/access.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: drivers/pci/pci.h:400
Inline: True
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
In drivers/pci/access.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: drivers/pci/pci.h:400
Inline: True
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
In drivers/pci/access.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: drivers/pci/pci.h:400
Inline: True
```
</details>
</li>
</ul>

## Differences
