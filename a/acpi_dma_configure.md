# Function: <code>acpi_dma_configure</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814efc3d)
Location: drivers/acpi/scan.c:1376
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/acpi/glue.c:acpi_bind_one
```
**Symbols:**

```
ffffffff814efc3d-ffffffff814efc48: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fcd70)
Location: drivers/acpi/scan.c:1367
Inline: False
Direct callers:
  - drivers/base/dma-mapping.c:dma_configure
```
**Symbols:**

```
ffffffff814fcd70-ffffffff814fcd7d: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8153eac0)
Location: drivers/acpi/scan.c:1453
Inline: False
Direct callers:
  - drivers/base/dma-mapping.c:dma_configure
```
**Symbols:**

```
ffffffff8153eac0-ffffffff8153eacd: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81574a00)
Location: drivers/acpi/scan.c:1454
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff81574a00-ffffffff81574a0d: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158c620)
Location: drivers/acpi/scan.c:1454
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff8158c620-ffffffff8158c63c: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bd400)
Location: drivers/acpi/scan.c:1452
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff815bd400-ffffffff815bd41c: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815de6c0)
Location: drivers/acpi/scan.c:1452
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff815de6c0-ffffffff815de6dc: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81689070)
Location: drivers/acpi/scan.c:1461
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff81689070-ffffffff8168908c: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81652b12)
Location: include/acpi/acpi_bus.h:594
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/base/platform.c (ffffffff817d0f6f)
Location: include/acpi/acpi_bus.h:594
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816355d5)
Location: include/acpi/acpi_bus.h:595
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/base/platform.c (ffffffff817b498f)
Location: include/acpi/acpi_bus.h:595
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a54e5)
Location: include/acpi/acpi_bus.h:602
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/base/platform.c (ffffffff8183ddcf)
Location: include/acpi/acpi_bus.h:602
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
In drivers/pci/pci-driver.c (ffffffff817c8208)
Location: include/acpi/acpi_bus.h:618
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/base/platform.c (ffffffff81980a2f)
Location: include/acpi/acpi_bus.h:618
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_dma_configure
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
In drivers/pci/pci-driver.c (ffffffff818e5a48)
Location: include/acpi/acpi_bus.h:627
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/base/platform.c (ffffffff81aee56f)
Location: include/acpi/acpi_bus.h:627
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_dma_configure
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
In drivers/pci/pci-driver.c (ffffffff81929088)
Location: include/acpi/acpi_bus.h:630
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/base/platform.c (ffffffff81b3c92f)
Location: include/acpi/acpi_bus.h:630
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_dma_configure
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
In drivers/pci/pci-driver.c (ffffffff81971888)
Location: include/acpi/acpi_bus.h:732
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/base/platform.c (ffffffff81b9445d)
Location: include/acpi/acpi_bus.h:732
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_dma_configure
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
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076b108)
Location: drivers/acpi/scan.c:1452
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/acpi/arm64/iort.c:arm_smmu_dma_configure
  - drivers/acpi/arm64/iort.c:arm_smmu_v3_dma_configure
```
**Symbols:**

```
ffff80001076b108-ffff80001076b1c8: acpi_dma_configure (STB_GLOBAL)
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:851
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:851
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:851
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:851
Inline: True
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:851
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:851
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d0ba0)
Location: drivers/acpi/scan.c:1452
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff815d0ba0-ffffffff815d0bbc: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ba760)
Location: drivers/acpi/scan.c:1452
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff815ba760-ffffffff815ba77c: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d29a0)
Location: drivers/acpi/scan.c:1452
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff815d29a0-ffffffff815d29bc: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_dma_configure(struct device *dev, enum dev_dma_attr attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ec860)
Location: drivers/acpi/scan.c:1452
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
**Symbols:**

```
ffffffff815ec860-ffffffff815ec87c: acpi_dma_configure (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
