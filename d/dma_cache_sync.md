# Function: <code>dma_cache_sync</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811180b0)
Location: kernel/dma/mapping.c:347
Inline: True
```
**Symbols:**

```
ffffffff811180b0-ffffffff811180fd: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81122440)
Location: kernel/dma/mapping.c:381
Inline: True
```
**Symbols:**

```
ffffffff81122440-ffffffff8112247e: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112ead0)
Location: kernel/dma/mapping.c:401
Inline: True
```
**Symbols:**

```
ffffffff8112ead0-ffffffff8112eb0e: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d440)
Location: kernel/dma/mapping.c:372
Inline: True
```
**Symbols:**

```
ffffffff8113d440-ffffffff8113d47e: dma_cache_sync (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193f70)
Location: kernel/dma/mapping.c:401
Inline: True
```
**Symbols:**

```
ffff800010193f70-ffff800010193fdc: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e12e4)
Location: kernel/dma/mapping.c:401
Inline: True
```
**Symbols:**

```
c03e12e4-c03e133c: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f3c30)
Location: kernel/dma/mapping.c:401
Inline: False
```
**Symbols:**

```
c0000000001f3c30-c0000000001f3c90: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe000126294)
Location: kernel/dma/mapping.c:401
Inline: True
```
**Symbols:**

```
ffffffe000126294-ffffffe0001262e8: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811270b0)
Location: kernel/dma/mapping.c:401
Inline: True
```
**Symbols:**

```
ffffffff811270b0-ffffffff811270ee: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119b10)
Location: kernel/dma/mapping.c:401
Inline: True
```
**Symbols:**

```
ffffffff81119b10-ffffffff81119b4e: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124fa0)
Location: kernel/dma/mapping.c:401
Inline: True
```
**Symbols:**

```
ffffffff81124fa0-ffffffff81124fde: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dma_cache_sync(struct device *dev, void *vaddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811315e0)
Location: kernel/dma/mapping.c:401
Inline: True
```
**Symbols:**

```
ffffffff811315e0-ffffffff8113161e: dma_cache_sync (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
