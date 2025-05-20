# Function: <code>unpin_user_pages_dirty_lock</code>

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
void unpin_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287c30)
Location: mm/gup.c:273
Inline: True
Direct callers:
  - mm/process_vm_access.c:process_vm_rw_single_vec
  - mm/process_vm_access.c:process_vm_rw_single_vec
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81287c30-ffffffff81287cba: unpin_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291a90)
Location: mm/gup.c:239
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81291a90-ffffffff81291b1f: unpin_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unpin_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81297140)
Location: mm/gup.c:319
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81297140-ffffffff81297285: unpin_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unpin_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d7af0)
Location: mm/gup.c:331
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff812d7af0-ffffffff812d7c35: unpin_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unpin_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813376d0)
Location: mm/gup.c:299
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff813376d0-ffffffff8133787f: unpin_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unpin_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813aedc0)
Location: mm/gup.c:314
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff813aedc0-ffffffff813aef6f: unpin_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unpin_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e3390)
Location: mm/gup.c:358
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff813e3390-ffffffff813e3544: unpin_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unpin_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140dbc0)
Location: mm/gup.c:358
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff8140dbc0-ffffffff8140dd6e: unpin_user_pages_dirty_lock (STB_GLOBAL)
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
