# Function: <code>arm_smmu_writel</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/arm-smmu.c (ffff8000108cfed0)
Location: drivers/iommu/arm-smmu.h:352
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_write_sme
  - drivers/iommu/arm-smmu.c:arm_smmu_write_s2cr
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_vmid_nosync
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_range_s2
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_range_s1
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_context_s2
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_context_s1
  - drivers/iommu/arm-smmu.c:__arm_smmu_tlb_sync
```
```
In drivers/iommu/arm-smmu-impl.c (ffff8000108d31a4)
Location: drivers/iommu/arm-smmu.h:352
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
```
</details>
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
