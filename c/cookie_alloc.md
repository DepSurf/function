# Function: <code>cookie_alloc</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817920d5)
Location: drivers/iommu/dma-iommu.c:60
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817be835)
Location: drivers/iommu/dma-iommu.c:82
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a1cf5)
Location: drivers/iommu/dma-iommu.c:86
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182a275)
Location: drivers/iommu/dma-iommu.c:86
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
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
In drivers/iommu/dma-iommu.c (ffffffff8196a785)
Location: drivers/iommu/dma-iommu.c:288
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad4b05)
Location: drivers/iommu/dma-iommu.c:291
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b232d5)
Location: drivers/iommu/dma-iommu.c:292
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b79c5b)
Location: drivers/iommu/dma-iommu.c:373
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
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
struct iommu_dma_cookie *cookie_alloc(enum iommu_dma_cookie_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c8a80)
Location: drivers/iommu/dma-iommu.c:59
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
```
**Symbols:**

```
ffff8000108c8a80-ffff8000108c8acc: cookie_alloc (STB_LOCAL)
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
