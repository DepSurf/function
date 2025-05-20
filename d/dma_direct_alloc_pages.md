# Function: <code>dma_direct_alloc_pages</code>

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
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118bd0)
Location: kernel/dma/direct.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff81118bd0-ffffffff81118cb4: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81123060)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff81123060-ffffffff8112318b: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f4a0)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff8112f4a0-ffffffff8112f5cb: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e030)
Location: kernel/dma/direct.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff8113e030-ffffffff8113e1cb: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81138de0)
Location: kernel/dma/direct.c:279
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_pages
```
**Symbols:**

```
ffffffff81138de0-ffffffff81138f7d: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139ec0)
Location: kernel/dma/direct.c:279
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_alloc_pages
```
**Symbols:**

```
ffffffff81139ec0-ffffffff8113a05d: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:318
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_alloc_pages
```
**Symbols:**

```
ffffffff81cb03fa-ffffffff81cb0419: dma_direct_alloc_pages.cold (STB_LOCAL)
ffffffff8115cf20-ffffffff8115d0d2: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81186d60)
Location: kernel/dma/direct.c:367
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_alloc_pages
```
**Symbols:**

```
ffffffff81186d60-ffffffff81186f15: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c2820)
Location: kernel/dma/direct.c:367
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_alloc_pages
```
**Symbols:**

```
ffffffff811c2820-ffffffff811c29d5: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d5360)
Location: kernel/dma/direct.c:366
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_alloc_pages
```
**Symbols:**

```
ffffffff811d5360-ffffffff811d5515: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811ea250)
Location: kernel/dma/direct.c:355
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_alloc_pages
```
**Symbols:**

```
ffffffff811ea250-ffffffff811ea40b: dma_direct_alloc_pages (STB_GLOBAL)
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
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194f08)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffff800010194f08-ffff80001019500c: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e1c9c)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
c03e1c9c-c03e1dd8: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f51e0)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
c0000000001f51e0-c0000000001f5378: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126d4a)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffe000126d4a-ffffffe000126dd8: dma_direct_alloc_pages (STB_GLOBAL)
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
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127ae0)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff81127ae0-ffffffff81127c0b: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a4e0)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff8111a4e0-ffffffff8111a60b: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125970)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff81125970-ffffffff81125a9b: dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131fb0)
Location: kernel/dma/direct.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff81131fb0-ffffffff811320db: dma_direct_alloc_pages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum dma_data_direction dir</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int attrs</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, size, dma_handle, gfp, attrs</code> ➡️ <code>dev, size, dma_handle, dir, gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>struct page *</code>
</li>
</ul>
</details>
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
