# Function: <code>iommu_detach_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152ad50)
Location: drivers/iommu/iommu.c:1143
Inline: False
```
**Symbols:**

```
ffffffff8152ad50-ffffffff8152ade3: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157e160)
Location: drivers/iommu/iommu.c:1133
Inline: False
```
**Symbols:**

```
ffffffff8157e160-ffffffff8157e1f3: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aa700)
Location: drivers/iommu/iommu.c:1284
Inline: False
```
**Symbols:**

```
ffffffff815aa700-ffffffff815aa793: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c0a90)
Location: drivers/iommu/iommu.c:1334
Inline: False
```
**Symbols:**

```
ffffffff815c0a90-ffffffff815c0b14: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627230)
Location: drivers/iommu/iommu.c:1339
Inline: False
```
**Symbols:**

```
ffffffff81627230-ffffffff816272ad: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81661730)
Location: drivers/iommu/iommu.c:1343
Inline: False
```
**Symbols:**

```
ffffffff81661730-ffffffff816617a8: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167f800)
Location: drivers/iommu/iommu.c:1410
Inline: False
```
**Symbols:**

```
ffffffff8167f800-ffffffff8167f878: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1627
Inline: False
```
**Symbols:**

```
ffffffff816b8a06-ffffffff816b8a19: iommu_detach_device.cold (STB_LOCAL)
ffffffff816b7c10-ffffffff816b7c8c: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816da970)
Location: drivers/iommu/iommu.c:1683
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff816da970-ffffffff816da9e8: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178ec50)
Location: drivers/iommu/iommu.c:1996
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
**Symbols:**

```
ffffffff8178ec50-ffffffff8178ecc8: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bae60)
Location: drivers/iommu/iommu.c:2206
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
**Symbols:**

```
ffffffff817bae60-ffffffff817baed8: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179e5a0)
Location: drivers/iommu/iommu.c:2237
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
**Symbols:**

```
ffffffff8179e5a0-ffffffff8179e618: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81827610)
Location: drivers/iommu/iommu.c:2258
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
**Symbols:**

```
ffffffff81827610-ffffffff81827688: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81967620)
Location: drivers/iommu/iommu.c:2021
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
**Symbols:**

```
ffffffff81967620-ffffffff819676db: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad0a30)
Location: drivers/iommu/iommu.c:2059
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81ad0a30-ffffffff81ad0aeb: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1e970)
Location: drivers/iommu/iommu.c:2037
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81b1e970-ffffffff81b1ea26: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b76b10)
Location: drivers/iommu/iommu.c:2302
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81b76b10-ffffffff81b76c23: iommu_detach_device (STB_GLOBAL)
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
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c5c88)
Location: drivers/iommu/iommu.c:1683
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffff8000108c5c88-ffff8000108c5d24: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd7f0)
Location: drivers/iommu/iommu.c:1683
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
c09bd7f0-c09bd890: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096c730)
Location: drivers/iommu/iommu.c:1683
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
c00000000096c730-c00000000096c810: iommu_detach_device (STB_GLOBAL)
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
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a03c0)
Location: drivers/iommu/iommu.c:1683
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff816a03c0-ffffffff816a0438: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167ddb0)
Location: drivers/iommu/iommu.c:1683
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff8167ddb0-ffffffff8167de28: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ce630)
Location: drivers/iommu/iommu.c:1683
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
```
**Symbols:**

```
ffffffff816ce630-ffffffff816ce6a8: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8b90)
Location: drivers/iommu/iommu.c:1683
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff816e8b90-ffffffff816e8c08: iommu_detach_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
