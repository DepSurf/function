# Function: <code>vaddr_get_pfn</code>

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
int vaddr_get_pfn(struct mm_struct *mm, long unsigned int vaddr, int prot, long unsigned int *pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3190)
Location: drivers/vfio/vfio_iommu_type1.c:338
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817d3190-ffffffff817d33a4: vaddr_get_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vaddr_get_pfn(struct mm_struct *mm, long unsigned int vaddr, int prot, long unsigned int *pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e0a0)
Location: drivers/vfio/vfio_iommu_type1.c:444
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff8189e0a0-ffffffff8189e21d: vaddr_get_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vaddr_get_pfn(struct mm_struct *mm, long unsigned int vaddr, int prot, long unsigned int *pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad3d0)
Location: drivers/vfio/vfio_iommu_type1.c:467
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff818ad3d0-ffffffff818ad529: vaddr_get_pfn (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
int vaddr_get_pfn(struct mm_struct *mm, long unsigned int vaddr, int prot, long unsigned int *pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d240)
Location: drivers/vfio/vfio_iommu_type1.c:338
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff8177d240-ffffffff8177d454: vaddr_get_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vaddr_get_pfn(struct mm_struct *mm, long unsigned int vaddr, int prot, long unsigned int *pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8010)
Location: drivers/vfio/vfio_iommu_type1.c:338
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817c8010-ffffffff817c8224: vaddr_get_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vaddr_get_pfn(struct mm_struct *mm, long unsigned int vaddr, int prot, long unsigned int *pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e22b0)
Location: drivers/vfio/vfio_iommu_type1.c:338
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817e22b0-ffffffff817e24c4: vaddr_get_pfn (STB_LOCAL)
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
