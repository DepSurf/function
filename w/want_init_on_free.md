# Function: <code>want_init_on_free</code>

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
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002a37)
Location: include/linux/mm.h:2710
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff8126d49a)
Location: include/linux/mm.h:2710
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff81280783)
Location: include/linux/mm.h:2710
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
**Symbols:**

```
ffffffff81002a37-ffffffff81002a56: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002a37)
Location: include/linux/mm.h:2685
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff8127bfda)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff812901b3)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
**Symbols:**

```
ffffffff81002a37-ffffffff81002a56: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81003aa8)
Location: include/linux/mm.h:2932
Inline: False
Direct callers:
  - init/main.c:report_meminit
  - init/main.c:report_meminit
```
```
In mm/page_alloc.c (ffffffff812af7b4)
Location: include/linux/mm.h:2932
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff812c2e13)
Location: include/linux/mm.h:2932
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710505)
Location: include/linux/mm.h:2932
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81003aa8-ffffffff81003ac7: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81bd16a3)
Location: include/linux/mm.h:2961
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff81113551)
Location: include/linux/mm.h:2961
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_page
```
```
In mm/page_alloc.c (ffffffff812be014)
Location: include/linux/mm.h:2961
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff812cead8)
Location: include/linux/mm.h:2961
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d0e5)
Location: include/linux/mm.h:2961
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81bd16a3-ffffffff81bd16ae: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81bc36b3)
Location: include/linux/mm.h:2959
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff81113f33)
Location: include/linux/mm.h:2959
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff812c47ca)
Location: include/linux/mm.h:2959
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff812d5628)
Location: include/linux/mm.h:2959
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710545)
Location: include/linux/mm.h:2959
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81bc36b3-ffffffff81bc36be: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81c9472b)
Location: include/linux/mm.h:3017
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff81134021)
Location: include/linux/mm.h:3017
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff81308643)
Location: include/linux/mm.h:3017
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff8131b448)
Location: include/linux/mm.h:3017
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178cf25)
Location: include/linux/mm.h:3017
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81c9472b-ffffffff81c94733: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81e4386f)
Location: include/linux/mm.h:3129
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff8115609d)
Location: include/linux/mm.h:3129
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/vmalloc.c (ffffffff81366ff1)
Location: include/linux/mm.h:3129
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff813709c6)
Location: include/linux/mm.h:3129
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff81386c38)
Location: include/linux/mm.h:3129
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c5025)
Location: include/linux/mm.h:3129
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81e4386f-ffffffff81e4387f: want_init_on_free (STB_LOCAL)
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
In init/main.c (ffffffff83e61283)
Location: include/linux/mm.h:3321
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff811866ef)
Location: include/linux/mm.h:3321
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/vmalloc.c (ffffffff813e2e91)
Location: include/linux/mm.h:3321
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff813ece48)
Location: include/linux/mm.h:3321
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff81404ad4)
Location: include/linux/mm.h:3321
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a158c5)
Location: include/linux/mm.h:3321
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
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
In kernel/power/snapshot.c (ffffffff811977a1)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/mm_init.c (ffffffff836e2f6e)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
```
```
In mm/vmalloc.c (ffffffff81417aee)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff81421d92)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/dmapool.c (ffffffff814386ea)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ec45)
Location: include/linux/mm.h:3496
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
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
In kernel/power/snapshot.c (ffffffff811a63b1)
Location: include/linux/mm.h:3702
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/mm_init.c (ffffffff839157fe)
Location: include/linux/mm.h:3702
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
```
```
In mm/vmalloc.c (ffffffff8144463e)
Location: include/linux/mm.h:3702
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff8144ebc4)
Location: include/linux/mm.h:3702
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/dmapool.c (ffffffff8147207a)
Location: include/linux/mm.h:3702
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab13a5)
Location: include/linux/mm.h:3702
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffff800010085074)
Location: include/linux/mm.h:2685
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffff800010313570)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffff80001032d220)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
**Symbols:**

```
ffff800010085074-ffff8000100850a4: want_init_on_free (STB_LOCAL)
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
In init/main.c (c1500e94)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (c052e304)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (c05430a0)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c000000000010390)
Location: include/linux/mm.h:2685
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (c0000000003e5200)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (c000000000404ca4)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
**Symbols:**

```
c000000000010390-c0000000000103d8: want_init_on_free (STB_LOCAL)
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
In init/main.c (ffffffe000000bac)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffe00021a816)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffe00022b908)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002a37)
Location: include/linux/mm.h:2685
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff8127462a)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff81288793)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
**Symbols:**

```
ffffffff81002a37-ffffffff81002a56: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81000f0a)
Location: include/linux/mm.h:2685
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff8126659a)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff8127a5e3)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
**Symbols:**

```
ffffffff81000f0a-ffffffff81000f29: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002a37)
Location: include/linux/mm.h:2685
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff812723ca)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff812865a3)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
**Symbols:**

```
ffffffff81002a37-ffffffff81002a56: want_init_on_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool want_init_on_free();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002a67)
Location: include/linux/mm.h:2685
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In mm/page_alloc.c (ffffffff812821fa)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/dmapool.c (ffffffff81296393)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
```
**Symbols:**

```
ffffffff81002a67-ffffffff81002a86: want_init_on_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
