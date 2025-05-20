# Function: <code>acpi_dma_configure_id</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_dma_configure_id(struct device *dev, enum dev_dma_attr attr, const u32 *input_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a6c00)
Location: drivers/acpi/scan.c:1526
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff816a6c00-ffffffff816a6c1c: acpi_dma_configure_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_dma_configure_id(struct device *dev, enum dev_dma_attr attr, const u32 *input_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81689890)
Location: drivers/acpi/scan.c:1529
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff81689890-ffffffff816898ac: acpi_dma_configure_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_dma_configure_id(struct device *dev, enum dev_dma_attr attr, const u32 *input_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816ffd50)
Location: drivers/acpi/scan.c:1608
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff816ffd50-ffffffff816ffe31: acpi_dma_configure_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_dma_configure_id(struct device *dev, enum dev_dma_attr attr, const u32 *input_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182d8b0)
Location: drivers/acpi/scan.c:1638
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/base/platform.c:platform_dma_configure
```
**Symbols:**

```
ffffffff8182d8b0-ffffffff8182d98b: acpi_dma_configure_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_dma_configure_id(struct device *dev, enum dev_dma_attr attr, const u32 *input_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81960680)
Location: drivers/acpi/scan.c:1618
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/base/platform.c:platform_dma_configure
```
**Symbols:**

```
ffffffff81960680-ffffffff8196075b: acpi_dma_configure_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_dma_configure_id(struct device *dev, enum dev_dma_attr attr, const u32 *input_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a6e20)
Location: drivers/acpi/scan.c:1620
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/base/platform.c:platform_dma_configure
```
**Symbols:**

```
ffffffff819a6e20-ffffffff819a6efb: acpi_dma_configure_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_dma_configure_id(struct device *dev, enum dev_dma_attr attr, const u32 *input_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819ef840)
Location: drivers/acpi/scan.c:1627
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/base/platform.c:platform_dma_configure
```
**Symbols:**

```
ffffffff819ef840-ffffffff819ef91c: acpi_dma_configure_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
