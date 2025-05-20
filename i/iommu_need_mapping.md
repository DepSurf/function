# Function: <code>iommu_need_mapping</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool iommu_need_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cb23d)
Location: drivers/iommu/intel-iommu.c:3449
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816cb1c0-ffffffff816cb294: iommu_need_mapping (STB_LOCAL)
ffffffff816cc67c-ffffffff816cc696: iommu_need_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool iommu_need_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eea00)
Location: drivers/iommu/intel-iommu.c:3461
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816ee970-ffffffff816eea56: iommu_need_mapping (STB_LOCAL)
ffffffff816efeeb-ffffffff816efeff: iommu_need_mapping.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool iommu_need_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4170)
Location: drivers/iommu/intel-iommu.c:3461
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816b40e0-ffffffff816b41c6: iommu_need_mapping (STB_LOCAL)
ffffffff816b56d1-ffffffff816b56e5: iommu_need_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool iommu_need_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81691e30)
Location: drivers/iommu/intel-iommu.c:3461
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff81691da0-ffffffff81691e86: iommu_need_mapping (STB_LOCAL)
ffffffff8169331b-ffffffff8169332f: iommu_need_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool iommu_need_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e26c0)
Location: drivers/iommu/intel-iommu.c:3461
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816e2630-ffffffff816e2716: iommu_need_mapping (STB_LOCAL)
ffffffff816e3bab-ffffffff816e3bbf: iommu_need_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool iommu_need_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fcd20)
Location: drivers/iommu/intel-iommu.c:3461
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816fcc90-ffffffff816fcd76: iommu_need_mapping (STB_LOCAL)
ffffffff816fe257-ffffffff816fe26b: iommu_need_mapping.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
