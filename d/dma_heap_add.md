# Function: <code>dma_heap_add</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dma_heap *dma_heap_add(const struct dma_heap_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-heap.c (0)
Location: drivers/dma-buf/dma-heap.c:193
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_create
```
**Symbols:**

```
ffffffff8182a089-ffffffff8182a108: dma_heap_add.cold (STB_LOCAL)
ffffffff81829e50-ffffffff8182a068: dma_heap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dma_heap *dma_heap_add(const struct dma_heap_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-heap.c (0)
Location: drivers/dma-buf/dma-heap.c:193
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_create
```
**Symbols:**

```
ffffffff81c161b6-ffffffff81c16235: dma_heap_add.cold (STB_LOCAL)
ffffffff8183a800-ffffffff8183aa18: dma_heap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dma_heap *dma_heap_add(const struct dma_heap_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-heap.c (0)
Location: drivers/dma-buf/dma-heap.c:217
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_create
```
**Symbols:**

```
ffffffff81c07ea4-ffffffff81c07f23: dma_heap_add.cold (STB_LOCAL)
ffffffff8181da60-ffffffff8181dc78: dma_heap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dma_heap *dma_heap_add(const struct dma_heap_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-heap.c (0)
Location: drivers/dma-buf/dma-heap.c:219
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_create
```
**Symbols:**

```
ffffffff81d0bba7-ffffffff81d0bc26: dma_heap_add.cold (STB_LOCAL)
ffffffff818a7ea0-ffffffff818a80b8: dma_heap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dma_heap *dma_heap_add(const struct dma_heap_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-heap.c (0)
Location: drivers/dma-buf/dma-heap.c:219
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_create
```
**Symbols:**

```
ffffffff81ed4a0e-ffffffff81ed4a7f: dma_heap_add.cold (STB_LOCAL)
ffffffff819f1bd0-ffffffff819f1df2: dma_heap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dma_heap *dma_heap_add(const struct dma_heap_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff81b6f8c0)
Location: drivers/dma-buf/dma-heap.c:219
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_create
```
**Symbols:**

```
ffffffff81b6f8c0-ffffffff81b6fb6c: dma_heap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dma_heap *dma_heap_add(const struct dma_heap_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff81bc31f0)
Location: drivers/dma-buf/dma-heap.c:219
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_create
```
**Symbols:**

```
ffffffff81bc31f0-ffffffff81bc349c: dma_heap_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dma_heap *dma_heap_add(const struct dma_heap_export_info *exp_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff81c17960)
Location: drivers/dma-buf/dma-heap.c:219
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_create
```
**Symbols:**

```
ffffffff81c17960-ffffffff81c17c3b: dma_heap_add (STB_GLOBAL)
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
