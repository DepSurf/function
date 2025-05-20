# Function: <code>of_pci_dma_range_parser_init</code>

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
int of_pci_dma_range_parser_init(struct of_pci_range_parser *parser, struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b726f8)
Location: drivers/of/address.c:261
Inline: False
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
```
**Symbols:**

```
ffff800010b726f8-ffff800010b72734: of_pci_dma_range_parser_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_pci_dma_range_parser_init(struct of_pci_range_parser *parser, struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c554c0)
Location: drivers/of/address.c:261
Inline: False
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_parse_map_dma_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
**Symbols:**

```
c0c554c0-c0c554e4: of_pci_dma_range_parser_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_pci_dma_range_parser_init(struct of_pci_range_parser *parser, struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c4f880)
Location: drivers/of/address.c:261
Inline: False
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges
```
**Symbols:**

```
c000000000c4f880-c000000000c4f89c: of_pci_dma_range_parser_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_pci_dma_range_parser_init(struct of_pci_range_parser *parser, struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe00072634c)
Location: drivers/of/address.c:261
Inline: False
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges
```
**Symbols:**

```
ffffffe00072634c-ffffffe000726386: of_pci_dma_range_parser_init (STB_GLOBAL)
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
