# Function: <code>iommu_unmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152a750)
Location: drivers/iommu/iommu.c:1367
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:default_iommu_map_sg
```
**Symbols:**

```
ffffffff8152a750-ffffffff8152a8f5: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157db90)
Location: drivers/iommu/iommu.c:1358
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff8157db90-ffffffff8157dd10: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aa130)
Location: drivers/iommu/iommu.c:1509
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff815aa130-ffffffff815aa2b0: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bfdc0)
Location: drivers/iommu/iommu.c:1559
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff815bfdc0-ffffffff815bff42: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816268cb)
Location: drivers/iommu/iommu.c:1620
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816265c0-ffffffff816265d5: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816614eb)
Location: drivers/iommu/iommu.c:1626
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816611f0-ffffffff81661205: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167fda7)
Location: drivers/iommu/iommu.c:1702
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff8167fab0-ffffffff8167fac5: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b71ca)
Location: drivers/iommu/iommu.c:1923
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816b6ea0-ffffffff816b6eb5: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d99f0)
Location: drivers/iommu/iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff816d99f0-ffffffff816d9a72: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178e980)
Location: drivers/iommu/iommu.c:2300
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff8178e980-ffffffff8178ea02: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817babb0)
Location: drivers/iommu/iommu.c:2520
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff817babb0-ffffffff817bac3a: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179d4c0)
Location: drivers/iommu/iommu.c:2551
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff8179d4c0-ffffffff8179d54a: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81826200)
Location: drivers/iommu/iommu.c:2637
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81826200-ffffffff81826292: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819664e0)
Location: drivers/iommu/iommu.c:2414
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff819664e0-ffffffff8196657f: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acfea0)
Location: drivers/iommu/iommu.c:2478
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81acfea0-ffffffff81acff3f: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1f150)
Location: drivers/iommu/iommu.c:2490
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81b1f150-ffffffff81b1f1ef: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b75590)
Location: drivers/iommu/iommu.c:2754
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81b75590-ffffffff81b7562f: iommu_unmap (STB_GLOBAL)
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
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c58c0)
Location: drivers/iommu/iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffff8000108c58c0-ffff8000108c595c: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bc68c)
Location: drivers/iommu/iommu.c:1973
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_remove_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
c09bc68c-c09bc720: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096b430)
Location: drivers/iommu/iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
c00000000096b430-c00000000096b4e8: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169f440)
Location: drivers/iommu/iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff8169f440-ffffffff8169f4c2: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167ce30)
Location: drivers/iommu/iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8167ce30-ffffffff8167ceb2: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cd6b0)
Location: drivers/iommu/iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff816cd6b0-ffffffff816cd732: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e7be0)
Location: drivers/iommu/iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff816e7be0-ffffffff816e7c62: iommu_unmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
