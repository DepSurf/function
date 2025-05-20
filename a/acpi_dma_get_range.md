# Function: <code>acpi_dma_get_range</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815402b0)
Location: drivers/acpi/scan.c:1383
Inline: False
```
**Symbols:**

```
ffffffff815402b0-ffffffff81540493: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81576210)
Location: drivers/acpi/scan.c:1384
Inline: False
```
**Symbols:**

```
ffffffff81576210-ffffffff815763e5: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158de30)
Location: drivers/acpi/scan.c:1384
Inline: False
```
**Symbols:**

```
ffffffff8158de30-ffffffff8158e005: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1382
Inline: False
```
**Symbols:**

```
ffffffff815c05da-ffffffff815c05f3: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff815bebb0-ffffffff815bed5a: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1382
Inline: False
```
**Symbols:**

```
ffffffff815e189a-ffffffff815e18b3: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff815dfe70-ffffffff815e001a: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1391
Inline: False
```
**Symbols:**

```
ffffffff8168c632-ffffffff8168c64b: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff8168b840-ffffffff8168b9eb: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1455
Inline: False
```
**Symbols:**

```
ffffffff81c011d5-ffffffff81c011ee: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff816a9640-ffffffff816a97eb: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1458
Inline: False
```
**Symbols:**

```
ffffffff81bf2b5e-ffffffff81bf2b77: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff8168bdd0-ffffffff8168bf72: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1465
Inline: False
```
**Symbols:**

```
ffffffff81cef4f1-ffffffff81cef50a: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff81701550-ffffffff817016ef: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1495
Inline: False
```
**Symbols:**

```
ffffffff81eb6f4a-ffffffff81eb6f5e: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff8182f1b0-ffffffff8182f35c: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_dma_get_range(struct device *dev, const struct bus_dma_region **map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81962180)
Location: drivers/acpi/scan.c:1478
Inline: False
```
**Symbols:**

```
ffffffff81962180-ffffffff81962353: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_dma_get_range(struct device *dev, const struct bus_dma_region **map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a8580)
Location: drivers/acpi/scan.c:1480
Inline: False
```
**Symbols:**

```
ffffffff819a8580-ffffffff819a8753: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_dma_get_range(struct device *dev, const struct bus_dma_region **map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f0fa0)
Location: drivers/acpi/scan.c:1483
Inline: False
```
**Symbols:**

```
ffffffff819f0fa0-ffffffff819f1170: acpi_dma_get_range (STB_GLOBAL)
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
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076c738)
Location: drivers/acpi/scan.c:1382
Inline: False
Direct callers:
  - drivers/acpi/arm64/iort.c:iort_dma_setup
```
**Symbols:**

```
ffff80001076c738-ffff80001076c938: acpi_dma_get_range (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1382
Inline: False
```
**Symbols:**

```
ffffffff815d3b6a-ffffffff815d3b83: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff815d2280-ffffffff815d242a: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1382
Inline: False
```
**Symbols:**

```
ffffffff815bd72a-ffffffff815bd743: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff815bbe40-ffffffff815bbfea: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1382
Inline: False
```
**Symbols:**

```
ffffffff815d5b7a-ffffffff815d5b93: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff815d4150-ffffffff815d42fa: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_dma_get_range(struct device *dev, u64 *dma_addr, u64 *offset, u64 *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1382
Inline: False
```
**Symbols:**

```
ffffffff815efa3a-ffffffff815efa53: acpi_dma_get_range.cold (STB_LOCAL)
ffffffff815ee010-ffffffff815ee1ba: acpi_dma_get_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bus_dma_region **map</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 *dma_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 *offset</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 *size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
