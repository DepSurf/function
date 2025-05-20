# Function: <code>pcie_downstream_port</code>

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
In drivers/pci/access.c (0)
Location: drivers/pci/access.c:574
Inline: True
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
In drivers/pci/access.c (ffffffff814798b9)
Location: drivers/pci/access.c:685
Inline: True
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
In drivers/pci/access.c (ffffffff8149ad49)
Location: drivers/pci/access.c:697
Inline: True
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
In drivers/pci/access.c (ffffffff814a4adb)
Location: drivers/pci/access.c:706
Inline: True
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
In drivers/pci/access.c (ffffffff814e38af)
Location: drivers/pci/access.c:706
Inline: True
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
In drivers/pci/access.c (ffffffff81513297)
Location: drivers/pci/access.c:339
Inline: True
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
In drivers/pci/access.c (ffffffff81528964)
Location: drivers/pci/access.c:339
Inline: True
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
In drivers/pci/access.c (ffffffff81557c05)
Location: drivers/pci/access.c:339
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
In drivers/pci/access.c (ffffffff8157921c)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8157bf4e)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81584bd4)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff815900b3)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pcie/err.c (ffffffff81599e71)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8159b821)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff8161e440)
Location: drivers/pci/pci.h:133
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff8162163e)
Location: drivers/pci/pci.h:133
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8162b80f)
Location: drivers/pci/pci.h:133
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff81637939)
Location: drivers/pci/pci.h:133
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/aspm.c (ffffffff8163b2e3)
Location: drivers/pci/pci.h:133
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff81644c5c)
Location: drivers/pci/pci.h:135
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff816481ce)
Location: drivers/pci/pci.h:135
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8165150c)
Location: drivers/pci/pci.h:135
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff8165c2f9)
Location: drivers/pci/pci.h:135
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/aspm.c (ffffffff81662343)
Location: drivers/pci/pci.h:135
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff816278fc)
Location: drivers/pci/pci.h:129
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff8162adee)
Location: drivers/pci/pci.h:129
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81633f8c)
Location: drivers/pci/pci.h:129
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff8163e89f)
Location: drivers/pci/pci.h:129
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/aspm.c (ffffffff816446ff)
Location: drivers/pci/pci.h:129
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff816971fc)
Location: drivers/pci/pci.h:150
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff8169a2be)
Location: drivers/pci/pci.h:150
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff816a416c)
Location: drivers/pci/pci.h:150
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff816af42f)
Location: drivers/pci/pci.h:150
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/aspm.c (ffffffff816b549c)
Location: drivers/pci/pci.h:150
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff817b899a)
Location: drivers/pci/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff817bb951)
Location: drivers/pci/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff817c655c)
Location: drivers/pci/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff817d28fb)
Location: drivers/pci/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/aspm.c (ffffffff817d8dfa)
Location: drivers/pci/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff818d340a)
Location: drivers/pci/pci.h:126
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff818d7471)
Location: drivers/pci/pci.h:126
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff818e3923)
Location: drivers/pci/pci.h:126
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff818f31ab)
Location: drivers/pci/pci.h:126
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/aspm.c (ffffffff818fa5b1)
Location: drivers/pci/pci.h:126
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff8191646a)
Location: drivers/pci/pci.h:114
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff8191a701)
Location: drivers/pci/pci.h:114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81926ecb)
Location: drivers/pci/pci.h:114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff819365c7)
Location: drivers/pci/pci.h:114
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/aspm.c (ffffffff8193dac1)
Location: drivers/pci/pci.h:114
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/quirks.c (ffffffff8194e293)
Location: drivers/pci/pci.h:114
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pcie_failed_link_retrain
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
In drivers/pci/access.c (ffffffff8195e49a)
Location: drivers/pci/pci.h:123
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff81962b01)
Location: drivers/pci/pci.h:123
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8196f66b)
Location: drivers/pci/pci.h:123
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff8197f427)
Location: drivers/pci/pci.h:123
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/aspm.c (ffffffff81986991)
Location: drivers/pci/pci.h:123
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/quirks.c (ffffffff819976c3)
Location: drivers/pci/pci.h:123
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pcie_failed_link_retrain
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
In drivers/pci/access.c (ffff8000106da694)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (ffff8000106df5f0)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffff8000106e9234)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffff8000106f5234)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pcie/err.c (ffff800010701744)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffff800010703458)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (c0877db4)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (c087b27c)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (c08841e0)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (c088fcb4)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pcie/err.c (c0899320)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (c089ad4c)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (c000000000852db0)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (c000000000857f80)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (c000000000864090)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (c000000000873d2c)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/access.c (ffffffe0004b3ea4)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (ffffffe0004b7566)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffe0004bf61c)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffe0004c816a)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pcie/err.c (ffffffe0004d0332)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffe0004d1dca)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff8156d73c)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8157046e)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff815790f4)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff81583f33)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pcie/err.c (ffffffff8158dd01)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158f6b1)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff8155beac)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8155ebce)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81567834)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff81572d13)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pcie/err.c (ffffffff8157c841)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8157e1f1)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff8156cf6c)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8156fc9e)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81578924)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff81583e03)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pcie/err.c (ffffffff8158dbc1)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158f571)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
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
In drivers/pci/access.c (ffffffff81587a6c)
Location: drivers/pci/pci.h:132
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8158a17e)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81592de4)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
```
In drivers/pci/vc.c (ffffffff8159e2b3)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pcie/err.c (ffffffff815a8071)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff815a9a21)
Location: drivers/pci/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
</details>
</li>
</ul>

## Differences
