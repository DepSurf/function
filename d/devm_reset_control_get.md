# Function: <code>devm_reset_control_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct reset_control *devm_reset_control_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff814df4d0)
Location: drivers/reset/core.c:260
Inline: False
Direct callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff814df4d0-ffffffff814df524: devm_reset_control_get (STB_GLOBAL)
```
</details>
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560df8)
Location: include/linux/reset.h:366
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81590f77)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff800010733dec)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010736ad4)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
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
In drivers/pci/controller/dwc/pcie-qcom.c (c08bcb34)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08bea4c)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/clk/tegra/clk-dfll.c (c090cd64)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
```
```
In drivers/dma/tegra20-apb-dma.c (c092a598)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6467)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81595607)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a69f7)
Location: include/linux/reset.h:423
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
