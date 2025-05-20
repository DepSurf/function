# Function: <code>dma_alloc_noncontiguous</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sg_table *dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811389a0)
Location: kernel/dma/mapping.c:566
Inline: False
```
**Symbols:**

```
ffffffff811389a0-ffffffff81138b12: dma_alloc_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sg_table *dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b880)
Location: kernel/dma/mapping.c:631
Inline: False
```
**Symbols:**

```
ffffffff8115b880-ffffffff8115ba30: dma_alloc_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sg_table *dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811853c0)
Location: kernel/dma/mapping.c:625
Inline: False
```
**Symbols:**

```
ffffffff811853c0-ffffffff8118555f: dma_alloc_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sg_table *dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0bf0)
Location: kernel/dma/mapping.c:642
Inline: False
```
**Symbols:**

```
ffffffff811c0bf0-ffffffff811c0da9: dma_alloc_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sg_table *dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d36e0)
Location: kernel/dma/mapping.c:646
Inline: False
```
**Symbols:**

```
ffffffff811d36e0-ffffffff811d3899: dma_alloc_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sg_table *dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8360)
Location: kernel/dma/mapping.c:646
Inline: False
```
**Symbols:**

```
ffffffff811e8360-ffffffff811e853f: dma_alloc_noncontiguous (STB_GLOBAL)
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
