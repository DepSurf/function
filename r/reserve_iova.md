# Function: <code>reserve_iova</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8152d1e0)
Location: drivers/iommu/iova.c:452
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8152d1e0-ffffffff8152d2b5: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580570)
Location: drivers/iommu/iova.c:533
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff81580570-ffffffff8158063e: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815ad110)
Location: drivers/iommu/iova.c:533
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff815ad110-ffffffff815ad1de: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c2c90)
Location: drivers/iommu/iova.c:507
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff815c2c90-ffffffff815c2d67: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629750)
Location: drivers/iommu/iova.c:651
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff81629750-ffffffff81629856: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81664450)
Location: drivers/iommu/iova.c:651
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff81664450-ffffffff81664563: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816825e0)
Location: drivers/iommu/iova.c:660
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816825e0-ffffffff816826f3: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:659
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816bb0ee-ffffffff816bb104: reserve_iova.cold (STB_LOCAL)
ffffffff816b9e00-ffffffff816b9f0f: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dcc00)
Location: drivers/iommu/iova.c:661
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816dcc00-ffffffff816dcd16: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81793bc0)
Location: drivers/iommu/iova.c:661
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/intel/iommu.c:intel_iommu_apply_resv_region
  - drivers/iommu/intel/iommu.c:dmar_init_reserved_ranges
  - drivers/iommu/intel/iommu.c:dmar_init_reserved_ranges
```
**Symbols:**

```
ffffffff81793bc0-ffffffff81793ccf: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0150)
Location: drivers/iommu/iova.c:676
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/iova.c:copy_reserved_iova
```
**Symbols:**

```
ffffffff817c0150-ffffffff817c025f: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a32c0)
Location: drivers/iommu/iova.c:743
Inline: False
```
**Symbols:**

```
ffffffff817a32c0-ffffffff817a33cf: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:755
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff81d0209d-ffffffff81d020bd: reserve_iova.cold (STB_LOCAL)
ffffffff8182cb90-ffffffff8182ccf8: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:572
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff81eca5a6-ffffffff81eca5c6: reserve_iova.cold (STB_LOCAL)
ffffffff8196de30-ffffffff8196dfb7: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:577
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff82098121-ffffffff82098141: reserve_iova.cold (STB_LOCAL)
ffffffff81ad8770-ffffffff81ad88f7: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:577
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff82119110-ffffffff82119130: reserve_iova.cold (STB_LOCAL)
ffffffff81b26890-ffffffff81b26a19: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:578
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff821f70ec-ffffffff821f710c: reserve_iova.cold (STB_LOCAL)
ffffffff81b7d4d0-ffffffff81b7d659: reserve_iova (STB_GLOBAL)
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
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cd2d8)
Location: drivers/iommu/iova.c:661
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/iova.c:copy_reserved_iova
```
**Symbols:**

```
ffff8000108cd2d8-ffff8000108cd470: reserve_iova (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2650)
Location: drivers/iommu/iova.c:661
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816a2650-ffffffff816a2766: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680040)
Location: drivers/iommu/iova.c:661
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff81680040-ffffffff81680156: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d08c0)
Location: drivers/iommu/iova.c:661
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816d08c0-ffffffff816d09d6: reserve_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct iova *reserve_iova(struct iova_domain *iovad, long unsigned int pfn_lo, long unsigned int pfn_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eae50)
Location: drivers/iommu/iova.c:661
Inline: False
Direct callers:
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816eae50-ffffffff816eaf66: reserve_iova (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
