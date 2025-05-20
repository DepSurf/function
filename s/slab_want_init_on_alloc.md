# Function: <code>slab_want_init_on_alloc</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129ab7f)
Location: mm/slab.h:610
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aaa3f)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dccee)
Location: mm/slab.h:676
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e9692)
Location: mm/slab.h:598
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f0341)
Location: mm/slab.h:610
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
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
In mm/slub.c (ffffffff81338cce)
Location: mm/slab.h:606
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/core.c (ffffffff8133c0a0)
Location: mm/slab.h:606
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
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
In mm/slub.c (ffffffff813aa8e3)
Location: mm/slab.h:832
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/core.c (ffffffff813aed3f)
Location: mm/slab.h:832
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
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
In mm/slub.c (ffffffff8142ccca)
Location: mm/slab.h:844
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/core.c (ffffffff8142f290)
Location: mm/slab.h:844
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
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
In mm/slub.c (ffffffff814622da)
Location: mm/slab.h:843
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/core.c (ffffffff81464fdf)
Location: mm/slab.h:843
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
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
In mm/slub.c (ffffffff8145e7b3)
Location: mm/slab.h:631
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/core.c (ffffffff81493c26)
Location: mm/slab.h:631
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034c950)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c05502d4)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042c5dc)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d7bc)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a301f)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294af4)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a0e2f)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b0fad)
Location: mm/slab.h:674
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
</ul>

## Differences
