# Function: <code>dma_alloc_from_global_coherent</code>

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
void *dma_alloc_from_global_coherent(ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff811237e0)
Location: kernel/dma/coherent.c:194
Inline: False
```
**Symbols:**

```
ffffffff811237e0-ffffffff81123806: dma_alloc_from_global_coherent (STB_GLOBAL)
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
void *dma_alloc_from_global_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195d08)
Location: kernel/dma/coherent.c:183
Inline: False
```
**Symbols:**

```
ffff800010195d08-ffff800010195d5c: dma_alloc_from_global_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *dma_alloc_from_global_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e269c)
Location: kernel/dma/coherent.c:183
Inline: False
```
**Symbols:**

```
c03e269c-c03e26e0: dma_alloc_from_global_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *dma_alloc_from_global_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f5e70)
Location: kernel/dma/coherent.c:183
Inline: False
```
**Symbols:**

```
c0000000001f5e70-c0000000001f5ea8: dma_alloc_from_global_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *dma_alloc_from_global_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe000127802)
Location: kernel/dma/coherent.c:183
Inline: False
```
**Symbols:**

```
ffffffe000127802-ffffffe000127848: dma_alloc_from_global_coherent (STB_GLOBAL)
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
