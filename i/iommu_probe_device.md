# Function: <code>iommu_probe_device</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680600)
Location: drivers/iommu/iommu.c:114
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
```
**Symbols:**

```
ffffffff81680600-ffffffff8168063c: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:121
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816b8a19-ffffffff816b8a2c: iommu_probe_device.cold (STB_LOCAL)
ffffffff816b7dd0-ffffffff816b7ea6: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816dab30)
Location: drivers/iommu/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816dab30-ffffffff816dac10: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178fd50)
Location: drivers/iommu/iommu.c:245
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/intel/iommu.c:probe_acpi_namespace_devices
```
**Symbols:**

```
ffffffff8178fd50-ffffffff8178fe5a: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bc110)
Location: drivers/iommu/iommu.c:247
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:probe_acpi_namespace_devices
  - drivers/iommu/iommu.c:iommu_bus_notifier
```
**Symbols:**

```
ffffffff817bc110-ffffffff817bc23f: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f2d0)
Location: drivers/iommu/iommu.c:254
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/iommu.c:iommu_bus_notifier
```
**Symbols:**

```
ffffffff8179f2d0-ffffffff8179f3ff: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81828290)
Location: drivers/iommu/iommu.c:271
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/iommu.c:iommu_bus_notifier
```
**Symbols:**

```
ffffffff81828290-ffffffff818283d8: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81968240)
Location: drivers/iommu/iommu.c:273
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81968240-ffffffff819683a6: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad1ed0)
Location: drivers/iommu/iommu.c:398
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81ad1ed0-ffffffff81ad2095: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b20800)
Location: drivers/iommu/iommu.c:408
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b20800-ffffffff81b20966: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b77500)
Location: drivers/iommu/iommu.c:592
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b77500-ffffffff81b77569: iommu_probe_device (STB_GLOBAL)
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
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c69f0)
Location: drivers/iommu/iommu.c:174
Inline: False
Direct callers:
  - drivers/acpi/arm64/iort.c:iort_iommu_configure
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
**Symbols:**

```
ffff8000108c69f0-ffff8000108c6ac4: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bda10)
Location: drivers/iommu/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
**Symbols:**

```
c09bda10-c09bdaec: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096d4f0)
Location: drivers/iommu/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
**Symbols:**

```
c00000000096d4f0-c00000000096d620: iommu_probe_device (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a0580)
Location: drivers/iommu/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816a0580-ffffffff816a0660: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167df70)
Location: drivers/iommu/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8167df70-ffffffff8167e050: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ce7f0)
Location: drivers/iommu/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816ce7f0-ffffffff816ce8d0: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_probe_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8d60)
Location: drivers/iommu/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:add_iommu_group
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816e8d60-ffffffff816e8e40: iommu_probe_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
