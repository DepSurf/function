# Function: <code>want_init_on_alloc</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82899ede)
Location: include/linux/mm.h:2697
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff8126d49f)
Location: include/linux/mm.h:2697
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffffffff812805a6)
Location: include/linux/mm.h:2697
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff818e0901)
Location: include/linux/mm.h:2697
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289cec3)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff8127bfdf)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffffffff8128ffd6)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff81912b41)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82cc31be)
Location: include/linux/mm.h:2919
Inline: True
Inline callers:
  - init/main.c:report_meminit
```
```
In mm/page_alloc.c (ffffffff812af7b9)
Location: include/linux/mm.h:2919
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffffffff812c2cfe)
Location: include/linux/mm.h:2919
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff819e3b1d)
Location: include/linux/mm.h:2919
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82faf503)
Location: include/linux/mm.h:2953
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff812be019)
Location: include/linux/mm.h:2953
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/dmapool.c (ffffffff812ceb9e)
Location: include/linux/mm.h:2953
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff819e34bd)
Location: include/linux/mm.h:2953
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff831b9524)
Location: include/linux/mm.h:2950
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff812c47cf)
Location: include/linux/mm.h:2950
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/dmapool.c (ffffffff812d56f6)
Location: include/linux/mm.h:2950
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff819c953d)
Location: include/linux/mm.h:2950
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83299883)
Location: include/linux/mm.h:3008
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff81308645)
Location: include/linux/mm.h:3008
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/dmapool.c (ffffffff8131b516)
Location: include/linux/mm.h:3008
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff81a788bd)
Location: include/linux/mm.h:3008
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83447ac2)
Location: include/linux/mm.h:3120
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/vmalloc.c (ffffffff81366ff3)
Location: include/linux/mm.h:3120
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff813709cf)
Location: include/linux/mm.h:3120
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/dmapool.c (ffffffff81386d10)
Location: include/linux/mm.h:3120
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff81bec2f5)
Location: include/linux/mm.h:3120
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e6128f)
Location: include/linux/mm.h:3312
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/vmalloc.c (ffffffff813e2e93)
Location: include/linux/mm.h:3312
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff813ece51)
Location: include/linux/mm.h:3312
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/dmapool.c (ffffffff81404be0)
Location: include/linux/mm.h:3312
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff81d98d55)
Location: include/linux/mm.h:3312
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e2f7a)
Location: include/linux/mm.h:3487
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
```
```
In mm/vmalloc.c (ffffffff81417af0)
Location: include/linux/mm.h:3487
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff81421d97)
Location: include/linux/mm.h:3487
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/dmapool.c (ffffffff8143813c)
Location: include/linux/mm.h:3487
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff81e070d5)
Location: include/linux/mm.h:3487
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8391580a)
Location: include/linux/mm.h:3693
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
```
```
In mm/vmalloc.c (ffffffff81444640)
Location: include/linux/mm.h:3693
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff8144ebc9)
Location: include/linux/mm.h:3693
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/dmapool.c (ffffffff81471a9c)
Location: include/linux/mm.h:3693
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff81ec3945)
Location: include/linux/mm.h:3693
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffff800011430ec8)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffff800010313574)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffff80001032d374)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffff800010baa2cc)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c1500e60)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (c052e318)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (c0542eac)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (c0cc8e00)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c000000001343fc0)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (c0000000003e5204)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (c0000000004049cc)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (c000000000c80454)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffe000000b84)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffe00021a822)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffffffe00022b754)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffe00073dc8e)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8288aec3)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff8127462f)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffffffff812885b6)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff818b2b41)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82888e63)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff8126659f)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffffffff8127a406)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff8186ca91)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289dec3)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff812723cf)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffffffff812863c6)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff81903b41)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289dec3)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff812821ff)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/dmapool.c (ffffffff812961ba)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In net/core/sock.c (ffffffff81924b41)
Location: include/linux/mm.h:2672
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
</ul>

## Differences
