# Function: <code>put_pfn</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int put_pfn(long unsigned int pfn, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3720)
Location: drivers/vfio/vfio_iommu_type1.c:326
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817d3720-ffffffff817d37d0: put_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int put_pfn(long unsigned int pfn, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a08ce)
Location: drivers/vfio/vfio_iommu_type1.c:407
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff8189e220-ffffffff8189e29d: put_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int put_pfn(long unsigned int pfn, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818b0cab)
Location: drivers/vfio/vfio_iommu_type1.c:420
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff818acee0-ffffffff818acf5d: put_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int put_pfn(long unsigned int pfn, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890908)
Location: drivers/vfio/vfio_iommu_type1.c:458
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff81891080-ffffffff81891101: put_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int put_pfn(long unsigned int pfn, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819243e8)
Location: drivers/vfio/vfio_iommu_type1.c:459
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff81924b90-ffffffff81924c11: put_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7c8de)
Location: drivers/vfio/vfio_iommu_type1.c:457
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int put_pfn(long unsigned int pfn, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d7d0)
Location: drivers/vfio/vfio_iommu_type1.c:326
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff8177d7d0-ffffffff8177d880: put_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int put_pfn(long unsigned int pfn, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c85a0)
Location: drivers/vfio/vfio_iommu_type1.c:326
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817c85a0-ffffffff817c8650: put_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int put_pfn(long unsigned int pfn, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2840)
Location: drivers/vfio/vfio_iommu_type1.c:326
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817e2840-ffffffff817e28f0: put_pfn (STB_LOCAL)
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
