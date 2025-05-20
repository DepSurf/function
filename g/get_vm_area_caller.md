# Function: <code>get_vm_area_caller</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cec00)
Location: mm/vmalloc.c:1396
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:alloc_vm_area
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff811cec00-ffffffff811cec42: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec136)
Location: mm/vmalloc.c:1420
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff811ebda0-ffffffff811ebde3: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd376)
Location: mm/vmalloc.c:1403
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff811fcfd0-ffffffff811fd013: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81208056)
Location: mm/vmalloc.c:1454
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff81207cd0-ffffffff81207d09: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81221136)
Location: mm/vmalloc.c:1452
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff81220dc0-ffffffff81220df9: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242fe5)
Location: mm/vmalloc.c:1439
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - kernel/dma/mapping.c:dma_common_contiguous_remap
  - kernel/dma/mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff81242c60-ffffffff81242c99: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812576f5)
Location: mm/vmalloc.c:1441
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81257340-ffffffff81257379: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a4a5)
Location: mm/vmalloc.c:2104
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8126a3b0-ffffffff8126a3e9: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812793b5)
Location: mm/vmalloc.c:2110
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff812792c0-ffffffff812792f9: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812abbd0)
Location: mm/vmalloc.c:2155
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffff812abbd0-ffffffff812abc2a: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b70f0)
Location: mm/vmalloc.c:2137
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffff812b70f0-ffffffff812b714a: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bc9c0)
Location: mm/vmalloc.c:2412
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffff812bc9c0-ffffffff812bca1a: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff150)
Location: mm/vmalloc.c:2464
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffff812ff150-ffffffff812ff1aa: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81366160)
Location: mm/vmalloc.c:2504
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffff81366160-ffffffff813661be: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e1d40)
Location: mm/vmalloc.c:2566
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffff813e1d40-ffffffff813e1d9e: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81416a80)
Location: mm/vmalloc.c:2646
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffff81416a80-ffffffff81416ade: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81443550)
Location: mm/vmalloc.c:2646
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffff81443550-ffffffff814435ae: get_vm_area_caller (STB_GLOBAL)
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
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030fe30)
Location: mm/vmalloc.c:2110
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/arm64/mm/ioremap.c:__ioremap_caller
  - kernel/dma/remap.c:__dma_common_pages_remap
```
**Symbols:**

```
ffff80001030fce0-ffff80001030fd44: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c204)
Location: mm/vmalloc.c:2110
Inline: False
Direct callers:
  - arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller
  - kernel/dma/remap.c:__dma_common_pages_remap
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
c052c204-c052c264: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e10d4)
Location: mm/vmalloc.c:2110
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
c0000000003e0f50-c0000000003e0f94: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe00021835c)
Location: mm/vmalloc.c:2110
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/riscv/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffe00021825e-ffffffe0002182aa: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271a05)
Location: mm/vmalloc.c:2110
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81271910-ffffffff81271949: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263975)
Location: mm/vmalloc.c:2110
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81263880-ffffffff812638b9: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126f7a5)
Location: mm/vmalloc.c:2110
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8126f6b0-ffffffff8126f6e9: get_vm_area_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *get_vm_area_caller(long unsigned int size, long unsigned int flags, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f1b5)
Location: mm/vmalloc.c:2110
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8127f0d0-ffffffff8127f109: get_vm_area_caller (STB_GLOBAL)
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
