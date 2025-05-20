# Function: <code>vfio_iommu_type1_pin_pages</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:541
Inline: False
```
**Symbols:**

```
ffffffff817d4410-ffffffff817d47f4: vfio_iommu_type1_pin_pages (STB_LOCAL)
ffffffff817d5ddf-ffffffff817d5e26: vfio_iommu_type1_pin_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, struct iommu_group *iommu_group, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a0920)
Location: drivers/vfio/vfio_iommu_type1.c:631
Inline: False
```
**Symbols:**

```
ffffffff818a0920-ffffffff818a0d5c: vfio_iommu_type1_pin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, struct iommu_group *iommu_group, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818b08d0)
Location: drivers/vfio/vfio_iommu_type1.c:654
Inline: False
```
**Symbols:**

```
ffffffff818b08d0-ffffffff818b0d4c: vfio_iommu_type1_pin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, struct iommu_group *iommu_group, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:832
Inline: False
```
**Symbols:**

```
ffffffff818917a0-ffffffff81891d72: vfio_iommu_type1_pin_pages (STB_LOCAL)
ffffffff81c0be0c-ffffffff81c0be59: vfio_iommu_type1_pin_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, struct iommu_group *iommu_group, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:833
Inline: False
```
**Symbols:**

```
ffffffff819259c0-ffffffff81925f95: vfio_iommu_type1_pin_pages (STB_LOCAL)
ffffffff81d11b0b-ffffffff81d11bbf: vfio_iommu_type1_pin_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, struct iommu_group *iommu_group, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:831
Inline: False
```
**Symbols:**

```
ffffffff81a7c450-ffffffff81a7ca9a: vfio_iommu_type1_pin_pages (STB_LOCAL)
ffffffff81edc886-ffffffff81edc93b: vfio_iommu_type1_pin_pages.cold (STB_LOCAL)
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:541
Inline: False
```
**Symbols:**

```
ffffffff8177e4c0-ffffffff8177e8a4: vfio_iommu_type1_pin_pages (STB_LOCAL)
ffffffff8177fe8f-ffffffff8177fed6: vfio_iommu_type1_pin_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:541
Inline: False
```
**Symbols:**

```
ffffffff817c9290-ffffffff817c9674: vfio_iommu_type1_pin_pages (STB_LOCAL)
ffffffff817cac5f-ffffffff817caca6: vfio_iommu_type1_pin_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_pin_pages(void *iommu_data, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:541
Inline: False
```
**Symbols:**

```
ffffffff817e3530-ffffffff817e3914: vfio_iommu_type1_pin_pages (STB_LOCAL)
ffffffff817e4eff-ffffffff817e4f46: vfio_iommu_type1_pin_pages.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_group *iommu_group</code>
</li>
<li>
<b>Param reordered. </b>
<code>iommu_data, user_pfn, npage, prot, phys_pfn</code> ➡️ <code>iommu_data, iommu_group, user_pfn, npage, prot, phys_pfn</code>
</li>
</ul>
</details>
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
