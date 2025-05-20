# Function: <code>kmem_cache_free_bulk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *orig_s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ec0d0)
Location: mm/slub.c:2890
Inline: False
Direct callers:
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff811ec0d0-ffffffff811ec37f: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120b340)
Location: mm/slub.c:3055
Inline: False
Direct callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff8120b340-ffffffff8120b62f: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121d380)
Location: mm/slub.c:3077
Inline: False
Direct callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff8121d380-ffffffff8121d660: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81228c00)
Location: mm/slub.c:3074
Inline: True
Direct callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff81228c00-ffffffff81228ecc: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81242870)
Location: mm/slub.c:3087
Inline: True
Direct callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff81242870-ffffffff81242b7f: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81268490)
Location: mm/slub.c:3068
Inline: True
Direct callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff81268490-ffffffff8126879c: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127cf30)
Location: mm/slub.c:3118
Inline: True
Direct callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff8127cf30-ffffffff8127d240: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81299480)
Location: mm/slub.c:3129
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff81299480-ffffffff812998c9: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff8129b9c3-ffffffff8129b9d6: kmem_cache_free_bulk.cold (STB_LOCAL)
ffffffff812998d0-ffffffff812998e9: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a92f0)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff812a92f0-ffffffff812a97a4: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812de690)
Location: mm/slub.c:3185
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - fs/io_uring.c:io_submit_sqes
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff812de690-ffffffff812de7c7: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff812de7d0-ffffffff812de7e8: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812ea230)
Location: mm/slub.c:3256
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_req_free_batch
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff812ea230-ffffffff812ea55b: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff812ea560-ffffffff812ea5a5: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812f1980)
Location: mm/slub.c:3288
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - fs/io_uring.c:io_ring_ctx_free
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__kfree_skb_defer
```
**Symbols:**

```
ffffffff812f1980-ffffffff812f1cdb: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff812f1ce0-ffffffff812f1d25: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3620
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - fs/io_uring.c:io_ring_ctx_free
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__kfree_skb_defer
```
**Symbols:**

```
ffffffff8133a730-ffffffff8133aa6c: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff81cc1ad6-ffffffff81cc1ba6: kmem_cache_free_bulk.part.0.cold (STB_LOCAL)
ffffffff81cc1ba6-ffffffff81cc1c13: kmem_cache_free_bulk.cold (STB_LOCAL)
ffffffff8133aa70-ffffffff8133ac7f: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3670
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__kfree_skb_defer
```
**Symbols:**

```
ffffffff813ac680-ffffffff813acb1d: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff81e73ffc-ffffffff81e74092: kmem_cache_free_bulk.part.0.cold (STB_LOCAL)
ffffffff81e74092-ffffffff81e740fd: kmem_cache_free_bulk.cold (STB_LOCAL)
ffffffff813acb20-ffffffff813acd92: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8142cb78)
Location: mm/slub.c:3893
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - mm/slub.c:__kmem_cache_alloc_bulk
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__kfree_skb_defer
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mt_destroy_walk
  - lib/maple_tree.c:mt_destroy_walk
  - lib/maple_tree.c:mt_free_walk
  - lib/maple_tree.c:mt_free_walk
```
**Symbols:**

```
ffffffff8142c640-ffffffff8142c921: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff8142c940-ffffffff8142c96a: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81462187)
Location: mm/slub.c:3907
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
Direct callers:
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_list_reason
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mt_free_walk
  - lib/maple_tree.c:mt_free_walk
```
**Symbols:**

```
ffffffff81461c00-ffffffff81461f00: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff81461f10-ffffffff81461f3a: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8145e030)
Location: mm/slub.c:4514
Inline: True
Direct callers:
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - net/core/skbuff.c:napi_skb_cache_put
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_list_reason
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mt_free_walk
  - lib/maple_tree.c:mt_free_walk
```
**Symbols:**

```
ffffffff8145e030-ffffffff8145e36e: kmem_cache_free_bulk.part.0 (STB_LOCAL)
ffffffff8145e380-ffffffff8145e3aa: kmem_cache_free_bulk (STB_GLOBAL)
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
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034ae20)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffff80001034ae20-ffff80001034b27c: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054e420)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
c054e420-c054e99c: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042a180)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
c00000000042a180-c00000000042a7b8: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023c4e8)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffe00023c4e8-ffffffe00023c91e: kmem_cache_free_bulk (STB_GLOBAL)
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
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a18d0)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff812a18d0-ffffffff812a1d84: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812933b0)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff812933b0-ffffffff81293864: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129f6e0)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff8129f6e0-ffffffff8129fb94: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache *s, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812af810)
Location: mm/slub.c:3127
Inline: True
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
```
**Symbols:**

```
ffffffff812af810-ffffffff812afcd3: kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kmem_cache *s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kmem_cache *orig_s</code>
</li>
</ul>
</details>
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
