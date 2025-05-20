# Function: <code>__dma_map_sg_attrs</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b0c0)
Location: kernel/dma/mapping.c:180
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_sgtable
  - kernel/dma/mapping.c:dma_map_sg_attrs
```
**Symbols:**

```
ffffffff8115b0c0-ffffffff8115b12a: __dma_map_sg_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184a00)
Location: kernel/dma/mapping.c:180
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_sgtable
  - kernel/dma/mapping.c:dma_map_sg_attrs
```
**Symbols:**

```
ffffffff81184a00-ffffffff81184aa8: __dma_map_sg_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0050)
Location: kernel/dma/mapping.c:182
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_sgtable
  - kernel/dma/mapping.c:dma_map_sg_attrs
```
**Symbols:**

```
ffffffff811c0050-ffffffff811c0116: __dma_map_sg_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d2b30)
Location: kernel/dma/mapping.c:186
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_sgtable
  - kernel/dma/mapping.c:dma_map_sg_attrs
```
**Symbols:**

```
ffffffff811d2b30-ffffffff811d2bf6: __dma_map_sg_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e77b0)
Location: kernel/dma/mapping.c:186
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_sgtable
  - kernel/dma/mapping.c:dma_map_sg_attrs
```
**Symbols:**

```
ffffffff811e77b0-ffffffff811e7876: __dma_map_sg_attrs (STB_LOCAL)
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
