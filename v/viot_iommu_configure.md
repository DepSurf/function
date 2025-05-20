# Function: <code>viot_iommu_configure</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int viot_iommu_configure(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff8176ce30)
Location: drivers/acpi/viot.c:358
Inline: False
```
**Symbols:**

```
ffffffff8176ce30-ffffffff8176cf0f: viot_iommu_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int viot_iommu_configure(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff818a1e80)
Location: drivers/acpi/viot.c:372
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
**Symbols:**

```
ffffffff818a1e80-ffffffff818a1f78: viot_iommu_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int viot_iommu_configure(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff819eb630)
Location: drivers/acpi/viot.c:371
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
**Symbols:**

```
ffffffff819eb630-ffffffff819eb6e9: viot_iommu_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int viot_iommu_configure(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff81a33d60)
Location: drivers/acpi/viot.c:372
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
**Symbols:**

```
ffffffff81a33d60-ffffffff81a33e1a: viot_iommu_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int viot_iommu_configure(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff81a7f1d0)
Location: drivers/acpi/viot.c:372
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
**Symbols:**

```
ffffffff81a7f1d0-ffffffff81a7f28a: viot_iommu_configure (STB_GLOBAL)
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
