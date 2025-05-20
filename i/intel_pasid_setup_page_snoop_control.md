# Function: <code>intel_pasid_setup_page_snoop_control</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pasid_setup_page_snoop_control(struct intel_iommu *iommu, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8195f4d0)
Location: drivers/iommu/intel/pasid.c:703
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
**Symbols:**

```
ffffffff8195f4d0-ffffffff8195f62f: intel_pasid_setup_page_snoop_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pasid_setup_page_snoop_control(struct intel_iommu *iommu, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac70f0)
Location: drivers/iommu/intel/pasid.c:721
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
**Symbols:**

```
ffffffff81ac70f0-ffffffff81ac724f: intel_pasid_setup_page_snoop_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pasid_setup_page_snoop_control(struct intel_iommu *iommu, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b13c50)
Location: drivers/iommu/intel/pasid.c:678
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
**Symbols:**

```
ffffffff81b13c50-ffffffff81b13db2: intel_pasid_setup_page_snoop_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pasid_setup_page_snoop_control(struct intel_iommu *iommu, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b68ad0)
Location: drivers/iommu/intel/pasid.c:536
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
**Symbols:**

```
ffffffff81b68ad0-ffffffff81b68c32: intel_pasid_setup_page_snoop_control (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
