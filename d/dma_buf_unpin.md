# Function: <code>dma_buf_unpin</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8182567c)
Location: drivers/dma-buf/dma-buf.c:833
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
**Symbols:**

```
ffffffff818247a0-ffffffff818247c1: dma_buf_unpin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8183605c)
Location: drivers/dma-buf/dma-buf.c:846
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
**Symbols:**

```
ffffffff81835120-ffffffff81835141: dma_buf_unpin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81818340)
Location: drivers/dma-buf/dma-buf.c:899
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
```
**Symbols:**

```
ffffffff81818340-ffffffff8181836c: dma_buf_unpin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff818a3c6c)
Location: drivers/dma-buf/dma-buf.c:903
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
```
**Symbols:**

```
ffffffff818a29c0-ffffffff818a29ec: dma_buf_unpin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff819ed7c8)
Location: drivers/dma-buf/dma-buf.c:895
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
```
**Symbols:**

```
ffffffff819ec210-ffffffff819ec24c: dma_buf_unpin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81b68ec0)
Location: drivers/dma-buf/dma-buf.c:1069
Inline: False
```
**Symbols:**

```
ffffffff81b68ec0-ffffffff81b68efc: dma_buf_unpin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81bbc2e0)
Location: drivers/dma-buf/dma-buf.c:1069
Inline: False
```
**Symbols:**

```
ffffffff81bbc2e0-ffffffff81bbc31c: dma_buf_unpin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_buf_unpin(struct dma_buf_attachment *attach);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81c10ae0)
Location: drivers/dma-buf/dma-buf.c:1064
Inline: False
```
**Symbols:**

```
ffffffff81c10ae0-ffffffff81c10b1c: dma_buf_unpin (STB_GLOBAL)
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
