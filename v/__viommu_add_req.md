# Function: <code>__viommu_add_req</code>

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
int __viommu_add_req(struct viommu_dev *viommu, void *buf, size_t len, bool writeback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8182e620)
Location: drivers/iommu/virtio-iommu.c:217
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
```
**Symbols:**

```
ffffffff8182e620-ffffffff8182e7eb: __viommu_add_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __viommu_add_req(struct viommu_dev *viommu, void *buf, size_t len, bool writeback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8196f430)
Location: drivers/iommu/virtio-iommu.c:218
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
```
**Symbols:**

```
ffffffff8196f430-ffffffff8196f650: __viommu_add_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __viommu_add_req(struct viommu_dev *viommu, void *buf, size_t len, bool writeback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81ada170)
Location: drivers/iommu/virtio-iommu.c:217
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap_pages
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
```
**Symbols:**

```
ffffffff81ada170-ffffffff81ada390: __viommu_add_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __viommu_add_req(struct viommu_dev *viommu, void *buf, size_t len, bool writeback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:217
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap_pages
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
```
**Symbols:**

```
ffffffff81b282a0-ffffffff81b28520: __viommu_add_req (STB_LOCAL)
ffffffff82119194-ffffffff821191c3: __viommu_add_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __viommu_add_req(struct viommu_dev *viommu, void *buf, size_t len, bool writeback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f210)
Location: drivers/iommu/virtio-iommu.c:217
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/iommu/virtio-iommu.c:viommu_add_req
```
**Symbols:**

```
ffffffff81b7f210-ffffffff81b7f43e: __viommu_add_req (STB_LOCAL)
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
int __viommu_add_req(struct viommu_dev *viommu, void *buf, size_t len, bool writeback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffff8000108dbbc8)
Location: drivers/iommu/virtio-iommu.c:218
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
```
**Symbols:**

```
ffff8000108dbbc8-ffff8000108dbd74: __viommu_add_req (STB_LOCAL)
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
