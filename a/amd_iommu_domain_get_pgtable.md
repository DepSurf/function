# Function: <code>amd_iommu_domain_get_pgtable</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8179651b)
Location: drivers/iommu/amd/iommu.c:156
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:fetch_pte
  - drivers/iommu/amd/iommu.c:increase_address_space
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4cfb)
Location: drivers/iommu/amd/iommu.c:154
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:fetch_pte
  - drivers/iommu/amd/iommu.c:increase_address_space
```
</details>
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
