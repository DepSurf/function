# Function: <code>__domain_flush_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152f4c0)
Location: drivers/iommu/amd_iommu.c:1039
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:__map_single
  - drivers/iommu/amd_iommu.c:__map_single
```
**Symbols:**

```
ffffffff8152f4c0-ffffffff8152f6b8: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81582da0)
Location: drivers/iommu/amd_iommu.c:1135
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:__queue_flush
```
**Symbols:**

```
ffffffff81582da0-ffffffff81582fbe: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b00d0)
Location: drivers/iommu/amd_iommu.c:1224
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:__queue_flush
```
**Symbols:**

```
ffffffff815b00d0-ffffffff815b02e4: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c5440)
Location: drivers/iommu/amd_iommu.c:1283
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:dma_ops_domain_flush_tlb
```
**Symbols:**

```
ffffffff815c5440-ffffffff815c5548: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162c190)
Location: drivers/iommu/amd_iommu.c:1224
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff8162c190-ffffffff8162c298: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667680)
Location: drivers/iommu/amd_iommu.c:1230
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff81667680-ffffffff8166777f: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81686130)
Location: drivers/iommu/amd_iommu.c:1245
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff81686130-ffffffff8168622f: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1244
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816bd9e0-ffffffff816bdae6: __domain_flush_pages (STB_LOCAL)
ffffffff816c1214-ffffffff816c1227: __domain_flush_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0bd0)
Location: drivers/iommu/amd_iommu.c:1266
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816e0bd0-ffffffff816e0cdf: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817969e0)
Location: drivers/iommu/amd/iommu.c:1210
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff817969e0-ffffffff81796aed: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5100)
Location: drivers/iommu/amd/iommu.c:1300
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff817a5100-ffffffff817a520d: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787400)
Location: drivers/iommu/amd/iommu.c:1232
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81787400-ffffffff817875af: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1244
Inline: True
```
**Symbols:**

```
ffffffff8180e6e0-ffffffff8180e822: __domain_flush_pages.constprop.0 (STB_LOCAL)
ffffffff81cfe088-ffffffff81cfe09d: __domain_flush_pages.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1266
Inline: True
```
**Symbols:**

```
ffffffff8194f900-ffffffff8194faee: __domain_flush_pages.constprop.0 (STB_LOCAL)
ffffffff81ec6a16-ffffffff81ec6a2b: __domain_flush_pages.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1348
Inline: True
```
**Symbols:**

```
ffffffff81ab4a40-ffffffff81ab4c28: __domain_flush_pages.constprop.0 (STB_LOCAL)
ffffffff82096e2c-ffffffff82096e41: __domain_flush_pages.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1368
Inline: True
```
**Symbols:**

```
ffffffff81b010b0-ffffffff81b01227: __domain_flush_pages.constprop.0 (STB_LOCAL)
ffffffff82117d41-ffffffff82117d56: __domain_flush_pages.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b547a0)
Location: drivers/iommu/amd/iommu.c:1461
Inline: False
```
**Symbols:**

```
ffffffff81b547a0-ffffffff81b549c6: __domain_flush_pages (STB_LOCAL)
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
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6620)
Location: drivers/iommu/amd_iommu.c:1266
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816a6620-ffffffff816a672f: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684010)
Location: drivers/iommu/amd_iommu.c:1266
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff81684010-ffffffff8168411f: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d4890)
Location: drivers/iommu/amd_iommu.c:1266
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816d4890-ffffffff816d499f: __domain_flush_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain *domain, u64 address, size_t size, int pde);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eef90)
Location: drivers/iommu/amd_iommu.c:1266
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
**Symbols:**

```
ffffffff816eef90-ffffffff816ef09f: __domain_flush_pages (STB_LOCAL)
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
