# Function: <code>of_pci_range_parser_one</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of_address.h:101
Inline: True
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
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of_address.h:101
Inline: True
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
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of_address.h:101
Inline: True
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
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of_address.h:128
Inline: True
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
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of_address.h:128
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct of_pci_range *of_pci_range_parser_one(struct of_pci_range_parser *parser, struct of_pci_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b73f58)
Location: drivers/of/address.c:268
Inline: False
Direct callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
```
**Symbols:**

```
ffff800010b73f58-ffff800010b740d0: of_pci_range_parser_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct of_pci_range *of_pci_range_parser_one(struct of_pci_range_parser *parser, struct of_pci_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c55dac)
Location: drivers/of/address.c:268
Inline: False
Direct callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_parse_map_dma_ranges
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_parse_map_dma_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
**Symbols:**

```
c0c55dac-c0c55fc0: of_pci_range_parser_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct of_pci_range *of_pci_range_parser_one(struct of_pci_range_parser *parser, struct of_pci_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c508c0)
Location: drivers/of/address.c:268
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pci_process_bridge_OF_ranges
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges
```
**Symbols:**

```
c000000000c508c0-c000000000c50b20: of_pci_range_parser_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct of_pci_range *of_pci_range_parser_one(struct of_pci_range_parser *parser, struct of_pci_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe0007278b2)
Location: drivers/of/address.c:268
Inline: False
Direct callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges
```
**Symbols:**

```
ffffffe0007278b2-ffffffe000727b1a: of_pci_range_parser_one (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
