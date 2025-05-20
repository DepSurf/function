# Function: <code>device_iommu_mapped</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: include/linux/device.h:1066
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
In drivers/usb/host/xhci.c (0)
Location: include/linux/device.h:1089
Inline: True
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
In drivers/usb/host/xhci.c (0)
Location: include/linux/device.h:1331
Inline: True
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
In drivers/usb/host/xhci.c (ffffffff81906a86)
Location: include/linux/device.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
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
In drivers/usb/host/xhci.c (ffffffff8190f226)
Location: include/linux/device.h:595
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
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
In drivers/usb/host/xhci.c (ffffffff818f2805)
Location: include/linux/device.h:601
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
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
In drivers/acpi/scan.c (ffffffff816ffdb6)
Location: include/linux/device.h:618
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8198fa75)
Location: include/linux/device.h:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
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
In drivers/acpi/scan.c (ffffffff8182d91f)
Location: include/linux/device.h:693
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/usb/host/xhci.c (ffffffff81aebfa5)
Location: include/linux/device.h:693
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
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
In drivers/acpi/scan.c (ffffffff819606ef)
Location: include/linux/device.h:690
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa3d07)
Location: include/linux/device.h:690
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/host/xhci.c (ffffffff81c785f9)
Location: include/linux/device.h:690
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
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
In drivers/acpi/scan.c (ffffffff819a6e8f)
Location: include/linux/device.h:811
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aef5ca)
Location: include/linux/device.h:811
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
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
In drivers/char/agp/intel-gtt.c (ffffffff81b42b0f)
Location: include/linux/device.h:843
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
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
In drivers/acpi/arm64/iort.c (0)
Location: include/linux/device.h:1331
Inline: True
```
```
In drivers/iommu/of_iommu.c (0)
Location: include/linux/device.h:1331
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/device.h:1331
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
In drivers/iommu/of_iommu.c (c09c1694)
Location: include/linux/device.h:1331
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
```
In drivers/usb/host/xhci.c (c0b44c30)
Location: include/linux/device.h:1331
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
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
In arch/powerpc/kernel/eeh.c (c0000000000429a0)
Location: include/linux/device.h:1331
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:dev_has_iommu_table
```
```
In arch/powerpc/kernel/iommu.c (c000000000051c1c)
Location: include/linux/device.h:1331
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_add_device
```
```
In drivers/iommu/of_iommu.c (c000000000970924)
Location: include/linux/device.h:1331
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
```
In drivers/usb/host/xhci.c (c000000000b459d8)
Location: include/linux/device.h:1331
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe0006894cc)
Location: include/linux/device.h:1331
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
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
In drivers/usb/host/xhci.c (0)
Location: include/linux/device.h:1331
Inline: True
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
In drivers/usb/host/xhci.c (0)
Location: include/linux/device.h:1331
Inline: True
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
In drivers/usb/host/xhci.c (0)
Location: include/linux/device.h:1331
Inline: True
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
In drivers/usb/host/xhci.c (0)
Location: include/linux/device.h:1331
Inline: True
```
</details>
</li>
</ul>

## Differences
