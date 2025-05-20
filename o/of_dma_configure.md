# Function: <code>of_dma_configure</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (0)
Location: include/linux/of_device.h:107
Inline: True
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
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/of_device.h:108
Inline: True
```
```
In drivers/base/dma-mapping.c (0)
Location: include/linux/of_device.h:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:110
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:121
Inline: True
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
Inline: True
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:110
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:79
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:79
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
int of_dma_configure(struct device *dev, struct device_node *np, bool force_dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (ffff800010b6c7f8)
Location: drivers/of/device.c:89
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffff800010b6c7f8-ffff800010b6cab4: of_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_dma_configure(struct device *dev, struct device_node *np, bool force_dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (c0c4f77c)
Location: drivers/of/device.c:89
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/base/platform.c:platform_dma_configure
```
**Symbols:**

```
c0c4f77c-c0c4fb24: of_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_dma_configure(struct device *dev, struct device_node *np, bool force_dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (c000000000c46c90)
Location: drivers/of/device.c:89
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/base/platform.c:platform_dma_configure
```
**Symbols:**

```
c000000000c46c90-c000000000c46fc4: of_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_dma_configure(struct device *dev, struct device_node *np, bool force_dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/device.c (ffffffe000721a28)
Location: drivers/of/device.c:89
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/base/platform.c:platform_dma_configure
```
**Symbols:**

```
ffffffe000721a28-ffffffe000721c7c: of_dma_configure (STB_GLOBAL)
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
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
In drivers/base/platform.c (0)
Location: include/linux/of_device.h:109
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
