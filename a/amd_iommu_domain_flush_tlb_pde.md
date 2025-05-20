# Function: <code>amd_iommu_domain_flush_tlb_pde</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8178a769)
Location: drivers/iommu/amd/iommu.c:1270
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff81789840-ffffffff81789861: amd_iommu_domain_flush_tlb_pde (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81811254)
Location: drivers/iommu/amd/iommu.c:1319
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff81810a50-ffffffff81810a6c: amd_iommu_domain_flush_tlb_pde (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81950cb0)
Location: drivers/iommu/amd/iommu.c:1341
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff81952760-ffffffff81952786: amd_iommu_domain_flush_tlb_pde (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab6080)
Location: drivers/iommu/amd/iommu.c:1423
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
```
**Symbols:**

```
ffffffff81ab7970-ffffffff81ab7996: amd_iommu_domain_flush_tlb_pde (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b019e0)
Location: drivers/iommu/amd/iommu.c:1443
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
```
**Symbols:**

```
ffffffff81b03b90-ffffffff81b03bb6: amd_iommu_domain_flush_tlb_pde (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
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
</ul>
