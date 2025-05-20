# Function: <code>vma_is_fsdax</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81207a62)
Location: include/linux/fs.h:3214
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/frame_vector.c (ffffffff8126c926)
Location: include/linux/fs.h:3214
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81228620)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/frame_vector.c (ffffffff812914a9)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123be40)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/frame_vector.c (ffffffff812a64c9)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124d68e)
Location: include/linux/fs.h:3329
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffffffff812c1bc5)
Location: include/linux/fs.h:3329
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125bbbe)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffffffff812d3af5)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d321a)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a322)
Location: include/linux/fs.h:3441
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffffffff8130997e)
Location: include/linux/fs.h:3441
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812932d7)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/frame_vector.c (ffffffff8131579e)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
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
In mm/gup.c (ffffffff81298c6e)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff812d7313)
Location: include/linux/fs.h:3466
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
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
In mm/gup.c (ffffffff81336eb2)
Location: include/linux/fs.h:3244
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
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
In mm/gup.c (ffffffff813ae3c6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
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
In mm/gup.c (ffffffff813e282d)
Location: include/linux/fs.h:3001
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
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
In mm/gup.c (ffffffff8140d05d)
Location: include/linux/fs.h:3298
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f2fc4)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffff800010379a2c)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/fs.h:3391
Inline: True
```
```
In mm/frame_vector.c (0)
Location: include/linux/fs.h:3391
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b9940)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (c00000000046cc78)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe00020536a)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffffffe000250dd2)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125420e)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffffffff812cc0d5)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81246e5e)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffffffff812bcf45)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d2ca)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251fae)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffffffff812c9ee5)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c809a)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8126195e)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/frame_vector.c (ffffffff812dabe5)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e233a)
Location: include/linux/fs.h:3391
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
</details>
</li>
</ul>

## Differences
