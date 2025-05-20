# Function: <code>dma_unmap_resource</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dma_unmap_resource(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137cd0)
Location: kernel/dma/mapping.c:246
Inline: True
```
**Symbols:**

```
ffffffff81137cd0-ffffffff81137d0e: dma_unmap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dma_unmap_resource(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138d00)
Location: kernel/dma/mapping.c:248
Inline: True
```
**Symbols:**

```
ffffffff81138d00-ffffffff81138d3e: dma_unmap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_unmap_resource(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b080)
Location: kernel/dma/mapping.c:313
Inline: False
```
**Symbols:**

```
ffffffff8115b080-ffffffff8115b0be: dma_unmap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_unmap_resource(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811849a0)
Location: kernel/dma/mapping.c:309
Inline: False
```
**Symbols:**

```
ffffffff811849a0-ffffffff81184a00: dma_unmap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_unmap_resource(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811bffe0)
Location: kernel/dma/mapping.c:316
Inline: False
```
**Symbols:**

```
ffffffff811bffe0-ffffffff811c0040: dma_unmap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_unmap_resource(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d2ac0)
Location: kernel/dma/mapping.c:320
Inline: False
```
**Symbols:**

```
ffffffff811d2ac0-ffffffff811d2b20: dma_unmap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_unmap_resource(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e7740)
Location: kernel/dma/mapping.c:320
Inline: False
```
**Symbols:**

```
ffffffff811e7740-ffffffff811e77a0: dma_unmap_resource (STB_GLOBAL)
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
