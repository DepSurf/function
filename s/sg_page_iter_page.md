# Function: <code>sg_page_iter_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa464)
Location: include/linux/scatterlist.h:316
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814414cd)
Location: include/linux/scatterlist.h:341
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e6ed)
Location: include/linux/scatterlist.h:341
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814638fa)
Location: include/linux/scatterlist.h:343
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f89a)
Location: include/linux/scatterlist.h:353
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c457a)
Location: include/linux/scatterlist.h:367
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8c6d)
Location: include/linux/scatterlist.h:367
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504b20)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (ffffffff81522c60)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (ffffffff81585c53)
Location: include/linux/scatterlist.h:396
Inline: True
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
In lib/scatterlist.c (ffffffff815a2d33)
Location: include/linux/scatterlist.h:396
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183ac04)
Location: include/linux/scatterlist.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_do_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
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
In lib/scatterlist.c (ffffffff815a9c63)
Location: include/linux/scatterlist.h:396
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181dec7)
Location: include/linux/scatterlist.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
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
In lib/scatterlist.c (ffffffff81612dbf)
Location: include/linux/scatterlist.h:434
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8297)
Location: include/linux/scatterlist.h:434
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
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
In lib/scatterlist.c (ffffffff816df3f0)
Location: include/linux/scatterlist.h:451
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2004)
Location: include/linux/scatterlist.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
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
In lib/scatterlist.c (ffffffff817cf620)
Location: include/linux/scatterlist.h:520
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b6fda1)
Location: include/linux/scatterlist.h:520
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
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
In lib/scatterlist.c (ffffffff8180dad0)
Location: include/linux/scatterlist.h:580
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc36d1)
Location: include/linux/scatterlist.h:580
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
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
In lib/scatterlist.c (ffffffff81853780)
Location: include/linux/scatterlist.h:580
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c17e71)
Location: include/linux/scatterlist.h:580
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c813df)
Location: include/linux/scatterlist.h:580
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_clflush_sg
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cac290)
Location: include/linux/scatterlist.h:580
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_prime_sg_to_page_array
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
In lib/scatterlist.c (ffff80001062c7f8)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (c07d3274)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (c0000000007cf3a4)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (ffffffe00045c922)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (ffffffff8151b240)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (ffffffff8150b530)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (ffffffff815172d0)
Location: include/linux/scatterlist.h:382
Inline: True
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
In lib/scatterlist.c (ffffffff81530a89)
Location: include/linux/scatterlist.h:382
Inline: True
```
</details>
</li>
</ul>

## Differences
