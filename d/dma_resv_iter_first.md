# Function: <code>dma_resv_iter_first</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dma_fence *dma_resv_iter_first(struct dma_resv_iter *cursor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff819f133f)
Location: drivers/dma-buf/dma-resv.c:457
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_describe
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
**Symbols:**

```
ffffffff819f05a0-ffffffff819f05d4: dma_resv_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dma_fence *dma_resv_iter_first(struct dma_resv_iter *cursor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81b6ef8f)
Location: drivers/dma-buf/dma-resv.c:463
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_describe
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
**Symbols:**

```
ffffffff81b6e0d0-ffffffff81b6e104: dma_resv_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dma_fence *dma_resv_iter_first(struct dma_resv_iter *cursor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2855)
Location: drivers/dma-buf/dma-resv.c:463
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_describe
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
**Symbols:**

```
ffffffff81bc18e0-ffffffff81bc1914: dma_resv_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dma_fence *dma_resv_iter_first(struct dma_resv_iter *cursor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81c16fe5)
Location: drivers/dma-buf/dma-resv.c:463
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_describe
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
**Symbols:**

```
ffffffff81c16070-ffffffff81c160a4: dma_resv_iter_first (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
