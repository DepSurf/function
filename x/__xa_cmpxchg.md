# Function: <code>__xa_cmpxchg</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a18c50)
Location: lib/xarray.c:1416
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffffffff81a18c50-ffffffff81a18d8c: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a88960)
Location: lib/xarray.c:1434
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffffffff81a88960-ffffffff81a88a9a: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abfc00)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffffffff81abfc00-ffffffff81abfd3a: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fc200)
Location: lib/xarray.c:1447
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff815fc200-ffffffff815fc335: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620e20)
Location: lib/xarray.c:1597
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81620e20-ffffffff81620f55: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81604800)
Location: lib/xarray.c:1598
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81604800-ffffffff81604935: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816730f0)
Location: lib/xarray.c:1598
Inline: False
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - drivers/vfio/vfio.c:vfio_assign_device_set
```
**Symbols:**

```
ffffffff816730f0-ffffffff81673229: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178d6f0)
Location: lib/xarray.c:1605
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - drivers/vfio/vfio.c:vfio_assign_device_set
```
**Symbols:**

```
ffffffff8178d6f0-ffffffff8178d834: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8204ad70)
Location: lib/xarray.c:1605
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
**Symbols:**

```
ffffffff8204ad70-ffffffff8204aeb4: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c9670)
Location: lib/xarray.c:1603
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
**Symbols:**

```
ffffffff820c9670-ffffffff820c97b4: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3ff0)
Location: lib/xarray.c:1603
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - net/netlink/genetlink.c:genl_sk_priv_get
```
**Symbols:**

```
ffffffff821a3ff0-ffffffff821a4134: __xa_cmpxchg (STB_GLOBAL)
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
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9b580)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffff800010d9b580-ffff800010d9b6c8: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97c3c)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
c0e97c3c-c0e97dc0: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee1850)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
c000000000ee1850-c000000000ee1a08: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c3862)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffffffe0008c3862-ffffffe0008c3942: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5ea50)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffffffff81a5ea50-ffffffff81a5eb8a: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1bb20)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffffffff81a1bb20-ffffffff81a1bc5a: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acae40)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffffffff81acae40-ffffffff81acaf7a: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__xa_cmpxchg(struct xarray *xa, long unsigned int index, void *old, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad74a0)
Location: lib/xarray.c:1445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
```
**Symbols:**

```
ffffffff81ad74a0-ffffffff81ad75da: __xa_cmpxchg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
