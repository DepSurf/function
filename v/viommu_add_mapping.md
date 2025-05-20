# Function: <code>viommu_add_mapping</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8182f059)
Location: drivers/iommu/virtio-iommu.c:313
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int viommu_add_mapping(struct viommu_domain *vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8196fbb0)
Location: drivers/iommu/virtio-iommu.c:314
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_map
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
**Symbols:**

```
ffffffff8196fbb0-ffffffff8196fc58: viommu_add_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int viommu_add_mapping(struct viommu_domain *vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81ada870)
Location: drivers/iommu/virtio-iommu.c:313
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_map_pages
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
**Symbols:**

```
ffffffff81ada870-ffffffff81ada91b: viommu_add_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int viommu_add_mapping(struct viommu_domain *vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b28b20)
Location: drivers/iommu/virtio-iommu.c:313
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_map_pages
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
**Symbols:**

```
ffffffff81b28b20-ffffffff81b28bcb: viommu_add_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int viommu_add_mapping(struct viommu_domain *vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b7fa90)
Location: drivers/iommu/virtio-iommu.c:313
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_map_pages
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
**Symbols:**

```
ffffffff81b7fa90-ffffffff81b7fb6a: viommu_add_mapping (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffff8000108dcbc0)
Location: drivers/iommu/virtio-iommu.c:314
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_map
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
