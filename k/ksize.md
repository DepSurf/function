# Function: <code>ksize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8a50)
Location: mm/slub.c:3605
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:__krealloc
  - mm/slab_common.c:krealloc
  - fs/coredump.c:expand_corename
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff811e8a50-ffffffff811e8b0c: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81206740)
Location: mm/slub.c:3828
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - fs/coredump.c:expand_corename
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81206740-ffffffff8120681d: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81218770)
Location: mm/slub.c:3850
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - fs/coredump.c:expand_corename
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81218770-ffffffff81218848: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81223fe0)
Location: mm/slub.c:3855
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - fs/coredump.c:expand_corename
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81223fe0-ffffffff812240a0: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123f620)
Location: mm/slub.c:3871
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - fs/coredump.c:expand_corename
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8123f620-ffffffff8123f6f0: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81262ca0)
Location: mm/slub.c:3880
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:__d_free_external_name
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81262ca0-ffffffff81262d6e: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81277520)
Location: mm/slub.c:3932
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81277520-ffffffff812775f6: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81240b80)
Location: mm/slab_common.c:1698
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81240b80-ffffffff81240ba3: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124f130)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8124f130-ffffffff8124f153: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127d9e4)
Location: mm/slab_common.c:1748
Inline: True
Inline callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
Direct callers:
  - fs/coredump.c:format_corename
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8127d2b0-ffffffff8127d2d3: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81287bd5)
Location: mm/slab_common.c:1155
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
Direct callers:
  - fs/coredump.c:format_corename
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/base/devres.c:devm_krealloc
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81287bb0-ffffffff81287bc9: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128cd65)
Location: mm/slab_common.c:1252
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
Direct callers:
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/base/devres.c:devm_krealloc
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
```
**Symbols:**

```
ffffffff8128cd40-ffffffff8128cd59: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cd305)
Location: mm/slab_common.c:1286
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
Direct callers:
  - kernel/bpf/verifier.c:copy_array
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/base/devres.c:devm_krealloc
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
```
**Symbols:**

```
ffffffff812ccc00-ffffffff812ccc35: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132bc15)
Location: mm/slab_common.c:1263
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - kernel/bpf/verifier.c:copy_array
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/base/devres.c:devm_krealloc
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
```
**Symbols:**

```
ffffffff8132b300-ffffffff8132b346: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a25b5)
Location: mm/slab_common.c:1431
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
Direct callers:
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/memalloc.c:bpf_mem_free
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/base/devres.c:devm_krealloc
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
**Symbols:**

```
ffffffff813a2550-ffffffff813a2596: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d5a75)
Location: mm/slab_common.c:1439
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
Direct callers:
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/memalloc.c:bpf_mem_free
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/base/devres.c:devm_krealloc
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
**Symbols:**

```
ffffffff813d5a10-ffffffff813d5a56: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813ff745)
Location: mm/slab_common.c:1253
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
Direct callers:
  - kernel/bpf/verifier.c:copy_array
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/base/devres.c:devm_krealloc
  - drivers/gpu/drm/drm_managed.c:drmm_add_final_kfree
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
**Symbols:**

```
ffffffff813ff6e0-ffffffff813ff726: ksize (STB_GLOBAL)
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
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e5448)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffff8000102e5448-ffff8000102e549c: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050a318)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - fs/coredump.c:expand_corename
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
c050a318-c050a388: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a73b0)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
c0000000003a73b0-c0000000003a7418: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fbf7a)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffe0001fbf7a-ffffffe0001fbfbe: ksize (STB_GLOBAL)
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
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81247780)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81247780-ffffffff812477a3: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123a730)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff8123a730-ffffffff8123a753: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81245520)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81245520-ffffffff81245543: ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t ksize(const void *objp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81254f30)
Location: mm/slab_common.c:1762
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff81254f30-ffffffff81254f53: ksize (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *objp</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *object</code>
</li>
</ul>
</details>
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
