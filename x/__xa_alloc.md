# Function: <code>__xa_alloc</code>

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
int __xa_alloc(struct xarray *xa, u32 *id, u32 max, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a18f90)
Location: lib/xarray.c:1623
Inline: False
```
**Symbols:**

```
ffffffff81a18f90-ffffffff81a190ca: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a88bb0)
Location: lib/xarray.c:1601
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff81a88bb0-ffffffff81a88ce5: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abfe50)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff81abfe50-ffffffff81abff85: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fc450)
Location: lib/xarray.c:1614
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
**Symbols:**

```
ffffffff815fc450-ffffffff815fc585: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81621070)
Location: lib/xarray.c:1804
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
**Symbols:**

```
ffffffff81621070-ffffffff816211a5: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81604a50)
Location: lib/xarray.c:1805
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
**Symbols:**

```
ffffffff81604a50-ffffffff81604b88: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81673340)
Location: lib/xarray.c:1805
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
  - drivers/iommu/intel/svm.c:pasid_private_add
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
  - drivers/base/memory.c:memory_group_register
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
**Symbols:**

```
ffffffff81673340-ffffffff81673478: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178d970)
Location: lib/xarray.c:1812
Inline: False
Direct callers:
  - security/apparmor/secid.c:aa_alloc_secid
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
  - drivers/base/memory.c:memory_group_register
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
**Symbols:**

```
ffffffff8178d970-ffffffff8178dac0: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8204b010)
Location: lib/xarray.c:1812
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_insert_desc
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
  - drivers/base/memory.c:memory_group_register
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/opp/core.c:dev_pm_opp_set_config
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff8204b010-ffffffff8204b160: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c9910)
Location: lib/xarray.c:1810
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_insert_desc
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/base/memory.c:memory_group_register
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/opp/core.c:dev_pm_opp_set_config
  - net/devlink/leftover.c:devlink_region_snapshot_id_get
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff820c9910-ffffffff820c9a60: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a4290)
Location: lib/xarray.c:1813
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_insert_desc
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/base/memory.c:memory_group_register
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/opp/core.c:dev_pm_opp_set_config
  - net/devlink/region.c:devlink_region_snapshot_id_get
  - net/devlink/region.c:devlink_nl_region_new_doit
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff821a4290-ffffffff821a43e0: __xa_alloc (STB_GLOBAL)
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
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9b7f0)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffff800010d9b7f0-ffff800010d9b944: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97f14)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
c0e97f14-c0e980c8: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee1bb0)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
c000000000ee1bb0-c000000000ee1d94: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c3a3a)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffe0008c3a3a-ffffffe0008c3b36: __xa_alloc (STB_GLOBAL)
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
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5eca0)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff81a5eca0-ffffffff81a5edd5: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1bd70)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff81a1bd70-ffffffff81a1bea5: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acb090)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff81acb090-ffffffff81acb1c5: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __xa_alloc(struct xarray *xa, u32 *id, void *entry, struct xa_limit limit, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad76f0)
Location: lib/xarray.c:1612
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc_cyclic
  - lib/xarray.c:__xa_alloc_cyclic
```
**Symbols:**

```
ffffffff81ad76f0-ffffffff81ad7825: __xa_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xa_limit limit</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 max</code>
</li>
<li>
<b>Param reordered. </b>
<code>xa, id, max, entry, gfp</code> ➡️ <code>xa, id, entry, limit, gfp</code>
</li>
</ul>
</details>
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
