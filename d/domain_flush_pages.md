# Function: <code>domain_flush_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152f772)
Location: drivers/iommu/amd_iommu.c:1070
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__map_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81583b09)
Location: drivers/iommu/amd_iommu.c:1166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b0e19)
Location: drivers/iommu/amd_iommu.c:1255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c7274)
Location: drivers/iommu/amd_iommu.c:1314
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162df04)
Location: drivers/iommu/amd_iommu.c:1255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816685ba)
Location: drivers/iommu/amd_iommu.c:1261
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81686f4a)
Location: drivers/iommu/amd_iommu.c:1276
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be6ac)
Location: drivers/iommu/amd_iommu.c:1275
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e1515)
Location: drivers/iommu/amd_iommu.c:1297
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff81799c10)
Location: drivers/iommu/amd/iommu.c:1241
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
In drivers/iommu/amd/iommu.c (ffffffff817a8340)
Location: drivers/iommu/amd/iommu.c:1331
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
In drivers/iommu/amd/iommu.c (ffffffff81789f81)
Location: drivers/iommu/amd/iommu.c:1263
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_map
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
Location: drivers/iommu/amd/iommu.c:1275
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff8180e830-ffffffff8180e8c1: domain_flush_pages.constprop.0 (STB_LOCAL)
ffffffff81cfe09d-ffffffff81cfe0d0: domain_flush_pages.constprop.0.cold (STB_LOCAL)
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
Location: drivers/iommu/amd/iommu.c:1297
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff8194faf0-ffffffff8194fb9a: domain_flush_pages.constprop.0 (STB_LOCAL)
ffffffff81ec6a2b-ffffffff81ec6a5f: domain_flush_pages.constprop.0.cold (STB_LOCAL)
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
Location: drivers/iommu/amd/iommu.c:1379
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81ab4c40-ffffffff81ab4cea: domain_flush_pages.constprop.0 (STB_LOCAL)
ffffffff82096e41-ffffffff82096e75: domain_flush_pages.constprop.0.cold (STB_LOCAL)
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
Location: drivers/iommu/amd/iommu.c:1399
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81b01240-ffffffff81b012ea: domain_flush_pages.constprop.0 (STB_LOCAL)
ffffffff82117d56-ffffffff82117d8a: domain_flush_pages.constprop.0.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6f65)
Location: drivers/iommu/amd_iommu.c:1297
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684955)
Location: drivers/iommu/amd_iommu.c:1297
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d51d5)
Location: drivers/iommu/amd_iommu.c:1297
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816efb15)
Location: drivers/iommu/amd_iommu.c:1297
Inline: True
```
</details>
</li>
</ul>

## Differences
