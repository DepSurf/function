# Function: <code>iommu_put_resv_regions</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aad21)
Location: drivers/iommu/iommu.c:1707
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff815ab8d0-ffffffff815ab8fa: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c08b6)
Location: drivers/iommu/iommu.c:1799
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff815c15a0-ffffffff815c15cb: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81626f9e)
Location: drivers/iommu/iommu.c:1822
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81627d50-ffffffff81627d81: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81661baa)
Location: drivers/iommu/iommu.c:1828
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81662920-ffffffff81662950: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8168026a)
Location: drivers/iommu/iommu.c:1885
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81680b80-ffffffff81680bb0: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b862d)
Location: drivers/iommu/iommu.c:2106
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816b83d0-ffffffff816b83fd: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816db44d)
Location: drivers/iommu/iommu.c:2164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816db130-ffffffff816db15d: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f71d)
Location: drivers/iommu/iommu.c:2508
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81790430-ffffffff8179045d: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817ba2ad)
Location: drivers/iommu/iommu.c:2731
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff817bc670-ffffffff817bc69d: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179db0d)
Location: drivers/iommu/iommu.c:2717
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff8179f920-ffffffff8179f94d: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81826b0d)
Location: drivers/iommu/iommu.c:2802
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81828910-ffffffff8182893d: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819660a9)
Location: drivers/iommu/iommu.c:2579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff819688c0-ffffffff819688fd: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acfaa6)
Location: drivers/iommu/iommu.c:2654
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81acd950-ffffffff81acd9b4: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b200e2)
Location: drivers/iommu/iommu.c:2660
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81b1c3a0-ffffffff81b1c404: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b76691)
Location: drivers/iommu/iommu.c:2936
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81b72720-ffffffff81b72784: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c7424)
Location: drivers/iommu/iommu.c:2164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffff8000108c70a8-ffff8000108c70f0: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bcc88)
Location: drivers/iommu/iommu.c:2164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
c09be084-c09be0bc: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096bbdc)
Location: drivers/iommu/iommu.c:2164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
c00000000096e460-c00000000096e4b8: iommu_put_resv_regions (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a0e9d)
Location: drivers/iommu/iommu.c:2164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816a0b80-ffffffff816a0bad: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167e88d)
Location: drivers/iommu/iommu.c:2164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff8167e570-ffffffff8167e59d: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cf10d)
Location: drivers/iommu/iommu.c:2164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816cedf0-ffffffff816cee1d: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iommu_put_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e967d)
Location: drivers/iommu/iommu.c:2164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816e9360-ffffffff816e938d: iommu_put_resv_regions (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
