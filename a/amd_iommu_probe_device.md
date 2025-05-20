# Function: <code>amd_iommu_probe_device</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_device *amd_iommu_probe_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817980b0)
Location: drivers/iommu/amd/iommu.c:2125
Inline: True
```
**Symbols:**

```
ffffffff81798070-ffffffff8179827d: amd_iommu_probe_device (STB_LOCAL)
ffffffff8179a831-ffffffff8179a84b: amd_iommu_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_device *amd_iommu_probe_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a68d0)
Location: drivers/iommu/amd/iommu.c:2216
Inline: True
```
**Symbols:**

```
ffffffff817a6680-ffffffff817a68c6: amd_iommu_probe_device.part.0 (STB_LOCAL)
ffffffff81c0b6fb-ffffffff81c0b715: amd_iommu_probe_device.part.0.cold (STB_LOCAL)
ffffffff817a68d0-ffffffff817a690f: amd_iommu_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_device *amd_iommu_probe_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81788f10)
Location: drivers/iommu/amd/iommu.c:1677
Inline: True
```
**Symbols:**

```
ffffffff81788ed0-ffffffff81789142: amd_iommu_probe_device (STB_LOCAL)
ffffffff81bfd1cc-ffffffff81bfd1e6: amd_iommu_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_device *amd_iommu_probe_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180ec70)
Location: drivers/iommu/amd/iommu.c:1726
Inline: True
```
**Symbols:**

```
ffffffff8180ec30-ffffffff8180eeae: amd_iommu_probe_device (STB_LOCAL)
ffffffff81cfe0fa-ffffffff81cfe128: amd_iommu_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_device *amd_iommu_probe_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81950e2d)
Location: drivers/iommu/amd/iommu.c:1748
Inline: True
```
**Symbols:**

```
ffffffff81950df0-ffffffff81951068: amd_iommu_probe_device (STB_LOCAL)
ffffffff81ec6b23-ffffffff81ec6b37: amd_iommu_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct iommu_device *amd_iommu_probe_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab5530)
Location: drivers/iommu/amd/iommu.c:1862
Inline: False
```
**Symbols:**

```
ffffffff81ab5530-ffffffff81ab5762: amd_iommu_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct iommu_device *amd_iommu_probe_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b01680)
Location: drivers/iommu/amd/iommu.c:1887
Inline: False
```
**Symbols:**

```
ffffffff81b01680-ffffffff81b0198c: amd_iommu_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iommu_device *amd_iommu_probe_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b54c80)
Location: drivers/iommu/amd/iommu.c:1935
Inline: False
```
**Symbols:**

```
ffffffff81b54c80-ffffffff81b55069: amd_iommu_probe_device (STB_LOCAL)
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
