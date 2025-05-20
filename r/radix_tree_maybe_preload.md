# Function: <code>radix_tree_maybe_preload</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee100)
Location: lib/radix-tree.c:304
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swap_state.c:add_to_swap
  - mm/swap_state.c:__read_swap_cache_async
  - block/blk-ioc.c:ioc_create_icq
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff813ee100-ffffffff813ee116: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81434fe0)
Location: lib/radix-tree.c:404
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
  - block/blk-ioc.c:ioc_create_icq
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff81434fe0-ffffffff81434ffb: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff814511e0)
Location: lib/radix-tree.c:436
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
  - block/blk-ioc.c:ioc_create_icq
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff814511e0-ffffffff814511fb: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1220)
Location: lib/radix-tree.c:522
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/swap_state.c:__read_swap_cache_async
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff818f1220-ffffffff818f123b: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977660)
Location: lib/radix-tree.c:522
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/swap_state.c:__read_swap_cache_async
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81977660-ffffffff8197767c: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3e00)
Location: lib/radix-tree.c:523
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/swap_state.c:__read_swap_cache_async
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff819d3e00-ffffffff819d3e1c: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d060)
Location: lib/radix-tree.c:400
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81a0d060-ffffffff81a0d07c: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c990)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81a7c990-ffffffff81a7c9ab: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3cc0)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81ab3cc0-ffffffff81ab3cdb: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815edc00)
Location: lib/radix-tree.c:379
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff815edc00-ffffffff815edc1b: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612330)
Location: lib/radix-tree.c:379
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81612330-ffffffff8161234b: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5a10)
Location: lib/radix-tree.c:379
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff815f5a10-ffffffff815f5a2b: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81662e80)
Location: lib/radix-tree.c:379
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81662e80-ffffffff81662e9b: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177d050)
Location: lib/radix-tree.c:379
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff8177d050-ffffffff8177d082: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820398c0)
Location: lib/radix-tree.c:379
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff820398c0-ffffffff820398f2: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b7be0)
Location: lib/radix-tree.c:378
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff820b7be0-ffffffff820b7c12: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff821924f0)
Location: lib/radix-tree.c:378
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
**Symbols:**

```
ffffffff821924f0-ffffffff82192522: radix_tree_maybe_preload (STB_GLOBAL)
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
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e6d0)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffff800010d8e6d0-ffff800010d8e6f4: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88918)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
c0e88918-c0e8893c: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed09f0)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
c000000000ed09f0-c000000000ed0a18: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6c2e)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffe0008b6c2e-ffffffe0008b6c52: radix_tree_maybe_preload (STB_GLOBAL)
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
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52b10)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81a52b10-ffffffff81a52b2b: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0fc10)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81a0fc10-ffffffff81a0fc2b: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abef00)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81abef00-ffffffff81abef1b: radix_tree_maybe_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_maybe_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb3c0)
Location: lib/radix-tree.c:387
Inline: True
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81acb3c0-ffffffff81acb3e2: radix_tree_maybe_preload (STB_GLOBAL)
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
