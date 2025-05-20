# Function: <code>dma_vmap_noncontiguous</code>

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
void *dma_vmap_noncontiguous(struct device *dev, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138b20)
Location: kernel/dma/mapping.c:610
Inline: False
```
**Symbols:**

```
ffffffff81138b20-ffffffff81138b9e: dma_vmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *dma_vmap_noncontiguous(struct device *dev, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115ba30)
Location: kernel/dma/mapping.c:675
Inline: False
```
**Symbols:**

```
ffffffff8115ba30-ffffffff8115baae: dma_vmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dma_vmap_noncontiguous(struct device *dev, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185560)
Location: kernel/dma/mapping.c:669
Inline: False
```
**Symbols:**

```
ffffffff81185560-ffffffff811855f9: dma_vmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dma_vmap_noncontiguous(struct device *dev, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0dc0)
Location: kernel/dma/mapping.c:688
Inline: False
```
**Symbols:**

```
ffffffff811c0dc0-ffffffff811c0e59: dma_vmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dma_vmap_noncontiguous(struct device *dev, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d38b0)
Location: kernel/dma/mapping.c:692
Inline: False
```
**Symbols:**

```
ffffffff811d38b0-ffffffff811d3949: dma_vmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dma_vmap_noncontiguous(struct device *dev, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8550)
Location: kernel/dma/mapping.c:692
Inline: False
```
**Symbols:**

```
ffffffff811e8550-ffffffff811e85e9: dma_vmap_noncontiguous (STB_GLOBAL)
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
