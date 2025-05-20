# Function: <code>qi_flush_dev_iotlb_pasid</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb_pasid(struct intel_iommu *iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order, u64 granu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1441
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
```
**Symbols:**

```
ffffffff8179eec0-ffffffff8179eed7: qi_flush_dev_iotlb_pasid.cold (STB_LOCAL)
ffffffff8179e460-ffffffff8179e59a: qi_flush_dev_iotlb_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb_pasid(struct intel_iommu *iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1480
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81c0c308-ffffffff81c0c31f: qi_flush_dev_iotlb_pasid.cold (STB_LOCAL)
ffffffff817ac1b0-ffffffff817ac2e4: qi_flush_dev_iotlb_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb_pasid(struct intel_iommu *iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1549
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81bfdb72-ffffffff81bfdb89: qi_flush_dev_iotlb_pasid.cold (STB_LOCAL)
ffffffff8178f090-ffffffff8178f1bf: qi_flush_dev_iotlb_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb_pasid(struct intel_iommu *iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1578
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
**Symbols:**

```
ffffffff81cff17a-ffffffff81cff212: qi_flush_dev_iotlb_pasid.cold (STB_LOCAL)
ffffffff81816970-ffffffff81816ad1: qi_flush_dev_iotlb_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb_pasid(struct intel_iommu *iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1574
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
**Symbols:**

```
ffffffff81ec7946-ffffffff81ec7a21: qi_flush_dev_iotlb_pasid.cold (STB_LOCAL)
ffffffff81957930-ffffffff81957aac: qi_flush_dev_iotlb_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb_pasid(struct intel_iommu *iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1563
Inline: False
```
**Symbols:**

```
ffffffff820973e1-ffffffff8209749d: qi_flush_dev_iotlb_pasid.cold (STB_LOCAL)
ffffffff81abe8a0-ffffffff81abea32: qi_flush_dev_iotlb_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb_pasid(struct intel_iommu *iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1584
Inline: False
```
**Symbols:**

```
ffffffff82118447-ffffffff821184c0: qi_flush_dev_iotlb_pasid.cold (STB_LOCAL)
ffffffff81b0b230-ffffffff81b0b3c6: qi_flush_dev_iotlb_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb_pasid(struct intel_iommu *iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1593
Inline: False
```
**Symbols:**

```
ffffffff821f6151-ffffffff821f61ca: qi_flush_dev_iotlb_pasid.cold (STB_LOCAL)
ffffffff81b5f290-ffffffff81b5f439: qi_flush_dev_iotlb_pasid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 granu</code>
</li>
</ul>
</details>
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
