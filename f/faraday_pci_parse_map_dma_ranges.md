# Function: <code>faraday_pci_parse_map_dma_ranges</code>

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
int faraday_pci_parse_map_dma_ranges(struct faraday_pci *p, struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071ece8)
Location: drivers/pci/controller/pci-ftpci100.c:378
Inline: False
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
**Symbols:**

```
ffff80001071ece8-ffff80001071ee7c: faraday_pci_parse_map_dma_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (c08a8418)
Location: drivers/pci/controller/pci-ftpci100.c:378
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int faraday_pci_parse_map_dma_ranges(struct faraday_pci *p, struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (c000000000890550)
Location: drivers/pci/controller/pci-ftpci100.c:378
Inline: False
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
**Symbols:**

```
c000000000890550-c000000000890758: faraday_pci_parse_map_dma_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int faraday_pci_parse_map_dma_ranges(struct faraday_pci *p, struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e6114)
Location: drivers/pci/controller/pci-ftpci100.c:378
Inline: False
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
**Symbols:**

```
ffffffe0004e6114-ffffffe0004e624a: faraday_pci_parse_map_dma_ranges (STB_LOCAL)
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
