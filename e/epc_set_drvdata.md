# Function: <code>epc_set_drvdata</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:113
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:121
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:134
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:134
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:154
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167ceab)
Location: include/linux/pci-epc.h:154
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fd2a)
Location: include/linux/pci-epc.h:178
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d294a)
Location: include/linux/pci-epc.h:185
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbde0)
Location: include/linux/pci-epc.h:185
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81929067)
Location: include/linux/pci-epc.h:185
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196d2a7)
Location: include/linux/pci-epc.h:185
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b629f)
Location: include/linux/pci-epc.h:178
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e344)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff8000107295b8)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff800010730278)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/pcie-cadence-ep.c (c08a7544)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b43cc)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b9470)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f768)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
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
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e5556)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004ea200)
Location: include/linux/pci-epc.h:134
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:134
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:134
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:134
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/pci-epc.h:134
Inline: True
```
</details>
</li>
</ul>

## Differences
