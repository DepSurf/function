# Function: <code>trace_kmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b2802)
Location: include/trace/events/kmem.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff811eae49)
Location: include/trace/events/kmem.h:45
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_track_caller
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cc26b)
Location: include/trace/events/kmem.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff8120dea3)
Location: include/trace/events/kmem.h:45
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dc33f)
Location: include/trace/events/kmem.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff8121fee3)
Location: include/trace/events/kmem.h:45
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e6258)
Location: include/trace/events/kmem.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff8122bc24)
Location: include/trace/events/kmem.h:45
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fc498)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff81247354)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121d5f8)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff8126a296)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812305e8)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff8127eb34)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124060b)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff8129a91f)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff8124ebbb)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff812aa7df)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff8127d38b)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff812dca6b)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff81288d24)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff812e91a8)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff8128e3e4)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff812ef9a1)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff812ce31e)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff813389d5)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff8132c3bd)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff813abb03)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a1a46)
Location: include/trace/events/kmem.h:54
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d4d16)
Location: include/trace/events/kmem.h:54
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145b6b4)
Location: include/trace/events/kmem.h:54
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmalloc_large
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
In mm/slab_common.c (ffff8000102e6898)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffff80001034c6bc)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (c0509d44)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (c05502fc)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (c0000000003a6a98)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (c00000000042c22c)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffe0001fb9dc)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffe00023d7dc)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff8124720b)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff812a2dbf)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff8123a1bb)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff8129488f)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff81244fab)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff812a0bcf)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
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
In mm/slab_common.c (ffffffff8125499b)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/slub.c (ffffffff812b0d19)
Location: include/trace/events/kmem.h:46
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
```
</details>
</li>
</ul>

## Differences
