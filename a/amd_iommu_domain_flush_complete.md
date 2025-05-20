# Function: <code>amd_iommu_domain_flush_complete</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void amd_iommu_domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81789870)
Location: drivers/iommu/amd/iommu.c:1275
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff81789870-ffffffff817898be: amd_iommu_domain_flush_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void amd_iommu_domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1324
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff81cfe31f-ffffffff81cfe334: amd_iommu_domain_flush_complete.cold (STB_LOCAL)
ffffffff81810a70-ffffffff81810aef: amd_iommu_domain_flush_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81950d76)
Location: drivers/iommu/amd/iommu.c:1346
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff81952790-ffffffff819527fa: amd_iommu_domain_flush_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab6156)
Location: drivers/iommu/amd/iommu.c:1428
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
```
**Symbols:**

```
ffffffff81ab79b0-ffffffff81ab7a1a: amd_iommu_domain_flush_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b01aea)
Location: drivers/iommu/amd/iommu.c:1448
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
```
**Symbols:**

```
ffffffff81b03bd0-ffffffff81b03c62: amd_iommu_domain_flush_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_flush_complete(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b5670b)
Location: drivers/iommu/amd/iommu.c:1554
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
```
**Symbols:**

```
ffffffff81b57860-ffffffff81b578f2: amd_iommu_domain_flush_complete (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
