# Function: <code>resource_list_del</code>

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
In kernel/resource.c (ffffffff8108645d)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81485670)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In arch/x86/pci/acpi.c (ffffffff816f8bb9)
Location: include/linux/resource_ext.h:54
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
In kernel/resource.c (ffffffff810894b5)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff814d4fc3)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff8175d89d)
Location: include/linux/resource_ext.h:54
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
In kernel/resource.c (ffffffff8108e405)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/resource_ext.h:54
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff814f7616)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81789dcd)
Location: include/linux/resource_ext.h:54
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
In kernel/resource.c (ffffffff8108b413)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:54
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff81505fcf)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff817a8f0a)
Location: include/linux/resource_ext.h:54
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
In kernel/resource.c (ffffffff810920f3)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:54
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff81548135)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818203ba)
Location: include/linux/resource_ext.h:54
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
In kernel/resource.c (ffffffff81095af7)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:54
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff8157ded1)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff8186a645)
Location: include/linux/resource_ext.h:54
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
In kernel/resource.c (ffffffff8109de77)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:54
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff81595bb1)
Location: include/linux/resource_ext.h:54
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff8188a715)
Location: include/linux/resource_ext.h:54
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
In kernel/resource.c (ffffffff810a23c2)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:46
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815c71c5)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818d5033)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810a8992)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:46
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815e83e2)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff819073b3)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810b0112)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81693d35)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81bb7bb3)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810ab832)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81c01d71)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81bcc903)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810aca32)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81bf3874)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81bc0333)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810be5b2)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81cf04cc)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81c902ed)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810d5742)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff81eb8351)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81e3f3fe)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810f46e2)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/acpi/pci_root.c (ffffffff8196c44b)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff820190ed)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff81100b12)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/probe.c (ffffffff8191b2c4)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff819b29bb)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff82099772)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff8110a442)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/probe.c (ffffffff819636f4)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff819fcecb)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff82170e22)
Location: include/linux/resource_ext.h:46
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
In arch/arm64/kernel/pci.c (ffff8000100a79f0)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - arch/arm64/kernel/pci.c:pci_acpi_root_prepare_resources
```
```
In kernel/resource.c (ffff8000100ffe08)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/of.c (ffff8000106f9f58)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
```
```
In drivers/pci/controller/pci-aardvark.c (ffff8000107206ec)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072af70)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072f290)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/pci_root.c (ffff800010775708)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (c035cb14)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/of.c (c08925f4)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b63c4)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b8768)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (c0000000001475f0)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/of.c (c000000000877a44)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffe0000c7aee)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/of.c (ffffffe0004ca1c0)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e940c)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810a22b2)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:46
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815d969b)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818a6773)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff81090c92)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:46
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815c32b2)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818612a3)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810a2262)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:46
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815dc6c2)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff818f7dd3)
Location: include/linux/resource_ext.h:46
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
In kernel/resource.c (ffffffff810aa2c2)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - kernel/resource.c:resource_list_free
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/resource_ext.h:46
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815f6582)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:__acpi_pci_root_release_info
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In arch/x86/pci/acpi.c (ffffffff81918ed3)
Location: include/linux/resource_ext.h:46
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
</details>
</li>
</ul>

## Differences
