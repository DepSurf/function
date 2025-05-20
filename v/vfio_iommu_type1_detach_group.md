# Function: <code>vfio_iommu_type1_detach_group</code>

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
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3fc0)
Location: drivers/vfio/vfio_iommu_type1.c:1982
Inline: False
```
**Symbols:**

```
ffffffff817d3fc0-ffffffff817d4409: vfio_iommu_type1_detach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a0f00)
Location: drivers/vfio/vfio_iommu_type1.c:2342
Inline: False
```
**Symbols:**

```
ffffffff818a0f00-ffffffff818a13b3: vfio_iommu_type1_detach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818afce0)
Location: drivers/vfio/vfio_iommu_type1.c:2345
Inline: False
```
**Symbols:**

```
ffffffff818afce0-ffffffff818b01b9: vfio_iommu_type1_detach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892f80)
Location: drivers/vfio/vfio_iommu_type1.c:2558
Inline: False
```
**Symbols:**

```
ffffffff81892f80-ffffffff81893641: vfio_iommu_type1_detach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:2560
Inline: False
```
**Symbols:**

```
ffffffff81926aa0-ffffffff819271b7: vfio_iommu_type1_detach_group (STB_LOCAL)
ffffffff81d11c67-ffffffff81d11ce6: vfio_iommu_type1_detach_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:2556
Inline: False
```
**Symbols:**

```
ffffffff81a7cf40-ffffffff81a7d623: vfio_iommu_type1_detach_group (STB_LOCAL)
ffffffff81edc9b6-ffffffff81edca41: vfio_iommu_type1_detach_group.cold (STB_LOCAL)
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177e070)
Location: drivers/vfio/vfio_iommu_type1.c:1982
Inline: False
```
**Symbols:**

```
ffffffff8177e070-ffffffff8177e4b9: vfio_iommu_type1_detach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8e40)
Location: drivers/vfio/vfio_iommu_type1.c:1982
Inline: False
```
**Symbols:**

```
ffffffff817c8e40-ffffffff817c9289: vfio_iommu_type1_detach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_iommu_type1_detach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e30e0)
Location: drivers/vfio/vfio_iommu_type1.c:1982
Inline: False
```
**Symbols:**

```
ffffffff817e30e0-ffffffff817e3529: vfio_iommu_type1_detach_group (STB_LOCAL)
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
