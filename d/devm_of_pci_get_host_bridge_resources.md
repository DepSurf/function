# Function: <code>devm_of_pci_get_host_bridge_resources</code>

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
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/pci.h:462
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
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/pci.h:582
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
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/pci.h:587
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
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/pci.h:634
Inline: True
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device *dev, unsigned char busno, unsigned char bus_max, struct list_head *resources, resource_size_t *io_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffff8000106f9740)
Location: drivers/pci/of.c:258
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
```
**Symbols:**

```
ffff8000106f9740-ffff8000106f99d0: devm_of_pci_get_host_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device *dev, unsigned char busno, unsigned char bus_max, struct list_head *resources, resource_size_t *io_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c0891d2c)
Location: drivers/pci/of.c:258
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
c0891d2c-c0892018: devm_of_pci_get_host_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device *dev, unsigned char busno, unsigned char bus_max, struct list_head *resources, resource_size_t *io_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c000000000876ec0)
Location: drivers/pci/of.c:258
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
**Symbols:**

```
c000000000876ec0-c00000000087722c: devm_of_pci_get_host_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_of_pci_get_host_bridge_resources(struct device *dev, unsigned char busno, unsigned char bus_max, struct list_head *resources, resource_size_t *io_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffffffe0004c9aaa)
Location: drivers/pci/of.c:258
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffe0004c9aaa-ffffffe0004c9cf2: devm_of_pci_get_host_bridge_resources (STB_GLOBAL)
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
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/pci.h:634
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
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/pci.h:634
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
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/pci.h:634
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
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/pci.h:634
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
