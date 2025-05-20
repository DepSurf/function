# Function: <code>amd_iommu_iotlb_sync_map</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void amd_iommu_iotlb_sync_map(struct iommu_domain *dom, long unsigned int iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2050
Inline: False
```
**Symbols:**

```
ffffffff81811190-ffffffff8181121c: amd_iommu_iotlb_sync_map (STB_LOCAL)
ffffffff81cfe386-ffffffff81cfe3a3: amd_iommu_iotlb_sync_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void amd_iommu_iotlb_sync_map(struct iommu_domain *dom, long unsigned int iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2066
Inline: False
```
**Symbols:**

```
ffffffff81952110-ffffffff81952201: amd_iommu_iotlb_sync_map (STB_LOCAL)
ffffffff81ec6bdd-ffffffff81ec6bfa: amd_iommu_iotlb_sync_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void amd_iommu_iotlb_sync_map(struct iommu_domain *dom, long unsigned int iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2201
Inline: False
```
**Symbols:**

```
ffffffff81ab7220-ffffffff81ab7311: amd_iommu_iotlb_sync_map (STB_LOCAL)
ffffffff82096ff5-ffffffff82097012: amd_iommu_iotlb_sync_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void amd_iommu_iotlb_sync_map(struct iommu_domain *dom, long unsigned int iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2222
Inline: False
```
**Symbols:**

```
ffffffff81b03540-ffffffff81b03666: amd_iommu_iotlb_sync_map (STB_LOCAL)
ffffffff82117edb-ffffffff82117ef8: amd_iommu_iotlb_sync_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int amd_iommu_iotlb_sync_map(struct iommu_domain *dom, long unsigned int iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2320
Inline: False
```
**Symbols:**

```
ffffffff81b57300-ffffffff81b57395: amd_iommu_iotlb_sync_map (STB_LOCAL)
ffffffff821f5b33-ffffffff821f5b50: amd_iommu_iotlb_sync_map.cold (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
