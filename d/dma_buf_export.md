# Function: <code>dma_buf_export</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff815a2ec0)
Location: drivers/dma-buf/dma-buf.c:284
Inline: False
```
**Symbols:**

```
ffffffff815a2ec0-ffffffff815a3123: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff815f9f30)
Location: drivers/dma-buf/dma-buf.c:331
Inline: False
```
**Symbols:**

```
ffffffff815f9f30-ffffffff815fa196: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81628200)
Location: drivers/dma-buf/dma-buf.c:331
Inline: False
```
**Symbols:**

```
ffffffff81628200-ffffffff81628463: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8163db30)
Location: drivers/dma-buf/dma-buf.c:389
Inline: False
```
**Symbols:**

```
ffffffff8163db30-ffffffff8163dd95: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816a68b0)
Location: drivers/dma-buf/dma-buf.c:389
Inline: False
```
**Symbols:**

```
ffffffff816a68b0-ffffffff816a6b15: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816e2b70)
Location: drivers/dma-buf/dma-buf.c:389
Inline: False
```
**Symbols:**

```
ffffffff816e2b70-ffffffff816e2db7: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81706020)
Location: drivers/dma-buf/dma-buf.c:389
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81706020-ffffffff8170624e: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:506
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81741d28-ffffffff81741d42: dma_buf_export.cold (STB_LOCAL)
ffffffff817410b0-ffffffff81741356: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81765390)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81765390-ffffffff81765603: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81824ce0)
Location: drivers/dma-buf/dma-buf.c:506
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/heap-helpers.c:heap_helper_export_dmabuf
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81824ce0-ffffffff81824fae: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff818356a0)
Location: drivers/dma-buf/dma-buf.c:519
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff818356a0-ffffffff81835974: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81818b00)
Location: drivers/dma-buf/dma-buf.c:520
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81818b00-ffffffff81818dd1: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:512
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81d0ba81-ffffffff81d0ba9a: dma_buf_export.cold (STB_LOCAL)
ffffffff818a2f20-ffffffff818a3205: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:492
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81ed48ac-ffffffff81ed48c5: dma_buf_export.cold (STB_LOCAL)
ffffffff819eccd0-ffffffff819ecfa1: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:613
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8209b6a8-ffffffff8209b6c1: dma_buf_export.cold (STB_LOCAL)
ffffffff81b69c50-ffffffff81b69f00: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:613
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8211c595-ffffffff8211c5ae: dma_buf_export.cold (STB_LOCAL)
ffffffff81bbd090-ffffffff81bbd343: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:608
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_export
```
**Symbols:**

```
ffffffff821fa431-ffffffff821fa44a: dma_buf_export.cold (STB_LOCAL)
ffffffff81c11780-ffffffff81c11a36: dma_buf_export (STB_GLOBAL)
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
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffff800010965430)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffff800010965430-ffff800010965678: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (c0a3c168)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
c0a3c168-c0a3c3ac: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (c000000000a1c7c0)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
c000000000a1c7c0-c000000000a1caf4: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffe0005d2380)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffe0005d2380-ffffffe0005d2580: dma_buf_export (STB_GLOBAL)
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
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81719a80)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81719a80-ffffffff81719cf3: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816f2ef0)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff816f2ef0-ffffffff816f3163: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81758850)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81758850-ffffffff81758ac3: dma_buf_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dma_buf *dma_buf_export(const struct dma_buf_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81773cd0)
Location: drivers/dma-buf/dma-buf.c:507
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81773cd0-ffffffff81773f43: dma_buf_export (STB_GLOBAL)
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
