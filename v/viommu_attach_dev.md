# Function: <code>viommu_attach_dev</code>

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
int viommu_attach_dev(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:649
Inline: False
```
**Symbols:**

```
ffffffff8182e9f0-ffffffff8182ec95: viommu_attach_dev (STB_LOCAL)
ffffffff81d0217e-ffffffff81d021e6: viommu_attach_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int viommu_attach_dev(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:719
Inline: False
```
**Symbols:**

```
ffffffff8196fd90-ffffffff81970291: viommu_attach_dev (STB_LOCAL)
ffffffff81eca73c-ffffffff81eca7f7: viommu_attach_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int viommu_attach_dev(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:720
Inline: False
```
**Symbols:**

```
ffffffff81ada930-ffffffff81adae8b: viommu_attach_dev (STB_LOCAL)
ffffffff82098197-ffffffff8209820a: viommu_attach_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int viommu_attach_dev(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:720
Inline: False
```
**Symbols:**

```
ffffffff81b28be0-ffffffff81b2912f: viommu_attach_dev (STB_LOCAL)
ffffffff821191c3-ffffffff82119236: viommu_attach_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int viommu_attach_dev(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/virtio-iommu.c (0)
Location: drivers/iommu/virtio-iommu.c:720
Inline: False
```
**Symbols:**

```
ffffffff81b7fb80-ffffffff81b800d2: viommu_attach_dev (STB_LOCAL)
ffffffff821f7186-ffffffff821f71f9: viommu_attach_dev.cold (STB_LOCAL)
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
int viommu_attach_dev(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffff8000108dcd20)
Location: drivers/iommu/virtio-iommu.c:646
Inline: False
```
**Symbols:**

```
ffff8000108dcd20-ffff8000108dcfd0: viommu_attach_dev (STB_LOCAL)
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
