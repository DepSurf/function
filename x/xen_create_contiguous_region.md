# Function: <code>xen_create_contiguous_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101f890)
Location: arch/x86/xen/mmu.c:2622
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8101f890-ffffffff8101fa46: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ecb0)
Location: arch/x86/xen/mmu.c:2612
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8101ecb0-ffffffff8101ee89: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101f3a0)
Location: arch/x86/xen/mmu.c:2612
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8101f3a0-ffffffff8101f579: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810223b0)
Location: arch/x86/xen/mmu_pv.c:2613
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff810223b0-ffffffff81022587: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022e90)
Location: arch/x86/xen/mmu_pv.c:2554
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81022e90-ffffffff81023067: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810252e0)
Location: arch/x86/xen/mmu_pv.c:2590
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff810252e0-ffffffff810254ca: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810234b0)
Location: arch/x86/xen/mmu_pv.c:2598
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff810234b0-ffffffff8102369a: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810240a0)
Location: arch/x86/xen/mmu_pv.c:2586
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff810240a0-ffffffff8102428b: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028110)
Location: arch/x86/xen/mmu_pv.c:2586
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81028110-ffffffff810282fb: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a020)
Location: arch/x86/xen/mmu_pv.c:2586
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8102a020-ffffffff8102a20b: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102aa00)
Location: arch/x86/xen/mmu_pv.c:2268
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff8102aa00-ffffffff8102abeb: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102b5f0)
Location: arch/x86/xen/mmu_pv.c:2267
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
**Symbols:**

```
ffffffff8102b5f0-ffffffff8102b7db: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102fd50)
Location: arch/x86/xen/mmu_pv.c:2270
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
**Symbols:**

```
ffffffff8102fd50-ffffffff8102ff38: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81035340)
Location: arch/x86/xen/mmu_pv.c:2296
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
**Symbols:**

```
ffffffff81035340-ffffffff81035548: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103cf90)
Location: arch/x86/xen/mmu_pv.c:2296
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
**Symbols:**

```
ffffffff8103cf90-ffffffff8103d198: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103ce70)
Location: arch/x86/xen/mmu_pv.c:2304
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
**Symbols:**

```
ffffffff8103ce70-ffffffff8103d072: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81043340)
Location: arch/x86/xen/mmu_pv.c:2321
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
**Symbols:**

```
ffffffff81043340-ffffffff8104353d: xen_create_contiguous_region (STB_GLOBAL)
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
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/xen/mm.c (ffff8000100f0c88)
Location: arch/arm/xen/mm.c:119
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffff8000100f0c88-ffff8000100f0cd8: xen_create_contiguous_region (STB_GLOBAL)
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
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028270)
Location: arch/x86/xen/mmu_pv.c:2586
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81028270-ffffffff8102845b: xen_create_contiguous_region (STB_GLOBAL)
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
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810280d0)
Location: arch/x86/xen/mmu_pv.c:2586
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff810280d0-ffffffff810282bb: xen_create_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_create_contiguous_region(phys_addr_t pstart, unsigned int order, unsigned int address_bits, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028d60)
Location: arch/x86/xen/mmu_pv.c:2586
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81028d60-ffffffff81028f4b: xen_create_contiguous_region (STB_GLOBAL)
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
