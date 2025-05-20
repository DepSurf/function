# Function: <code>pool_alloc_page</code>

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
In mm/dmapool.c (ffffffff811d9649)
Location: mm/dmapool.c:222
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff811f7802)
Location: mm/dmapool.c:222
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff812081b2)
Location: mm/dmapool.c:222
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff812138a9)
Location: mm/dmapool.c:222
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff8122e429)
Location: mm/dmapool.c:222
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff81251278)
Location: mm/dmapool.c:222
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff81265680)
Location: mm/dmapool.c:222
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff812805ec)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff8129001c)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_page *pool_alloc_page(struct dma_pool *pool, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff812c2b90)
Location: mm/dmapool.c:219
Inline: False
Direct callers:
  - mm/dmapool.c:dma_pool_alloc
```
**Symbols:**

```
ffffffff812c2b90-ffffffff812c2c71: pool_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_page *pool_alloc_page(struct dma_pool *pool, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff812ce960)
Location: mm/dmapool.c:219
Inline: False
Direct callers:
  - mm/dmapool.c:dma_pool_alloc
```
**Symbols:**

```
ffffffff812ce960-ffffffff812cea41: pool_alloc_page (STB_LOCAL)
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
In mm/dmapool.c (ffffffff812d5733)
Location: mm/dmapool.c:220
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8131b550)
Location: mm/dmapool.c:219
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81386d5d)
Location: mm/dmapool.c:219
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff81404c2d)
Location: mm/dmapool.c:219
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff81438195)
Location: mm/dmapool.c:334
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff81471af6)
Location: mm/dmapool.c:334
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffff80001032d3f0)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (c0542ef0)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (c000000000404a3c)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffe00022b798)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff812885fc)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff8127a44c)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff8128640c)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
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
In mm/dmapool.c (ffffffff81296200)
Location: mm/dmapool.c:221
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
