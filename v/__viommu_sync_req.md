# Function: <code>__viommu_sync_req</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int __viommu_sync_req(struct viommu_dev *viommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8182e510)
Location: drivers/iommu/virtio-iommu.c:154
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffffffff8182e510-ffffffff8182e613: __viommu_sync_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __viommu_sync_req(struct viommu_dev *viommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8196f310)
Location: drivers/iommu/virtio-iommu.c:155
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffffffff8196f310-ffffffff8196f422: __viommu_sync_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __viommu_sync_req(struct viommu_dev *viommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81ada040)
Location: drivers/iommu/virtio-iommu.c:154
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffffffff81ada040-ffffffff81ada152: __viommu_sync_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __viommu_sync_req(struct viommu_dev *viommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b28170)
Location: drivers/iommu/virtio-iommu.c:154
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffffffff81b28170-ffffffff81b28282: __viommu_sync_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __viommu_sync_req(struct viommu_dev *viommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f030)
Location: drivers/iommu/virtio-iommu.c:154
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:viommu_sync_req
```
**Symbols:**

```
ffffffff81b7f030-ffffffff81b7f142: __viommu_sync_req (STB_LOCAL)
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
int __viommu_sync_req(struct viommu_dev *viommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffff8000108db7f8)
Location: drivers/iommu/virtio-iommu.c:154
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
```
**Symbols:**

```
ffff8000108db7f8-ffff8000108db918: __viommu_sync_req (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
