# Function: <code>__devm_reset_control_bulk_get</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __devm_reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732c40)
Location: drivers/reset/core.c:1069
Inline: False
```
**Symbols:**

```
ffffffff81732c40-ffffffff81732cf2: __devm_reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __devm_reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b3550)
Location: drivers/reset/core.c:1069
Inline: False
```
**Symbols:**

```
ffffffff817b3550-ffffffff817b3609: __devm_reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __devm_reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818ef120)
Location: drivers/reset/core.c:1070
Inline: False
```
**Symbols:**

```
ffffffff818ef120-ffffffff818ef201: __devm_reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __devm_reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a46df0)
Location: drivers/reset/core.c:1070
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
```
**Symbols:**

```
ffffffff81a46df0-ffffffff81a46ed1: __devm_reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __devm_reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a90f90)
Location: drivers/reset/core.c:1070
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
```
**Symbols:**

```
ffffffff81a90f90-ffffffff81a91071: __devm_reset_control_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __devm_reset_control_bulk_get(struct device *dev, int num_rstcs, struct reset_control_bulk_data *rstcs, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae3c70)
Location: drivers/reset/core.c:1070
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
```
**Symbols:**

```
ffffffff81ae3c70-ffffffff81ae3d51: __devm_reset_control_bulk_get (STB_GLOBAL)
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
