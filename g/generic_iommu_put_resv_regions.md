# Function: <code>generic_iommu_put_resv_regions</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void generic_iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178d1a0)
Location: drivers/iommu/iommu.c:2526
Inline: False
```
**Symbols:**

```
ffffffff8178d1a0-ffffffff8178d1cf: generic_iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void generic_iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b8b60)
Location: drivers/iommu/iommu.c:2749
Inline: False
```
**Symbols:**

```
ffffffff817b8b60-ffffffff817b8b8f: generic_iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void generic_iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179bd70)
Location: drivers/iommu/iommu.c:2735
Inline: False
```
**Symbols:**

```
ffffffff8179bd70-ffffffff8179bd9f: generic_iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void generic_iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81824940)
Location: drivers/iommu/iommu.c:2820
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81824940-ffffffff8182496f: generic_iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void generic_iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819648c0)
Location: drivers/iommu/iommu.c:2597
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff819648c0-ffffffff819648f7: generic_iommu_put_resv_regions (STB_GLOBAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
