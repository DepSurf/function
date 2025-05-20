# Function: <code>vfio_unregister_iommu_driver</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0230)
Location: drivers/vfio/vfio.c:251
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff817d0230-ffffffff817d02c5: vfio_unregister_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189ad80)
Location: drivers/vfio/vfio.c:252
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff8189ad80-ffffffff8189ae15: vfio_unregister_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9990)
Location: drivers/vfio/vfio.c:252
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff818a9990-ffffffff818a9a25: vfio_unregister_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188cd60)
Location: drivers/vfio/vfio.c:242
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff8188cd60-ffffffff8188cdf5: vfio_unregister_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff819201c0)
Location: drivers/vfio/vfio.c:315
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff819201c0-ffffffff81920255: vfio_unregister_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a76700)
Location: drivers/vfio/vfio.c:259
Inline: True
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff81a76700-ffffffff81a767a4: vfio_unregister_iommu_driver (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aae130)
Location: drivers/vfio/vfio.c:251
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_cleanup
```
**Symbols:**

```
c000000000aae130-c000000000aae25c: vfio_unregister_iommu_driver (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a2e0)
Location: drivers/vfio/vfio.c:251
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff8177a2e0-ffffffff8177a375: vfio_unregister_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c50b0)
Location: drivers/vfio/vfio.c:251
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff817c50b0-ffffffff817c5145: vfio_unregister_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_unregister_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df350)
Location: drivers/vfio/vfio.c:251
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_cleanup
```
**Symbols:**

```
ffffffff817df350-ffffffff817df3e5: vfio_unregister_iommu_driver (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
