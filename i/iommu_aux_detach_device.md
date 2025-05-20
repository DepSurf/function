# Function: <code>iommu_aux_detach_device</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b6c00)
Location: drivers/iommu/iommu.c:2348
Inline: False
```
**Symbols:**

```
ffffffff816b6c00-ffffffff816b6c6e: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9790)
Location: drivers/iommu/iommu.c:2426
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff816d9790-ffffffff816d97fe: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178e540)
Location: drivers/iommu/iommu.c:2729
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff8178e540-ffffffff8178e5ae: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817ba710)
Location: drivers/iommu/iommu.c:2952
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff817ba710-ffffffff817ba770: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179d560)
Location: drivers/iommu/iommu.c:2931
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff8179d560-ffffffff8179d5c0: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818262b0)
Location: drivers/iommu/iommu.c:3016
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff818262b0-ffffffff8182630d: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c5520)
Location: drivers/iommu/iommu.c:2426
Inline: False
```
**Symbols:**

```
ffff8000108c5520-ffff8000108c55d0: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bc368)
Location: drivers/iommu/iommu.c:2426
Inline: False
```
**Symbols:**

```
c09bc368-c09bc410: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096b030)
Location: drivers/iommu/iommu.c:2426
Inline: False
```
**Symbols:**

```
c00000000096b030-c00000000096b10c: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169f1e0)
Location: drivers/iommu/iommu.c:2426
Inline: False
```
**Symbols:**

```
ffffffff8169f1e0-ffffffff8169f24e: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167cbd0)
Location: drivers/iommu/iommu.c:2426
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff8167cbd0-ffffffff8167cc3e: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cd450)
Location: drivers/iommu/iommu.c:2426
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff816cd450-ffffffff816cd4be: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e7950)
Location: drivers/iommu/iommu.c:2426
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff816e7950-ffffffff816e79d0: iommu_aux_detach_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
