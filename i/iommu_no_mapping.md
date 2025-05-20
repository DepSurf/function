# Function: <code>iommu_no_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int iommu_no_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153a0a0)
Location: drivers/iommu/intel-iommu.c:3381
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
**Symbols:**

```
ffffffff8153a0a0-ffffffff8153a166: iommu_no_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int iommu_no_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158eb50)
Location: drivers/iommu/intel-iommu.c:3442
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8158eb50-ffffffff8158ec14: iommu_no_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int iommu_no_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bc670)
Location: drivers/iommu/intel-iommu.c:3533
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815bc670-ffffffff815bc734: iommu_no_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iommu_no_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d24f0)
Location: drivers/iommu/intel-iommu.c:3529
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815d24f0-ffffffff815d25b0: iommu_no_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iommu_no_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816392d0)
Location: drivers/iommu/intel-iommu.c:3537
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816392d0-ffffffff81639390: iommu_no_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iommu_no_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3593
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81674510-ffffffff816745b3: iommu_no_mapping (STB_LOCAL)
ffffffff816757bb-ffffffff816757f6: iommu_no_mapping.cold.97 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iommu_no_mapping(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692b93)
Location: drivers/iommu/intel-iommu.c:3609
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:__intel_map_page
```
**Symbols:**

```
ffffffff81692b40-ffffffff81692be3: iommu_no_mapping (STB_LOCAL)
ffffffff81693cbb-ffffffff81693cf6: iommu_no_mapping.cold.102 (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
</ul>
