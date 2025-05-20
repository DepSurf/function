# Function: <code>__dma_alloc_from_coherent</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__dma_alloc_from_coherent(struct dma_coherent_mem *mem, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff811236e0)
Location: kernel/dma/coherent.c:138
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_alloc_from_global_coherent
  - kernel/dma/coherent.c:dma_alloc_from_dev_coherent
```
**Symbols:**

```
ffffffff811236e0-ffffffff81123798: __dma_alloc_from_coherent (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *__dma_alloc_from_coherent(struct device *dev, struct dma_coherent_mem *mem, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195a58)
Location: kernel/dma/coherent.c:126
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_alloc_from_global_coherent
  - kernel/dma/coherent.c:dma_alloc_from_dev_coherent
```
**Symbols:**

```
ffff800010195a58-ffff800010195bc8: __dma_alloc_from_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__dma_alloc_from_coherent(struct device *dev, struct dma_coherent_mem *mem, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e24a8)
Location: kernel/dma/coherent.c:126
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_alloc_from_global_coherent
  - kernel/dma/coherent.c:dma_alloc_from_dev_coherent
```
**Symbols:**

```
c03e24a8-c03e257c: __dma_alloc_from_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__dma_alloc_from_coherent(struct device *dev, struct dma_coherent_mem *mem, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f5b50)
Location: kernel/dma/coherent.c:126
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_alloc_from_global_coherent
  - kernel/dma/coherent.c:dma_alloc_from_dev_coherent
```
**Symbols:**

```
c0000000001f5b50-c0000000001f5cd4: __dma_alloc_from_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__dma_alloc_from_coherent(struct device *dev, struct dma_coherent_mem *mem, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe0001274f2)
Location: kernel/dma/coherent.c:126
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_alloc_from_global_coherent
  - kernel/dma/coherent.c:dma_alloc_from_dev_coherent
```
**Symbols:**

```
ffffffe0001274f2-ffffffe0001275b6: __dma_alloc_from_coherent (STB_LOCAL)
```
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
