# Function: <code>iommu_flush_iotlb_psi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81536420)
Location: drivers/iommu/intel-iommu.c:1532
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:flush_unmaps
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81536420-ffffffff81536535: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158b730)
Location: drivers/iommu/intel-iommu.c:1571
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8158b730-ffffffff8158b846: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b8e80)
Location: drivers/iommu/intel-iommu.c:1585
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815b8e80-ffffffff815b8f96: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815ce700)
Location: drivers/iommu/intel-iommu.c:1590
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815ce700-ffffffff815ce80d: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816355e0)
Location: drivers/iommu/intel-iommu.c:1573
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816355e0-ffffffff816356f3: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81670b90)
Location: drivers/iommu/intel-iommu.c:1590
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
```
**Symbols:**

```
ffffffff81670b90-ffffffff81670c87: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f490)
Location: drivers/iommu/intel-iommu.c:1467
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
```
**Symbols:**

```
ffffffff8168f490-ffffffff8168f587: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c7010)
Location: drivers/iommu/intel-iommu.c:1475
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816c7010-ffffffff816c7104: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e9ea0)
Location: drivers/iommu/intel-iommu.c:1486
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816e9ea0-ffffffff816e9f94: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a0970)
Location: drivers/iommu/intel/iommu.c:1515
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff817a0970-ffffffff817a0a7e: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817aec40)
Location: drivers/iommu/intel/iommu.c:1615
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_map
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
```
**Symbols:**

```
ffffffff817aec40-ffffffff817aed4e: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791400)
Location: drivers/iommu/intel/iommu.c:1639
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81791400-ffffffff8179150a: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1643
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff818188c0-ffffffff81818a22: iommu_flush_iotlb_psi (STB_LOCAL)
ffffffff81cff376-ffffffff81cff3a4: iommu_flush_iotlb_psi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1542
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81959610-ffffffff819597e5: iommu_flush_iotlb_psi (STB_LOCAL)
ffffffff81ec7b4b-ffffffff81ec7b81: iommu_flush_iotlb_psi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1509
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81ac0f70-ffffffff81ac110b: iommu_flush_iotlb_psi (STB_LOCAL)
ffffffff8209749d-ffffffff820974cb: iommu_flush_iotlb_psi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1479
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81b0d7e0-ffffffff81b0d99e: iommu_flush_iotlb_psi (STB_LOCAL)
ffffffff821184c0-ffffffff821184e6: iommu_flush_iotlb_psi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1419
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81b621d0-ffffffff81b622ed: iommu_flush_iotlb_psi (STB_LOCAL)
ffffffff821f6204-ffffffff821f6232: iommu_flush_iotlb_psi.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816af980)
Location: drivers/iommu/intel-iommu.c:1486
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816af980-ffffffff816afa74: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168d2d0)
Location: drivers/iommu/intel-iommu.c:1486
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff8168d2d0-ffffffff8168d3c4: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ddb60)
Location: drivers/iommu/intel-iommu.c:1486
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816ddb60-ffffffff816ddc54: iommu_flush_iotlb_psi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_flush_iotlb_psi(struct intel_iommu *iommu, struct dmar_domain *domain, long unsigned int pfn, unsigned int pages, int ih, int map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f8160)
Location: drivers/iommu/intel-iommu.c:1486
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816f8160-ffffffff816f8254: iommu_flush_iotlb_psi (STB_LOCAL)
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
