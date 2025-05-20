# Function: <code>arch_teardown_dma_ops</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: include/linux/dma-mapping.h:617
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: include/linux/dma-mapping.h:648
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: include/linux/dma-mapping.h:656
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
In drivers/acpi/scan.c (0)
Location: include/linux/dma-mapping.h:660
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:686
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:709
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:714
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:800
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
In drivers/base/dd.c (0)
Location: include/linux/dma-map-ops.h:347
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
In drivers/base/dd.c (0)
Location: include/linux/dma-map-ops.h:360
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
In drivers/base/dd.c (0)
Location: include/linux/dma-map-ops.h:363
Inline: True
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/dma-map-ops.h:363
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/dma-map-ops.h:363
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/dma-map-ops.h:363
Inline: True
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/dma-map-ops.h:377
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/dma-map-ops.h:377
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/dma-map-ops.h:377
Inline: True
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/dma-map-ops.h:440
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/dma-map-ops.h:440
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/dma-map-ops.h:440
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: include/linux/dma-map-ops.h:441
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/dma-map-ops.h:441
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/dma-map-ops.h:441
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
void arch_teardown_dma_ops(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/dma-mapping.c (ffff8000100acb70)
Location: arch/arm64/mm/dma-mapping.c:34
Inline: False
Direct callers:
  - drivers/acpi/arm64/iort.c:iort_add_platform_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffff8000100acb70-ffff8000100acb98: arch_teardown_dma_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_teardown_dma_ops(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/dma-mapping.c (c031e7d4)
Location: arch/arm/mm/dma-mapping.c:2324
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
c031e7d4-c031e81c: arch_teardown_dma_ops (STB_GLOBAL)
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:714
Inline: True
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:714
Inline: True
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:714
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:714
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:714
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
In drivers/base/dd.c (0)
Location: include/linux/dma-mapping.h:714
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
