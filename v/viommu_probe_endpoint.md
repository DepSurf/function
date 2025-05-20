# Function: <code>viommu_probe_endpoint</code>

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
int viommu_probe_endpoint(struct viommu_dev *viommu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:460
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff8182f160-ffffffff8182f342: viommu_probe_endpoint (STB_LOCAL)
ffffffff81d02293-ffffffff81d022e0: viommu_probe_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int viommu_probe_endpoint(struct viommu_dev *viommu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:513
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81970320-ffffffff81970504: viommu_probe_endpoint (STB_LOCAL)
ffffffff81eca7f7-ffffffff81eca87b: viommu_probe_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int viommu_probe_endpoint(struct viommu_dev *viommu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81adb0b0)
Location: drivers/iommu/virtio-iommu.c:514
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81adb0b0-ffffffff81adb30d: viommu_probe_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int viommu_probe_endpoint(struct viommu_dev *viommu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b29360)
Location: drivers/iommu/virtio-iommu.c:514
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81b29360-ffffffff81b295cc: viommu_probe_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int viommu_probe_endpoint(struct viommu_dev *viommu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b80340)
Location: drivers/iommu/virtio-iommu.c:514
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81b80340-ffffffff81b805ac: viommu_probe_endpoint (STB_LOCAL)
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
In drivers/iommu/virtio-iommu.c (ffff8000108dc8ac)
Location: drivers/iommu/virtio-iommu.c:461
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_add_device
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
