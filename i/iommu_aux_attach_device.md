# Function: <code>iommu_aux_attach_device</code>

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
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b7c90)
Location: drivers/iommu/iommu.c:2334
Inline: False
```
**Symbols:**

```
ffffffff816b7c90-ffffffff816b7d24: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816da9f0)
Location: drivers/iommu/iommu.c:2412
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff816da9f0-ffffffff816daa84: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178e770)
Location: drivers/iommu/iommu.c:2715
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff8178e770-ffffffff8178e804: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817ba8a0)
Location: drivers/iommu/iommu.c:2938
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff817ba8a0-ffffffff817ba91f: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179e0b0)
Location: drivers/iommu/iommu.c:2917
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff8179e0b0-ffffffff8179e12f: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81827370)
Location: drivers/iommu/iommu.c:3002
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff81827370-ffffffff818273ec: iommu_aux_attach_device (STB_GLOBAL)
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
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c55d0)
Location: drivers/iommu/iommu.c:2412
Inline: False
```
**Symbols:**

```
ffff8000108c55d0-ffff8000108c56b8: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd890)
Location: drivers/iommu/iommu.c:2412
Inline: False
```
**Symbols:**

```
c09bd890-c09bd950: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096c810)
Location: drivers/iommu/iommu.c:2412
Inline: False
```
**Symbols:**

```
c00000000096c810-c00000000096c94c: iommu_aux_attach_device (STB_GLOBAL)
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
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a0440)
Location: drivers/iommu/iommu.c:2412
Inline: False
```
**Symbols:**

```
ffffffff816a0440-ffffffff816a04d4: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167de30)
Location: drivers/iommu/iommu.c:2412
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff8167de30-ffffffff8167dec4: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ce6b0)
Location: drivers/iommu/iommu.c:2412
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff816ce6b0-ffffffff816ce744: iommu_aux_attach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8c10)
Location: drivers/iommu/iommu.c:2412
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff816e8c10-ffffffff816e8cb1: iommu_aux_attach_device (STB_GLOBAL)
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
