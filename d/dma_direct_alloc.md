# Function: <code>dma_direct_alloc</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110cd60)
Location: kernel/dma/direct.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/swiotlb.c:swiotlb_alloc
```
**Symbols:**

```
ffffffff8110cd60-ffffffff8110cf58: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118d80)
Location: kernel/dma/direct.c:196
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff81118d80-ffffffff81118d90: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81123270)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff81123270-ffffffff81123280: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f6b0)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff8112f6b0-ffffffff8112f6c0: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e2a0)
Location: kernel/dma/direct.c:289
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff8113e2a0-ffffffff8113e2b0: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81138a00)
Location: kernel/dma/direct.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff81138a00-ffffffff81138c9a: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139ae0)
Location: kernel/dma/direct.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff81139ae0-ffffffff81139d7a: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff81cb03bd-ffffffff81cb03dc: dma_direct_alloc.cold (STB_LOCAL)
ffffffff8115cb30-ffffffff8115cdde: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81186930)
Location: kernel/dma/direct.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff81186930-ffffffff81186bb7: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c23c0)
Location: kernel/dma/direct.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff811c23c0-ffffffff811c2647: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d4f00)
Location: kernel/dma/direct.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff811d4f00-ffffffff811d5187: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811e9df0)
Location: kernel/dma/direct.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff811e9df0-ffffffff811ea07d: dma_direct_alloc (STB_GLOBAL)
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
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff8000101950d8)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
**Symbols:**

```
ffff8000101950d8-ffff80001019516c: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e1e4c)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
c03e1e4c-c03e1e78: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f54c0)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
c0000000001f54c0-c0000000001f54d4: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126e8a)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffe000126e8a-ffffffe000126ed4: dma_direct_alloc (STB_GLOBAL)
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
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127cf0)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
**Symbols:**

```
ffffffff81127cf0-ffffffff81127d00: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a6f0)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff8111a6f0-ffffffff8111a700: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125b80)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff81125b80-ffffffff81125b90: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *dma_direct_alloc(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811321c0)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff811321c0-ffffffff811321d0: dma_direct_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
