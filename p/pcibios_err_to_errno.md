# Function: <code>pcibios_err_to_errno</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b44d)
Location: include/linux/pci.h:555
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8142e7b8)
Location: include/linux/pci.h:555
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_byte
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_read_config_dword
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a828)
Location: include/linux/pci.h:554
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8147a19a)
Location: include/linux/pci.h:554
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ada6)
Location: include/linux/pci.h:584
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8149b61a)
Location: include/linux/pci.h:584
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101914e)
Location: include/linux/pci.h:611
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff814a52f9)
Location: include/linux/pci.h:611
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101979e)
Location: include/linux/pci.h:636
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff814e411f)
Location: include/linux/pci.h:636
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a40d)
Location: include/linux/pci.h:636
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff81513a6f)
Location: include/linux/pci.h:636
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aa95)
Location: include/linux/pci.h:657
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8152927f)
Location: include/linux/pci.h:657
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c4d9)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff815584a0)
Location: include/linux/pci.h:674
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ce59)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff81579ab0)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/pci.h:671
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817dba42)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817dc35a)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ebcc)
Location: include/linux/pci.h:698
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8161ea30)
Location: include/linux/pci.h:698
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/pci.h:698
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818aa05f)
Location: include/linux/pci.h:698
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
```
```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818aa8c4)
Location: include/linux/pci.h:698
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101f32c)
Location: include/linux/pci.h:714
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff81645260)
Location: include/linux/pci.h:714
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/pci.c (ffffffff8164b5db)
Location: include/linux/pci.h:714
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
```
```
In drivers/pci/pcie/aer.c (ffffffff816630d5)
Location: include/linux/pci.h:714
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b8f99)
Location: include/linux/pci.h:714
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
```
```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818b95e4)
Location: include/linux/pci.h:714
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020f80)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff81628080)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/pci.c (ffffffff8162e1bb)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
```
```
In drivers/pci/pcie/aer.c (ffffffff81645595)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189c476)
Location: include/linux/pci.h:712
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024b83)
Location: include/linux/pci.h:728
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff81697980)
Location: include/linux/pci.h:728
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/pci.c (ffffffff8169cd1b)
Location: include/linux/pci.h:728
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
```
```
In drivers/pci/pcie/aer.c (ffffffff816b676b)
Location: include/linux/pci.h:728
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff819306cf)
Location: include/linux/pci.h:728
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81028328)
Location: include/linux/pci.h:741
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff817b8636)
Location: include/linux/pci.h:741
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/pci.c (ffffffff817bec84)
Location: include/linux/pci.h:741
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
```
```
In drivers/pci/pcie/aer.c (ffffffff817da2ca)
Location: include/linux/pci.h:741
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a871a2)
Location: include/linux/pci.h:741
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_cap_len
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102d267)
Location: include/linux/pci.h:745
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff818d2fd6)
Location: include/linux/pci.h:745
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/pci.c (ffffffff818dcbf4)
Location: include/linux/pci.h:745
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
```
```
In drivers/pci/pcie/aer.c (ffffffff818fbdaa)
Location: include/linux/pci.h:745
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102df27)
Location: include/linux/pci.h:750
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff81915fd6)
Location: include/linux/pci.h:750
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/pci.c (ffffffff8191fed4)
Location: include/linux/pci.h:750
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
```
```
In drivers/pci/pcie/aer.c (ffffffff8193f67a)
Location: include/linux/pci.h:750
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff810335ed)
Location: include/linux/pci.h:773
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:upi_fill_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8195df46)
Location: include/linux/pci.h:773
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/pci.c (ffffffff819680b4)
Location: include/linux/pci.h:773
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
```
```
In drivers/pci/pcie/aer.c (ffffffff819891cf)
Location: include/linux/pci.h:773
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
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
In drivers/pci/access.c (ffff8000106dade4)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072f11c)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
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
In drivers/pci/access.c (c0877b40)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b8610)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
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
In drivers/pci/access.c (c000000000854040)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abcc58)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/pci/access.c (ffffffe0004b482a)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e9306)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ce59)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8156dfd0)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/pci.h:671
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c549)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8155c72a)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/pci.h:671
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81785af2)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff8178640a)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ce19)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff8156d800)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/pci.h:671
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817d08c2)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817d11da)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ce76)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In drivers/pci/access.c (ffffffff815878db)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/pci.h:671
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817eab62)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817eb47a)
Location: include/linux/pci.h:671
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
</details>
</li>
</ul>

## Differences
