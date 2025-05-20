# Function: <code>page_poisoning_enabled</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81262b05)
Location: mm/page_poison.c:20
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81262ae0-ffffffff81262af2: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81277385)
Location: mm/page_poison.c:25
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
**Symbols:**

```
ffffffff81277360-ffffffff81277372: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81292cc5)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff81292ca0-ffffffff81292cb2: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff812a2a45)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff812a2a20-ffffffff812a2a32: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff812d7255)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:report_meminit
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff812d71a0-ffffffff812d71b2: page_poisoning_enabled (STB_GLOBAL)
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
In kernel/power/snapshot.c (ffffffff81113548)
Location: include/linux/mm.h:2922
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff812bb382)
Location: include/linux/mm.h:2922
Inline: True
Inline callers:
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
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
In kernel/power/snapshot.c (ffffffff81113f2a)
Location: include/linux/mm.h:2919
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff812c04c5)
Location: include/linux/mm.h:2919
Inline: True
Inline callers:
  - mm/page_alloc.c:init_mem_debugging_and_hardening
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
In kernel/power/snapshot.c (ffffffff8113400c)
Location: include/linux/mm.h:2977
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff81303275)
Location: include/linux/mm.h:2977
Inline: True
Inline callers:
  - mm/page_alloc.c:init_mem_debugging_and_hardening
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
In kernel/power/snapshot.c (ffffffff81156088)
Location: include/linux/mm.h:3089
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff8136ac35)
Location: include/linux/mm.h:3089
Inline: True
Inline callers:
  - mm/page_alloc.c:init_mem_debugging_and_hardening
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
In kernel/power/snapshot.c (ffffffff8118661c)
Location: include/linux/mm.h:3281
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff83ebe935)
Location: include/linux/mm.h:3281
Inline: True
Inline callers:
  - mm/page_alloc.c:init_mem_debugging_and_hardening
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
In kernel/power/snapshot.c (ffffffff8119778c)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/mm_init.c (ffffffff836e2e3c)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
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
In kernel/power/snapshot.c (ffffffff811a639c)
Location: include/linux/mm.h:3662
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/mm_init.c (ffffffff839156cc)
Location: include/linux/mm.h:3662
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
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
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffff800010342ae4)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffff800010342aa0-ffff800010342ac0: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (c05481fc)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
c05481c4-c05481e8: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (c00000000041ff40)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
c00000000041ff10-c00000000041ff2c: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffe0002366e8)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffe0002366a4-ffffffe0002366c6: page_poisoning_enabled (STB_GLOBAL)
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
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff8129b025)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff8129b000-ffffffff8129b012: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff8128cbe5)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff8128cbc0-ffffffff8128cbd2: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81298e35)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff81298e10-ffffffff81298e22: page_poisoning_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool page_poisoning_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff812a8c15)
Location: mm/page_poison.c:26
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:want_init_on_free
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - net/core/sock.c:sk_prot_alloc
```
**Symbols:**

```
ffffffff812a8bf0-ffffffff812a8c02: page_poisoning_enabled (STB_GLOBAL)
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
