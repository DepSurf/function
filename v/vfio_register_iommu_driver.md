# Function: <code>vfio_register_iommu_driver</code>

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
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d02d0)
Location: drivers/vfio/vfio.c:222
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff817d02d0-ffffffff817d0391: vfio_register_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189b6d0)
Location: drivers/vfio/vfio.c:223
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff8189b6d0-ffffffff8189b792: vfio_register_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aa130)
Location: drivers/vfio/vfio.c:223
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff818aa130-ffffffff818aa1f2: vfio_register_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d680)
Location: drivers/vfio/vfio.c:213
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff8188d680-ffffffff8188d741: vfio_register_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81920be0)
Location: drivers/vfio/vfio.c:286
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff81920be0-ffffffff81920ca1: vfio_register_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a774c0)
Location: drivers/vfio/vfio.c:230
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff81a774c0-ffffffff81a77599: vfio_register_iommu_driver (STB_GLOBAL)
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
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab0e00)
Location: drivers/vfio/vfio.c:222
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_init
```
**Symbols:**

```
c000000000ab0e00-c000000000ab0f2c: vfio_register_iommu_driver (STB_GLOBAL)
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
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a380)
Location: drivers/vfio/vfio.c:222
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff8177a380-ffffffff8177a441: vfio_register_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5150)
Location: drivers/vfio/vfio.c:222
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff817c5150-ffffffff817c5211: vfio_register_iommu_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_register_iommu_driver(const struct vfio_iommu_driver_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df3f0)
Location: drivers/vfio/vfio.c:222
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_init
```
**Symbols:**

```
ffffffff817df3f0-ffffffff817df4b1: vfio_register_iommu_driver (STB_GLOBAL)
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
