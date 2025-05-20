# Function: <code>quirk_extra_dev_tlb_flush</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void quirk_extra_dev_tlb_flush(struct device_domain_info *info, long unsigned int address, long unsigned int mask, u32 pasid, u16 qdep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac40d6)
Location: drivers/iommu/intel/iommu.c:5052
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
```
**Symbols:**

```
ffffffff81ac5fa0-ffffffff81ac6046: quirk_extra_dev_tlb_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void quirk_extra_dev_tlb_flush(struct device_domain_info *info, long unsigned int address, long unsigned int mask, u32 pasid, u16 qdep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b10a89)
Location: drivers/iommu/intel/iommu.c:5010
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
```
**Symbols:**

```
ffffffff81b12a60-ffffffff81b12b06: quirk_extra_dev_tlb_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void quirk_extra_dev_tlb_flush(struct device_domain_info *info, long unsigned int address, long unsigned int mask, u32 pasid, u16 qdep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b65559)
Location: drivers/iommu/intel/iommu.c:5136
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:parent_domain_flush
  - drivers/iommu/intel/iommu.c:parent_domain_flush
Direct callers:
  - drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user
```
**Symbols:**

```
ffffffff81b678a0-ffffffff81b67946: quirk_extra_dev_tlb_flush (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
