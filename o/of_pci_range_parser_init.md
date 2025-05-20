# Function: <code>of_pci_range_parser_init</code>

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
Location: include/linux/of_address.h:89
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
Location: include/linux/of_address.h:89
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
Location: include/linux/of_address.h:89
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
Location: include/linux/of_address.h:116
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
Location: include/linux/of_address.h:116
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
int of_pci_range_parser_init(struct of_pci_range_parser *parser, struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b726b8)
Location: drivers/of/address.c:254
Inline: False
Direct callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
**Symbols:**

```
ffff800010b726b8-ffff800010b726f4: of_pci_range_parser_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_pci_range_parser_init(struct of_pci_range_parser *parser, struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c5549c)
Location: drivers/of/address.c:254
Inline: False
Direct callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt
```
**Symbols:**

```
c0c5549c-c0c554c0: of_pci_range_parser_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_pci_range_parser_init(struct of_pci_range_parser *parser, struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c4f860)
Location: drivers/of/address.c:254
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pci_process_bridge_OF_ranges
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
**Symbols:**

```
c000000000c4f860-c000000000c4f87c: of_pci_range_parser_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_pci_range_parser_init(struct of_pci_range_parser *parser, struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe000726312)
Location: drivers/of/address.c:254
Inline: False
Direct callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
**Symbols:**

```
ffffffe000726312-ffffffe00072634c: of_pci_range_parser_init (STB_GLOBAL)
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
