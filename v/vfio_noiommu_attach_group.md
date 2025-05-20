# Function: <code>vfio_noiommu_attach_group</code>

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
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d01b0)
Location: drivers/vfio/vfio.c:196
Inline: False
```
**Symbols:**

```
ffffffff817d01b0-ffffffff817d01d6: vfio_noiommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189ad00)
Location: drivers/vfio/vfio.c:197
Inline: False
```
**Symbols:**

```
ffffffff8189ad00-ffffffff8189ad26: vfio_noiommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9910)
Location: drivers/vfio/vfio.c:197
Inline: False
```
**Symbols:**

```
ffffffff818a9910-ffffffff818a9936: vfio_noiommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188cce0)
Location: drivers/vfio/vfio.c:187
Inline: False
```
**Symbols:**

```
ffffffff8188cce0-ffffffff8188cd06: vfio_noiommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81920260)
Location: drivers/vfio/vfio.c:260
Inline: False
```
**Symbols:**

```
ffffffff81920260-ffffffff81920286: vfio_noiommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group, enum vfio_group_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a75810)
Location: drivers/vfio/vfio.c:189
Inline: False
```
**Symbols:**

```
ffffffff81a75810-ffffffff81a75821: vfio_noiommu_attach_group (STB_LOCAL)
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
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aadda0)
Location: drivers/vfio/vfio.c:196
Inline: False
```
**Symbols:**

```
c000000000aadda0-c000000000aaddf4: vfio_noiommu_attach_group (STB_LOCAL)
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
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a260)
Location: drivers/vfio/vfio.c:196
Inline: False
```
**Symbols:**

```
ffffffff8177a260-ffffffff8177a286: vfio_noiommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5030)
Location: drivers/vfio/vfio.c:196
Inline: False
```
**Symbols:**

```
ffffffff817c5030-ffffffff817c5056: vfio_noiommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_noiommu_attach_group(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df2d0)
Location: drivers/vfio/vfio.c:196
Inline: False
```
**Symbols:**

```
ffffffff817df2d0-ffffffff817df2f6: vfio_noiommu_attach_group (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum vfio_group_type type</code>
</li>
</ul>
</details>
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
