# Function: <code>vfio_info_cap_add</code>

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
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0830)
Location: drivers/vfio/vfio.c:1817
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
**Symbols:**

```
ffffffff817d0830-ffffffff817d08d9: vfio_info_cap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189b270)
Location: drivers/vfio/vfio.c:1837
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
**Symbols:**

```
ffffffff8189b270-ffffffff8189b319: vfio_info_cap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9e80)
Location: drivers/vfio/vfio.c:1838
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
**Symbols:**

```
ffffffff818a9e80-ffffffff818a9f2b: vfio_info_cap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d220)
Location: drivers/vfio/vfio.c:1737
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
```
**Symbols:**

```
ffffffff8188d220-ffffffff8188d2c8: vfio_info_cap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81920350)
Location: drivers/vfio/vfio.c:1844
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
```
**Symbols:**

```
ffffffff81920350-ffffffff819203f8: vfio_info_cap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a76390)
Location: drivers/vfio/vfio.c:1808
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
**Symbols:**

```
ffffffff81a76390-ffffffff81a76442: vfio_info_cap_add (STB_GLOBAL)
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
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aafc50)
Location: drivers/vfio/vfio.c:1817
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
```
**Symbols:**

```
c000000000aafc50-c000000000aafd78: vfio_info_cap_add (STB_GLOBAL)
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
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a8e0)
Location: drivers/vfio/vfio.c:1817
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
**Symbols:**

```
ffffffff8177a8e0-ffffffff8177a989: vfio_info_cap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c56b0)
Location: drivers/vfio/vfio.c:1817
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
**Symbols:**

```
ffffffff817c56b0-ffffffff817c5759: vfio_info_cap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfio_info_cap_header *vfio_info_cap_add(struct vfio_info_cap *caps, size_t size, u16 id, u16 version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df950)
Location: drivers/vfio/vfio.c:1817
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_info_add_capability
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps
```
**Symbols:**

```
ffffffff817df950-ffffffff817df9f9: vfio_info_cap_add (STB_GLOBAL)
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
