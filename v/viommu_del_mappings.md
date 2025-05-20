# Function: <code>viommu_del_mappings</code>

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
size_t viommu_del_mappings(struct viommu_domain *vdomain, long unsigned int iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8182e930)
Location: drivers/iommu/virtio-iommu.c:345
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_map
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
```
**Symbols:**

```
ffffffff8182e930-ffffffff8182e9ec: viommu_del_mappings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t viommu_del_mappings(struct viommu_domain *vdomain, u64 iova, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8196f1e0)
Location: drivers/iommu/virtio-iommu.c:345
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_map
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
```
**Symbols:**

```
ffffffff8196f1e0-ffffffff8196f2b2: viommu_del_mappings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t viommu_del_mappings(struct viommu_domain *vdomain, u64 iova, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81ad9cc0)
Location: drivers/iommu/virtio-iommu.c:344
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap_pages
  - drivers/iommu/virtio-iommu.c:viommu_map_pages
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
```
**Symbols:**

```
ffffffff81ad9cc0-ffffffff81ad9d95: viommu_del_mappings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t viommu_del_mappings(struct viommu_domain *vdomain, u64 iova, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b27e40)
Location: drivers/iommu/virtio-iommu.c:344
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap_pages
  - drivers/iommu/virtio-iommu.c:viommu_map_pages
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
```
**Symbols:**

```
ffffffff81b27e40-ffffffff81b27f15: viommu_del_mappings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t viommu_del_mappings(struct viommu_domain *vdomain, u64 iova, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b7ed00)
Location: drivers/iommu/virtio-iommu.c:344
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap_pages
  - drivers/iommu/virtio-iommu.c:viommu_map_pages
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
```
**Symbols:**

```
ffffffff81b7ed00-ffffffff81b7edd5: viommu_del_mappings (STB_LOCAL)
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
size_t viommu_del_mappings(struct viommu_domain *vdomain, long unsigned int iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffff8000108dc4f8)
Location: drivers/iommu/virtio-iommu.c:346
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_map
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
```
**Symbols:**

```
ffff8000108dc4f8-ffff8000108dc634: viommu_del_mappings (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 end</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int iova</code> ➡️ <code>u64 iova</code>
</li>
</ul>
</details>
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
