# Function: <code>dev_to_iommu_pmu</code>

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
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/perfmon.c (ffffffff81b1a8a5)
Location: drivers/iommu/intel/perfmon.c:62
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:int_cache_hit_posted_is_visible
  - drivers/iommu/intel/perfmon.c:int_cache_hit_nonposted_is_visible
  - drivers/iommu/intel/perfmon.c:int_cache_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:hpt_leaf_hit_is_visible
  - drivers/iommu/intel/perfmon.c:hpt_leaf_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:iotlb_hit_is_visible
  - drivers/iommu/intel/perfmon.c:iotlb_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:hpt_nonleaf_hit_is_visible
  - drivers/iommu/intel/perfmon.c:hpt_nonleaf_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:fs_nonleaf_hit_is_visible
  - drivers/iommu/intel/perfmon.c:fs_nonleaf_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:ss_nonleaf_hit_is_visible
  - drivers/iommu/intel/perfmon.c:ss_nonleaf_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:pasid_cache_hit_is_visible
  - drivers/iommu/intel/perfmon.c:pasid_cache_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:ctxt_cache_hit_is_visible
  - drivers/iommu/intel/perfmon.c:ctxt_cache_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:pg_req_posted_is_visible
  - drivers/iommu/intel/perfmon.c:iommu_mem_blocked_is_visible
  - drivers/iommu/intel/perfmon.c:iommu_mrds_is_visible
  - drivers/iommu/intel/perfmon.c:ats_blocked_is_visible
  - drivers/iommu/intel/perfmon.c:pw_occupancy_is_visible
  - drivers/iommu/intel/perfmon.c:iommu_requests_is_visible
  - drivers/iommu/intel/perfmon.c:iommu_clocks_is_visible
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/perfmon.c (ffffffff81b703d5)
Location: drivers/iommu/intel/perfmon.c:62
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:int_cache_hit_posted_is_visible
  - drivers/iommu/intel/perfmon.c:int_cache_hit_nonposted_is_visible
  - drivers/iommu/intel/perfmon.c:int_cache_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:hpt_leaf_hit_is_visible
  - drivers/iommu/intel/perfmon.c:hpt_leaf_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:iotlb_hit_is_visible
  - drivers/iommu/intel/perfmon.c:iotlb_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:hpt_nonleaf_hit_is_visible
  - drivers/iommu/intel/perfmon.c:hpt_nonleaf_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:fs_nonleaf_hit_is_visible
  - drivers/iommu/intel/perfmon.c:fs_nonleaf_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:ss_nonleaf_hit_is_visible
  - drivers/iommu/intel/perfmon.c:ss_nonleaf_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:pasid_cache_hit_is_visible
  - drivers/iommu/intel/perfmon.c:pasid_cache_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:ctxt_cache_hit_is_visible
  - drivers/iommu/intel/perfmon.c:ctxt_cache_lookup_is_visible
  - drivers/iommu/intel/perfmon.c:pg_req_posted_is_visible
  - drivers/iommu/intel/perfmon.c:iommu_mem_blocked_is_visible
  - drivers/iommu/intel/perfmon.c:iommu_mrds_is_visible
  - drivers/iommu/intel/perfmon.c:ats_blocked_is_visible
  - drivers/iommu/intel/perfmon.c:pw_occupancy_is_visible
  - drivers/iommu/intel/perfmon.c:iommu_requests_is_visible
  - drivers/iommu/intel/perfmon.c:iommu_clocks_is_visible
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
