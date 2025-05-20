# Function: <code>vfio_lock_acct</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d43c9)
Location: drivers/vfio/vfio_iommu_type1.c:268
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817d33b0-ffffffff817d3461: vfio_lock_acct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189ecf9)
Location: drivers/vfio/vfio_iommu_type1.c:367
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff8189e2a0-ffffffff8189e351: vfio_lock_acct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818adef9)
Location: drivers/vfio/vfio_iommu_type1.c:380
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff818ad2b0-ffffffff818ad3c2: vfio_lock_acct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189359e)
Location: drivers/vfio/vfio_iommu_type1.c:418
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff81890350-ffffffff81890456: vfio_lock_acct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192713f)
Location: drivers/vfio/vfio_iommu_type1.c:419
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff81924040-ffffffff8192415e: vfio_lock_acct.part.0 (STB_LOCAL)
ffffffff81d118f5-ffffffff81d11913: vfio_lock_acct.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7d5b0)
Location: drivers/vfio/vfio_iommu_type1.c:417
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff81a79a70-ffffffff81a79b85: vfio_lock_acct.part.0 (STB_LOCAL)
ffffffff81edc56d-ffffffff81edc58b: vfio_lock_acct.part.0.cold (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177e479)
Location: drivers/vfio/vfio_iommu_type1.c:268
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff8177d460-ffffffff8177d511: vfio_lock_acct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c9249)
Location: drivers/vfio/vfio_iommu_type1.c:268
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817c8230-ffffffff817c82e1: vfio_lock_acct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e34e9)
Location: drivers/vfio/vfio_iommu_type1.c:268
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
```
**Symbols:**

```
ffffffff817e24d0-ffffffff817e2581: vfio_lock_acct.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
