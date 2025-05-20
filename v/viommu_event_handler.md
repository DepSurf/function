# Function: <code>viommu_event_handler</code>

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
void viommu_event_handler(struct virtqueue *vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:558
Inline: False
```
**Symbols:**

```
ffffffff8182ede0-ffffffff8182ef1a: viommu_event_handler (STB_LOCAL)
ffffffff81d021e6-ffffffff81d02293: viommu_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void viommu_event_handler(struct virtqueue *vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:611
Inline: False
```
**Symbols:**

```
ffffffff8196f9d0-ffffffff8196fb3f: viommu_event_handler (STB_LOCAL)
ffffffff81eca68f-ffffffff81eca73c: viommu_event_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void viommu_event_handler(struct virtqueue *vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81ada5e0)
Location: drivers/iommu/virtio-iommu.c:612
Inline: False
```
**Symbols:**

```
ffffffff81ada5e0-ffffffff81ada7dc: viommu_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void viommu_event_handler(struct virtqueue *vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b28890)
Location: drivers/iommu/virtio-iommu.c:612
Inline: False
```
**Symbols:**

```
ffffffff81b28890-ffffffff81b28a8c: viommu_event_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void viommu_event_handler(struct virtqueue *vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f880)
Location: drivers/iommu/virtio-iommu.c:612
Inline: False
```
**Symbols:**

```
ffffffff81b7f880-ffffffff81b7fa7c: viommu_event_handler (STB_LOCAL)
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
void viommu_event_handler(struct virtqueue *vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffff8000108db9d0)
Location: drivers/iommu/virtio-iommu.c:559
Inline: False
```
**Symbols:**

```
ffff8000108db9d0-ffff8000108dbbc8: viommu_event_handler (STB_LOCAL)
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
