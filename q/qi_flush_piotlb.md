# Function: <code>qi_flush_piotlb</code>

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
void qi_flush_piotlb(struct intel_iommu *iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1400
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:domain_flush_piotlb
  - drivers/iommu/intel/iommu.c:domain_flush_piotlb
```
**Symbols:**

```
ffffffff8179eeab-ffffffff8179eec0: qi_flush_piotlb.cold (STB_LOCAL)
ffffffff8179e360-ffffffff8179e458: qi_flush_piotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void qi_flush_piotlb(struct intel_iommu *iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1439
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:domain_flush_piotlb
  - drivers/iommu/intel/iommu.c:domain_flush_piotlb
```
**Symbols:**

```
ffffffff81c0c2f3-ffffffff81c0c308: qi_flush_piotlb.cold (STB_LOCAL)
ffffffff817ac0c0-ffffffff817ac1b0: qi_flush_piotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void qi_flush_piotlb(struct intel_iommu *iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1508
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:domain_flush_piotlb
  - drivers/iommu/intel/iommu.c:domain_flush_piotlb
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81bfdb5d-ffffffff81bfdb72: qi_flush_piotlb.cold (STB_LOCAL)
ffffffff8178ef90-ffffffff8178f085: qi_flush_piotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void qi_flush_piotlb(struct intel_iommu *iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1537
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:domain_flush_piotlb
  - drivers/iommu/intel/iommu.c:domain_flush_piotlb
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
**Symbols:**

```
ffffffff81cff118-ffffffff81cff17a: qi_flush_piotlb.cold (STB_LOCAL)
ffffffff81816840-ffffffff81816963: qi_flush_piotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void qi_flush_piotlb(struct intel_iommu *iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1533
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
**Symbols:**

```
ffffffff81ec78e4-ffffffff81ec7946: qi_flush_piotlb.cold (STB_LOCAL)
ffffffff819577f0-ffffffff81957926: qi_flush_piotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void qi_flush_piotlb(struct intel_iommu *iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1522
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff82097384-ffffffff820973e1: qi_flush_piotlb.cold (STB_LOCAL)
ffffffff81abe740-ffffffff81abe889: qi_flush_piotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void qi_flush_piotlb(struct intel_iommu *iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1543
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff821183ea-ffffffff82118447: qi_flush_piotlb.cold (STB_LOCAL)
ffffffff81b0b0d0-ffffffff81b0b219: qi_flush_piotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void qi_flush_piotlb(struct intel_iommu *iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1552
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_flush_pasid_iotlb
  - drivers/iommu/intel/iommu.c:domain_flush_pasid_iotlb
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user
```
**Symbols:**

```
ffffffff821f60fe-ffffffff821f6151: qi_flush_piotlb.cold (STB_LOCAL)
ffffffff81b5f130-ffffffff81b5f27b: qi_flush_piotlb (STB_GLOBAL)
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
