# Function: <code>xen_swiotlb_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d44b0)
Location: drivers/xen/swiotlb-xen.c:295
Inline: False
```
**Symbols:**

```
ffffffff814d44b0-ffffffff814d46bb: xen_swiotlb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815252e0)
Location: drivers/xen/swiotlb-xen.c:295
Inline: False
```
**Symbols:**

```
ffffffff815252e0-ffffffff815254f5: xen_swiotlb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815517a0)
Location: drivers/xen/swiotlb-xen.c:299
Inline: False
```
**Symbols:**

```
ffffffff815517a0-ffffffff815519b5: xen_swiotlb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81565f10)
Location: drivers/xen/swiotlb-xen.c:302
Inline: False
```
**Symbols:**

```
ffffffff81565f10-ffffffff81566122: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815ca0b0)
Location: drivers/xen/swiotlb-xen.c:302
Inline: False
```
**Symbols:**

```
ffffffff815ca0b0-ffffffff815ca2c2: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81602840)
Location: drivers/xen/swiotlb-xen.c:288
Inline: False
```
**Symbols:**

```
ffffffff81602840-ffffffff81602a84: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161d9e0)
Location: drivers/xen/swiotlb-xen.c:288
Inline: False
```
**Symbols:**

```
ffffffff8161d9e0-ffffffff8161dc07: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81651ba0)
Location: drivers/xen/swiotlb-xen.c:276
Inline: False
```
**Symbols:**

```
ffffffff81651ba0-ffffffff81652032: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81674150)
Location: drivers/xen/swiotlb-xen.c:276
Inline: False
```
**Symbols:**

```
ffffffff81674150-ffffffff816745e2: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81724770)
Location: drivers/xen/swiotlb-xen.c:276
Inline: False
```
**Symbols:**

```
ffffffff81724770-ffffffff81724bf9: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817414c0)
Location: drivers/xen/swiotlb-xen.c:277
Inline: False
```
**Symbols:**

```
ffffffff817414c0-ffffffff81741a85: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81724e70)
Location: drivers/xen/swiotlb-xen.c:264
Inline: False
```
**Symbols:**

```
ffffffff81724e70-ffffffff81725438: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:262
Inline: False
```
**Symbols:**

```
ffffffff817a3d00-ffffffff817a42d4: xen_swiotlb_alloc_coherent (STB_LOCAL)
ffffffff81cf6751-ffffffff81cf6770: xen_swiotlb_alloc_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:134
Inline: False
```
**Symbols:**

```
ffffffff818de070-ffffffff818de4f5: xen_swiotlb_alloc_coherent (STB_LOCAL)
ffffffff81ebe8c1-ffffffff81ebe8f0: xen_swiotlb_alloc_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:134
Inline: False
```
**Symbols:**

```
ffffffff81a31570-ffffffff81a319f5: xen_swiotlb_alloc_coherent (STB_LOCAL)
ffffffff82094a22-ffffffff82094a51: xen_swiotlb_alloc_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:134
Inline: False
```
**Symbols:**

```
ffffffff81a7ad80-ffffffff81a7b205: xen_swiotlb_alloc_coherent (STB_LOCAL)
ffffffff82115846-ffffffff82115875: xen_swiotlb_alloc_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:134
Inline: False
```
**Symbols:**

```
ffffffff81acd240-ffffffff81acd6b8: xen_swiotlb_alloc_coherent (STB_LOCAL)
ffffffff821f34e9-ffffffff821f3518: xen_swiotlb_alloc_coherent.cold (STB_LOCAL)
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
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff80001083e280)
Location: drivers/xen/swiotlb-xen.c:276
Inline: False
```
**Symbols:**

```
ffff80001083e280-ffff80001083e4f4: xen_swiotlb_alloc_coherent (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81639e40)
Location: drivers/xen/swiotlb-xen.c:276
Inline: False
```
**Symbols:**

```
ffffffff81639e40-ffffffff8163a2d2: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81667f90)
Location: drivers/xen/swiotlb-xen.c:276
Inline: False
```
**Symbols:**

```
ffffffff81667f90-ffffffff81668422: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xen_swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81682550)
Location: drivers/xen/swiotlb-xen.c:276
Inline: False
```
**Symbols:**

```
ffffffff81682550-ffffffff816829e2: xen_swiotlb_alloc_coherent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *hwdev</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
