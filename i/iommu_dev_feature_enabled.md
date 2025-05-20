# Function: <code>iommu_dev_feature_enabled</code>

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
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b5b80)
Location: drivers/iommu/iommu.c:2313
Inline: False
```
**Symbols:**

```
ffffffff816b5b80-ffffffff816b5baf: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d8880)
Location: drivers/iommu/iommu.c:2391
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff816d8880-ffffffff816d88af: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178cff0)
Location: drivers/iommu/iommu.c:2694
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff8178cff0-ffffffff8178d01f: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b8a10)
Location: drivers/iommu/iommu.c:2917
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff817b8a10-ffffffff817b8a3f: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179bc70)
Location: drivers/iommu/iommu.c:2894
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff8179bc70-ffffffff8179bca8: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81824840)
Location: drivers/iommu/iommu.c:2979
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff81824840-ffffffff81824878: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81964710)
Location: drivers/iommu/iommu.c:2754
Inline: False
```
**Symbols:**

```
ffffffff81964710-ffffffff81964759: iommu_dev_feature_enabled (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c3f08)
Location: drivers/iommu/iommu.c:2391
Inline: False
```
**Symbols:**

```
ffff8000108c3f08-ffff8000108c3f68: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bb430)
Location: drivers/iommu/iommu.c:2391
Inline: False
```
**Symbols:**

```
c09bb430-c09bb470: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c000000000969b40)
Location: drivers/iommu/iommu.c:2391
Inline: False
```
**Symbols:**

```
c000000000969b40-c000000000969bac: iommu_dev_feature_enabled (STB_GLOBAL)
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
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e2d0)
Location: drivers/iommu/iommu.c:2391
Inline: False
```
**Symbols:**

```
ffffffff8169e2d0-ffffffff8169e2ff: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167bcc0)
Location: drivers/iommu/iommu.c:2391
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff8167bcc0-ffffffff8167bcef: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cc540)
Location: drivers/iommu/iommu.c:2391
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff816cc540-ffffffff816cc56f: iommu_dev_feature_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool iommu_dev_feature_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e6a10)
Location: drivers/iommu/iommu.c:2391
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff816e6a10-ffffffff816e6a3f: iommu_dev_feature_enabled (STB_GLOBAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
