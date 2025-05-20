# Function: <code>iommu_setup_dma_ops</code>

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
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:1142
Inline: False
```
**Symbols:**

```
ffffffff81792cdf-ffffffff81792d1a: iommu_setup_dma_ops.cold (STB_LOCAL)
ffffffff81792a60-ffffffff81792bc2: iommu_setup_dma_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:1320
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
```
**Symbols:**

```
ffffffff81c0d723-ffffffff81c0d742: iommu_setup_dma_ops.cold (STB_LOCAL)
ffffffff817bf540-ffffffff817bf59c: iommu_setup_dma_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:1314
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
```
**Symbols:**

```
ffffffff81bffa8c-ffffffff81bffaab: iommu_setup_dma_ops.cold (STB_LOCAL)
ffffffff817a24f0-ffffffff817a254c: iommu_setup_dma_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 dma_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81d01f56)
Location: drivers/iommu/dma-iommu.c:1331
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
**Symbols:**

```
ffffffff81d01f56-ffffffff81d01f75: iommu_setup_dma_ops.cold (STB_LOCAL)
ffffffff8182b780-ffffffff8182b7dc: iommu_setup_dma_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 dma_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81eca463)
Location: drivers/iommu/dma-iommu.c:1488
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
**Symbols:**

```
ffffffff81eca463-ffffffff81eca482: iommu_setup_dma_ops.cold (STB_LOCAL)
ffffffff8196c850-ffffffff8196c8c8: iommu_setup_dma_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 dma_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad6ee0)
Location: drivers/iommu/dma-iommu.c:1572
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
**Symbols:**

```
ffffffff81ad6ee0-ffffffff81ad6f8b: iommu_setup_dma_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 dma_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b256d0)
Location: drivers/iommu/dma-iommu.c:1616
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
**Symbols:**

```
ffffffff81b256d0-ffffffff81b2577b: iommu_setup_dma_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 dma_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7c410)
Location: drivers/iommu/dma-iommu.c:1737
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
**Symbols:**

```
ffffffff81b7c410-ffffffff81b7c4bb: iommu_setup_dma_ops (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void iommu_setup_dma_ops(struct device *dev, u64 dma_base, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108ca630)
Location: drivers/iommu/dma-iommu.c:1115
Inline: False
Direct callers:
  - arch/arm64/mm/dma-mapping.c:arch_setup_dma_ops
```
**Symbols:**

```
ffff8000108ca630-ffff8000108caa30: iommu_setup_dma_ops (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 dma_limit</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 size</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
</ul>
