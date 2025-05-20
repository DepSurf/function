# Function: <code>viommu_iotlb_sync</code>

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
void viommu_iotlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8182ef20)
Location: drivers/iommu/virtio-iommu.c:803
Inline: False
```
**Symbols:**

```
ffffffff8182ef20-ffffffff8182ef7c: viommu_iotlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void viommu_iotlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8196fb40)
Location: drivers/iommu/virtio-iommu.c:877
Inline: False
```
**Symbols:**

```
ffffffff8196fb40-ffffffff8196fbac: viommu_iotlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void viommu_iotlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81ada7f0)
Location: drivers/iommu/virtio-iommu.c:883
Inline: False
```
**Symbols:**

```
ffffffff81ada7f0-ffffffff81ada85c: viommu_iotlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void viommu_iotlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b28aa0)
Location: drivers/iommu/virtio-iommu.c:907
Inline: False
```
**Symbols:**

```
ffffffff81b28aa0-ffffffff81b28b0c: viommu_iotlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void viommu_iotlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f1e0)
Location: drivers/iommu/virtio-iommu.c:907
Inline: False
```
**Symbols:**

```
ffffffff81b7f1e0-ffffffff81b7f1fc: viommu_iotlb_sync (STB_LOCAL)
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
void viommu_iotlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffff8000108dbd78)
Location: drivers/iommu/virtio-iommu.c:800
Inline: False
```
**Symbols:**

```
ffff8000108dbd78-ffff8000108dbe48: viommu_iotlb_sync (STB_LOCAL)
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
