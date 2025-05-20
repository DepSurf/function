# Function: <code>pcie_find_root_port</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149cbc3)
Location: include/linux/pci.h:1961
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
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
In drivers/pci/probe.c (ffffffff814a6b41)
Location: include/linux/pci.h:1993
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
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
In drivers/pci/probe.c (ffffffff814e70b3)
Location: include/linux/pci.h:2049
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
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
In drivers/pci/probe.c (ffffffff8151662a)
Location: include/linux/pci.h:2052
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
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
In drivers/pci/probe.c (ffffffff8152bef7)
Location: include/linux/pci.h:2099
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
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
In drivers/pci/probe.c (ffffffff815597b8)
Location: include/linux/pci.h:2173
Inline: True
Inline callers:
  - drivers/pci/probe.c:program_hpp_type2
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
In drivers/pci/pci-acpi.c (ffffffff81592e6b)
Location: include/linux/pci.h:2147
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2172
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci-acpi.c (ffffffff816402f0)
Location: include/linux/pci.h:2172
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81643df5)
Location: include/linux/pci.h:2172
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
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
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2176
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pci-acpi.c (ffffffff81666702)
Location: include/linux/pci.h:2176
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8166a255)
Location: include/linux/pci.h:2176
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
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
In drivers/pci/probe.c (ffffffff8162a843)
Location: include/linux/pci.h:2215
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pcie/aer.c (ffffffff81645275)
Location: include/linux/pci.h:2215
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pci-acpi.c (ffffffff81648bb2)
Location: include/linux/pci.h:2215
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2215
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/probe.c (ffffffff81699d23)
Location: include/linux/pci.h:2276
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pcie/aer.c (ffffffff816b610b)
Location: include/linux/pci.h:2276
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pci-acpi.c (ffffffff816ba5d2)
Location: include/linux/pci.h:2276
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2276
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2308
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pcie/aer.c (ffffffff817d9d6f)
Location: include/linux/pci.h:2308
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pci-acpi.c (ffffffff817dfe9b)
Location: include/linux/pci.h:2308
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2347
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pcie/aer.c (ffffffff818fb7ae)
Location: include/linux/pci.h:2347
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pci-acpi.c (ffffffff81902dc5)
Location: include/linux/pci.h:2347
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2347
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/probe.c (ffffffff81919fd2)
Location: include/linux/pci.h:2439
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pcie/aer.c (ffffffff8193ed07)
Location: include/linux/pci.h:2439
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pci-acpi.c (ffffffff81946455)
Location: include/linux/pci.h:2439
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8194b88a)
Location: include/linux/pci.h:2439
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
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
In drivers/pci/probe.c (ffffffff819623d2)
Location: include/linux/pci.h:2510
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
```
In drivers/pci/pcie/aer.c (ffffffff81987dcd)
Location: include/linux/pci.h:2510
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pci-acpi.c (ffffffff8198f785)
Location: include/linux/pci.h:2510
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81996f5a)
Location: include/linux/pci.h:2510
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In arch/x86/pci/fixup.c (ffffffff82170c66)
Location: include/linux/pci.h:2510
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:amd_rp_pme_resume
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
In drivers/pci/pci-acpi.c (ffff8000106f8e0c)
Location: include/linux/pci.h:2147
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81586cfb)
Location: include/linux/pci.h:2147
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81575acb)
Location: include/linux/pci.h:2147
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81586bbb)
Location: include/linux/pci.h:2147
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff815a106b)
Location: include/linux/pci.h:2147
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
</details>
</li>
</ul>

## Differences
