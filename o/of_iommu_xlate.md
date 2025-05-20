# Function: <code>of_iommu_xlate</code>

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
int of_iommu_xlate(struct device *dev, struct of_phandle_args *iommu_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/of_iommu.c (ffff8000108ce728)
Location: drivers/iommu/of_iommu.c:87
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
  - drivers/iommu/of_iommu.c:of_fsl_mc_iommu_init
  - drivers/iommu/of_iommu.c:of_pci_iommu_init
```
**Symbols:**

```
ffff8000108ce728-ffff8000108ce7d0: of_iommu_xlate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_iommu_xlate(struct device *dev, struct of_phandle_args *iommu_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/of_iommu.c (c09c1428)
Location: drivers/iommu/of_iommu.c:87
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
  - drivers/iommu/of_iommu.c:of_pci_iommu_init
```
**Symbols:**

```
c09c1428-c09c14c0: of_iommu_xlate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_iommu_xlate(struct device *dev, struct of_phandle_args *iommu_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/of_iommu.c (c0000000009705d0)
Location: drivers/iommu/of_iommu.c:87
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
  - drivers/iommu/of_iommu.c:of_pci_iommu_init
```
**Symbols:**

```
c0000000009705d0-c0000000009706f0: of_iommu_xlate (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
