# Function: <code>unpin_user_pages</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287b30)
Location: mm/gup.c:327
Inline: True
Direct callers:
  - mm/frame_vector.c:put_vaddr_frames
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81287b30-ffffffff81287b66: unpin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291a30)
Location: mm/gup.c:293
Inline: True
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/frame_vector.c:put_vaddr_frames
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81291a30-ffffffff81291a89: unpin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unpin_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81296d50)
Location: mm/gup.c:404
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_pages_dirty_lock
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81296d50-ffffffff81296e5d: unpin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unpin_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d7700)
Location: mm/gup.c:416
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_pages_dirty_lock
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff812d7700-ffffffff812d780d: unpin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unpin_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813373d0)
Location: mm/gup.c:410
Inline: False
Direct callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_pages_dirty_lock
  - io_uring/io_uring.c:io_sqe_buffer_register
  - io_uring/io_uring.c:io_pin_pages
```
**Symbols:**

```
ffffffff813373d0-ffffffff81337508: unpin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unpin_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813ae790)
Location: mm/gup.c:425
Inline: False
Direct callers:
  - mm/gup.c:unpin_user_pages_dirty_lock
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
```
**Symbols:**

```
ffffffff813ae790-ffffffff813ae8c8: unpin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e3090)
Location: mm/gup.c:469
Inline: True
Direct callers:
  - mm/gup.c:unpin_user_pages_dirty_lock
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
```
**Symbols:**

```
ffffffff813e3090-ffffffff813e31c9: unpin_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_pages(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140d8c0)
Location: mm/gup.c:469
Inline: True
Direct callers:
  - mm/gup.c:unpin_user_pages_dirty_lock
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_for_each
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_for_each
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_alloc
```
**Symbols:**

```
ffffffff8140d8c0-ffffffff8140d9f3: unpin_user_pages (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
