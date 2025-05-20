# Function: <code>arm_smmu_readl</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 arm_smmu_readl(struct arm_smmu_device *smmu, int page, int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/arm-smmu.c (ffff8000108d1da4)
Location: drivers/iommu/arm-smmu.h:345
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:__arm_smmu_tlb_sync
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
```
```
In drivers/iommu/arm-smmu-impl.c (ffff8000108d3158)
Location: drivers/iommu/arm-smmu.h:345
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
```
**Symbols:**

```
ffff8000108d0b40-ffff8000108d0b90: arm_smmu_readl (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
