# Function: <code>resource_list_free_entry</code>

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
In kernel/resource.c (ffffffff81086483)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff814856a1)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In arch/x86/pci/acpi.c (ffffffff816f8be2)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810894c7)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff814d4fce)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff8175d8f4)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff8108e417)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/resource_ext.h:59
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff814f7621)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81789e24)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff8108b439)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:59
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff81505fd7)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff817a8f64)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff81092119)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:59
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff8154813d)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81820414)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff81095b09)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:59
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff8157def9)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff8186a667)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff8109de89)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:59
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff81595bd9)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff8188a737)
Location: include/linux/resource_ext.h:59
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810a23d4)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:51
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815c71eb)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818d5048)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810a89a4)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:51
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815e8408)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff819073c8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810b0124)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81693d5b)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81bb7bc8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810ab844)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81c01d97)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81bcc918)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810aca44)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81bf389a)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81bc0348)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810be5c4)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81cf04f2)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81c902fd)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810d5754)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81eb8377)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81e3f41d)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810f46f4)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff8196c471)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff82019105)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff81100b24)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/probe.c (ffffffff8191b2f1)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff819b29e1)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff8209978a)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff8110a454)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/probe.c (ffffffff81963721)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff819fcef1)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff82170e3a)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In arch/arm64/kernel/pci.c (ffff8000100a7a00)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/arm64/kernel/pci.c:pci_acpi_root_prepare_resources
```
```
In kernel/resource.c (ffff8000100ffe18)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/of.c (ffff8000106f9f7c)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
```
```
In drivers/pci/controller/pci-aardvark.c (ffff800010720714)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072af94)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072f2b8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/pci_root.c (ffff80001077572c)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
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
In kernel/resource.c (c035cb28)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/of.c (c0892610)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b63e0)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b8784)
Location: include/linux/resource_ext.h:51
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
In kernel/resource.c (c000000000147604)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/of.c (c000000000877a60)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
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
In kernel/resource.c (ffffffe0000c7b0a)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/of.c (ffffffe0004ca1c8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e9414)
Location: include/linux/resource_ext.h:51
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
In kernel/resource.c (ffffffff810a22c4)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:51
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815d96c1)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818a6788)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff81090ca4)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:51
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815c32d8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818612b8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810a2274)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:51
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815dc6e8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818f7de8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
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
In kernel/resource.c (ffffffff810aa2d4)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:51
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815f65a8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81918ee8)
Location: include/linux/resource_ext.h:51
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
</details>
</li>
</ul>

## Differences
