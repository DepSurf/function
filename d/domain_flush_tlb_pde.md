# Function: <code>domain_flush_tlb_pde</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152fafc)
Location: drivers/iommu/amd_iommu.c:1083
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff81583343)
Location: drivers/iommu/amd_iommu.c:1179
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff815b0653)
Location: drivers/iommu/amd_iommu.c:1268
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff815c584b)
Location: drivers/iommu/amd_iommu.c:1327
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff8162c41b)
Location: drivers/iommu/amd_iommu.c:1268
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff8166779f)
Location: drivers/iommu/amd_iommu.c:1274
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff816869bf)
Location: drivers/iommu/amd_iommu.c:1289
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd_iommu.c (ffffffff816be220)
Location: drivers/iommu/amd_iommu.c:1288
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd_iommu.c (ffffffff816e1616)
Location: drivers/iommu/amd_iommu.c:1310
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd/iommu.c (ffffffff81796d76)
Location: drivers/iommu/amd/iommu.c:1248
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_map_page
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
In drivers/iommu/amd/iommu.c (ffffffff817a54a6)
Location: drivers/iommu/amd/iommu.c:1338
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_map_page
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a7066)
Location: drivers/iommu/amd_iommu.c:1310
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd_iommu.c (ffffffff81684a56)
Location: drivers/iommu/amd_iommu.c:1310
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd_iommu.c (ffffffff816d52d6)
Location: drivers/iommu/amd_iommu.c:1310
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd_iommu.c (ffffffff816efc16)
Location: drivers/iommu/amd_iommu.c:1310
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
```
</details>
</li>
</ul>

## Differences
