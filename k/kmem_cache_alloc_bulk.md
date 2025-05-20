# Function: <code>kmem_cache_alloc_bulk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eb5c0)
Location: mm/slub.c:2912
Inline: False
```
**Symbols:**

```
ffffffff811eb5c0-ffffffff811eb7c9: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120b9b0)
Location: mm/slub.c:3073
Inline: False
```
**Symbols:**

```
ffffffff8120b9b0-ffffffff8120bb54: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121d9e0)
Location: mm/slub.c:3095
Inline: False
```
**Symbols:**

```
ffffffff8121d9e0-ffffffff8121db84: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81229300)
Location: mm/slub.c:3092
Inline: False
```
**Symbols:**

```
ffffffff81229300-ffffffff81229499: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81245890)
Location: mm/slub.c:3105
Inline: False
```
**Symbols:**

```
ffffffff81245890-ffffffff81245a38: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81267360)
Location: mm/slub.c:3086
Inline: False
```
**Symbols:**

```
ffffffff81267360-ffffffff81267519: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127c030)
Location: mm/slub.c:3136
Inline: False
```
**Symbols:**

```
ffffffff8127c030-ffffffff8127c1e9: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81297c00)
Location: mm/slub.c:3147
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81297c00-ffffffff81297dea: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a7a00)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
ffffffff812a7a00-ffffffff812a7c4a: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dcf20)
Location: mm/slub.c:3203
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff812dcf20-ffffffff812dd159: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e9830)
Location: mm/slub.c:3275
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff812e9830-ffffffff812e9a7a: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812efae0)
Location: mm/slub.c:3307
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_submit_sqes
  - net/core/skbuff.c:napi_skb_cache_get
  - net/core/xdp.c:xdp_alloc_skb_bulk
```
**Symbols:**

```
ffffffff812efae0-ffffffff812efd61: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81337e00)
Location: mm/slub.c:3639
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_submit_sqes
  - net/core/skbuff.c:napi_skb_cache_get
  - net/core/xdp.c:xdp_alloc_skb_bulk
```
**Symbols:**

```
ffffffff81337e00-ffffffff81338180: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a9360)
Location: mm/slub.c:3689
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - io_uring/io_uring.c:io_submit_sqes
  - net/core/skbuff.c:napi_skb_cache_get
  - net/core/xdp.c:xdp_alloc_skb_bulk
```
**Symbols:**

```
ffffffff813a9360-ffffffff813a96ca: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142cbc0)
Location: mm/slub.c:4012
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - io_uring/io_uring.c:__io_alloc_req_refill
  - net/core/skbuff.c:napi_skb_cache_get
  - net/core/xdp.c:xdp_alloc_skb_bulk
  - lib/maple_tree.c:mas_alloc_nodes
  - lib/maple_tree.c:mas_alloc_nodes
```
**Symbols:**

```
ffffffff8142cbc0-ffffffff8142cd8d: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814621d0)
Location: mm/slub.c:4027
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - io_uring/io_uring.c:__io_alloc_req_refill
  - net/core/skbuff.c:napi_skb_cache_get
  - net/core/xdp.c:xdp_alloc_skb_bulk
  - lib/maple_tree.c:mas_alloc_nodes
```
**Symbols:**

```
ffffffff814621d0-ffffffff8146239f: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145e710)
Location: mm/slub.c:4634
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - io_uring/io_uring.c:__io_alloc_req_refill
  - io_uring/kbuf.c:io_refill_buffer_cache
  - net/core/skbuff.c:napi_skb_cache_get
  - net/core/xdp.c:xdp_alloc_skb_bulk
  - lib/maple_tree.c:mas_alloc_nodes
```
**Symbols:**

```
ffffffff8145e710-ffffffff8145e8d6: kmem_cache_alloc_bulk (STB_GLOBAL)
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
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010348e68)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
ffff800010348e68-ffff8000103490f4: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054c924)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
c054c924-c054cba8: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000427980)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
c000000000427980-c000000000427d28: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023a6ae)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
ffffffe00023a6ae-ffffffe00023a93a: kmem_cache_alloc_bulk (STB_GLOBAL)
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
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129ffe0)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
ffffffff8129ffe0-ffffffff812a022a: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81291b00)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
ffffffff81291b00-ffffffff81291d38: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129ddf0)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
ffffffff8129ddf0-ffffffff8129e03a: kmem_cache_alloc_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kmem_cache_alloc_bulk(struct kmem_cache *s, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ade80)
Location: mm/slub.c:3145
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - fs/io_uring.c:io_get_req
```
**Symbols:**

```
ffffffff812ade80-ffffffff812ae0ad: kmem_cache_alloc_bulk (STB_GLOBAL)
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
