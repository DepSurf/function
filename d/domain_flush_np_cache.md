# Function: <code>domain_flush_np_cache</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be692)
Location: drivers/iommu/amd_iommu.c:1310
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e15a2)
Location: drivers/iommu/amd_iommu.c:1332
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816e14e0-ffffffff816e1538: domain_flush_np_cache.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81799be1)
Location: drivers/iommu/amd/iommu.c:1270
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a8311)
Location: drivers/iommu/amd/iommu.c:1360
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81789f34)
Location: drivers/iommu/amd/iommu.c:1292
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff818111ac)
Location: drivers/iommu/amd/iommu.c:1341
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8195212e)
Location: drivers/iommu/amd/iommu.c:1363
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab723e)
Location: drivers/iommu/amd/iommu.c:1445
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b0355e)
Location: drivers/iommu/amd/iommu.c:1465
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b5731c)
Location: drivers/iommu/amd/iommu.c:1571
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6ff2)
Location: drivers/iommu/amd_iommu.c:1332
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816a6f30-ffffffff816a6f88: domain_flush_np_cache.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816849e2)
Location: drivers/iommu/amd_iommu.c:1332
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff81684920-ffffffff81684978: domain_flush_np_cache.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d5262)
Location: drivers/iommu/amd_iommu.c:1332
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816d51a0-ffffffff816d51f8: domain_flush_np_cache.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816efba2)
Location: drivers/iommu/amd_iommu.c:1332
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816efae0-ffffffff816efb38: domain_flush_np_cache.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
