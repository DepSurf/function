# Function: <code>dma_direct_free_pages</code>

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
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118cf0)
Location: kernel/dma/direct.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff81118cf0-ffffffff81118d80: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811231c0)
Location: kernel/dma/direct.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff811231c0-ffffffff81123270: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f600)
Location: kernel/dma/direct.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff8112f600-ffffffff8112f6b0: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e1d0)
Location: kernel/dma/direct.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff8113e1d0-ffffffff8113e292: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_addr, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81138f80)
Location: kernel/dma/direct.c:317
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_pages
```
**Symbols:**

```
ffffffff81138f80-ffffffff8113901d: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_addr, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113a060)
Location: kernel/dma/direct.c:317
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_pages
```
**Symbols:**

```
ffffffff8113a060-ffffffff8113a0fd: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_addr, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:357
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_pages
```
**Symbols:**

```
ffffffff81cb0419-ffffffff81cb0437: dma_direct_free_pages.cold (STB_LOCAL)
ffffffff8115d0e0-ffffffff8115d190: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_addr, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:391
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_pages
```
**Symbols:**

```
ffffffff81e61070-ffffffff81e61081: dma_direct_free_pages.cold (STB_LOCAL)
ffffffff81186f20-ffffffff81186feb: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_addr, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c29f0)
Location: kernel/dma/direct.c:391
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_pages
```
**Symbols:**

```
ffffffff811c29f0-ffffffff811c2ac7: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_addr, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d5530)
Location: kernel/dma/direct.c:390
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_pages
```
**Symbols:**

```
ffffffff811d5530-ffffffff811d5607: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_addr, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811ea420)
Location: kernel/dma/direct.c:379
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_pages
```
**Symbols:**

```
ffffffff811ea420-ffffffff811ea4f7: dma_direct_free_pages (STB_GLOBAL)
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
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010195058)
Location: kernel/dma/direct.c:183
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffff800010195058-ffff8000101950d8: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e1e00)
Location: kernel/dma/direct.c:183
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
c03e1e00-c03e1e4c: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f53d0)
Location: kernel/dma/direct.c:183
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
c0000000001f53d0-c0000000001f54b8: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126e12)
Location: kernel/dma/direct.c:183
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffe000126e12-ffffffe000126e8a: dma_direct_free_pages (STB_GLOBAL)
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
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127c30)
Location: kernel/dma/direct.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff81127c30-ffffffff81127ce7: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a640)
Location: kernel/dma/direct.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff8111a640-ffffffff8111a6f0: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125ad0)
Location: kernel/dma/direct.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff81125ad0-ffffffff81125b80: dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_direct_free_pages(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81132110)
Location: kernel/dma/direct.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff81132110-ffffffff811321c0: dma_direct_free_pages (STB_GLOBAL)
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
<code>struct page *page</code>
</li>
<li>
<b>Param added. </b>
<code>enum dma_data_direction dir</code>
</li>
<li>
<b>Param removed. </b>
<code>void *cpu_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int attrs</code>
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
