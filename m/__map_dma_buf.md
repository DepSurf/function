# Function: <code>__map_dma_buf</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8181886e)
Location: drivers/dma-buf/dma-buf.c:684
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
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
In drivers/dma-buf/dma-buf.c (ffffffff818a3488)
Location: drivers/dma-buf/dma-buf.c:688
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sg_table *__map_dma_buf(struct dma_buf_attachment *attach, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff819ec5c0)
Location: drivers/dma-buf/dma-buf.c:668
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
**Symbols:**

```
ffffffff819ec5c0-ffffffff819ec65b: __map_dma_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sg_table *__map_dma_buf(struct dma_buf_attachment *attach, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81b693f0)
Location: drivers/dma-buf/dma-buf.c:782
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
**Symbols:**

```
ffffffff81b693f0-ffffffff81b69488: __map_dma_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sg_table *__map_dma_buf(struct dma_buf_attachment *attach, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81bbc830)
Location: drivers/dma-buf/dma-buf.c:782
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
**Symbols:**

```
ffffffff81bbc830-ffffffff81bbc8c8: __map_dma_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sg_table *__map_dma_buf(struct dma_buf_attachment *attach, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81c10f80)
Location: drivers/dma-buf/dma-buf.c:777
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
**Symbols:**

```
ffffffff81c10f80-ffffffff81c11018: __map_dma_buf (STB_LOCAL)
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
