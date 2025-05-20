# Function: <code>domain_flush_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152dcb0)
Location: drivers/iommu/amd_iommu.c:1088
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_page
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
**Symbols:**

```
ffffffff8152dcb0-ffffffff8152dd06: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81583021)
Location: drivers/iommu/amd_iommu.c:1184
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__queue_flush
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
```
**Symbols:**

```
ffffffff81581800-ffffffff81581858: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815aeed0)
Location: drivers/iommu/amd_iommu.c:1273
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__queue_flush
```
**Symbols:**

```
ffffffff815aeed0-ffffffff815aef42: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c4c20)
Location: drivers/iommu/amd_iommu.c:1332
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:dma_ops_domain_flush_tlb
```
**Symbols:**

```
ffffffff815c4c20-ffffffff815c4c70: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162ba80)
Location: drivers/iommu/amd_iommu.c:1273
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff8162ba80-ffffffff8162bad0: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816666e0)
Location: drivers/iommu/amd_iommu.c:1279
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816666e0-ffffffff8166672e: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684fb0)
Location: drivers/iommu/amd_iommu.c:1294
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff81684fb0-ffffffff81684ffe: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bc4c0)
Location: drivers/iommu/amd_iommu.c:1293
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816bc4c0-ffffffff816bc50e: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816df420)
Location: drivers/iommu/amd_iommu.c:1315
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816df420-ffffffff816df46e: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81796030)
Location: drivers/iommu/amd/iommu.c:1253
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:increase_address_space
```
**Symbols:**

```
ffffffff81796030-ffffffff8179607e: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4750)
Location: drivers/iommu/amd/iommu.c:1343
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:increase_address_space
```
**Symbols:**

```
ffffffff817a4750-ffffffff817a479e: domain_flush_complete (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4e70)
Location: drivers/iommu/amd_iommu.c:1315
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816a4e70-ffffffff816a4ebe: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682860)
Location: drivers/iommu/amd_iommu.c:1315
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff81682860-ffffffff816828ae: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d30e0)
Location: drivers/iommu/amd_iommu.c:1315
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816d30e0-ffffffff816d312e: domain_flush_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ed780)
Location: drivers/iommu/amd_iommu.c:1315
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816ed780-ffffffff816ed7ce: domain_flush_complete (STB_LOCAL)
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
