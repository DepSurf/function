# Function: <code>__dma_alloc_from_pool</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__dma_alloc_from_pool(struct device *dev, size_t size, struct gen_pool *pool, void **cpu_addr, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113f7e0)
Location: kernel/dma/pool.c:244
Inline: False
Direct callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
**Symbols:**

```
ffffffff8113f7e0-ffffffff8113f8c5: __dma_alloc_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__dma_alloc_from_pool(struct device *dev, size_t size, struct gen_pool *pool, void **cpu_addr, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113add0)
Location: kernel/dma/pool.c:240
Inline: False
Direct callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
**Symbols:**

```
ffffffff8113add0-ffffffff8113aeb5: __dma_alloc_from_pool (STB_LOCAL)
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
In kernel/dma/pool.c (ffffffff8113c26b)
Location: kernel/dma/pool.c:240
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
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
In kernel/dma/pool.c (ffffffff8115f38e)
Location: kernel/dma/pool.c:240
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
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
In kernel/dma/pool.c (ffffffff811895ae)
Location: kernel/dma/pool.c:240
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
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
In kernel/dma/pool.c (ffffffff811c59ce)
Location: kernel/dma/pool.c:240
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *__dma_alloc_from_pool(struct device *dev, size_t size, struct gen_pool *pool, void **cpu_addr, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff811d8440)
Location: kernel/dma/pool.c:240
Inline: False
Direct callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
**Symbols:**

```
ffffffff811d8440-ffffffff811d852d: __dma_alloc_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *__dma_alloc_from_pool(struct device *dev, size_t size, struct gen_pool *pool, void **cpu_addr, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff811edf50)
Location: kernel/dma/pool.c:240
Inline: False
Direct callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
**Symbols:**

```
ffffffff811edf50-ffffffff811ee03d: __dma_alloc_from_pool (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
