# Function: <code>xen_destroy_contiguous_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101fa50)
Location: arch/x86/xen/mmu.c:2669
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8101fa50-ffffffff8101fbca: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ee90)
Location: arch/x86/xen/mmu.c:2659
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8101ee90-ffffffff8101f00c: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101f580)
Location: arch/x86/xen/mmu.c:2659
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8101f580-ffffffff8101f6fc: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022590)
Location: arch/x86/xen/mmu_pv.c:2657
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81022590-ffffffff810226fb: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023070)
Location: arch/x86/xen/mmu_pv.c:2598
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81023070-ffffffff810231db: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810254d0)
Location: arch/x86/xen/mmu_pv.c:2634
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff810254d0-ffffffff8102563e: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810236a0)
Location: arch/x86/xen/mmu_pv.c:2642
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff810236a0-ffffffff8102380e: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024290)
Location: arch/x86/xen/mmu_pv.c:2630
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81024290-ffffffff810243fd: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028300)
Location: arch/x86/xen/mmu_pv.c:2629
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81028300-ffffffff8102846d: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a210)
Location: arch/x86/xen/mmu_pv.c:2629
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8102a210-ffffffff8102a37d: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102abf0)
Location: arch/x86/xen/mmu_pv.c:2311
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8102abf0-ffffffff8102ad5d: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102b7e0)
Location: arch/x86/xen/mmu_pv.c:2310
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8102b7e0-ffffffff8102b94d: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102ff40)
Location: arch/x86/xen/mmu_pv.c:2313
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8102ff40-ffffffff810300ad: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81035550)
Location: arch/x86/xen/mmu_pv.c:2339
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81035550-ffffffff810356e2: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103d1b0)
Location: arch/x86/xen/mmu_pv.c:2339
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8103d1b0-ffffffff8103d342: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103d090)
Location: arch/x86/xen/mmu_pv.c:2347
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8103d090-ffffffff8103d219: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81043550)
Location: arch/x86/xen/mmu_pv.c:2358
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81043550-ffffffff810436d9: xen_destroy_contiguous_region (STB_GLOBAL)
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/xen/mm.c (ffff8000100f0cd8)
Location: arch/arm/xen/mm.c:131
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffff8000100f0cd8-ffff8000100f0cf0: xen_destroy_contiguous_region (STB_GLOBAL)
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028460)
Location: arch/x86/xen/mmu_pv.c:2629
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81028460-ffffffff810285cd: xen_destroy_contiguous_region (STB_GLOBAL)
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810282c0)
Location: arch/x86/xen/mmu_pv.c:2629
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff810282c0-ffffffff8102842d: xen_destroy_contiguous_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028f50)
Location: arch/x86/xen/mmu_pv.c:2629
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81028f50-ffffffff810290bd: xen_destroy_contiguous_region (STB_GLOBAL)
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
