# Function: <code>vchan_tx_desc_free</code>

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
int vchan_tx_desc_free(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81706b60)
Location: drivers/dma/virt-dma.c:49
Inline: False
```
**Symbols:**

```
ffffffff81706b60-ffffffff81706bfb: vchan_tx_desc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vchan_tx_desc_free(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81782410)
Location: drivers/dma/virt-dma.c:49
Inline: False
```
**Symbols:**

```
ffffffff81782410-ffffffff817824a8: vchan_tx_desc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vchan_tx_desc_free(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff818b8e60)
Location: drivers/dma/virt-dma.c:49
Inline: False
```
**Symbols:**

```
ffffffff818b8e60-ffffffff818b8f08: vchan_tx_desc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vchan_tx_desc_free(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a064f0)
Location: drivers/dma/virt-dma.c:49
Inline: False
```
**Symbols:**

```
ffffffff81a064f0-ffffffff81a06598: vchan_tx_desc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vchan_tx_desc_free(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a4f380)
Location: drivers/dma/virt-dma.c:49
Inline: False
```
**Symbols:**

```
ffffffff81a4f380-ffffffff81a4f428: vchan_tx_desc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vchan_tx_desc_free(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a9b020)
Location: drivers/dma/virt-dma.c:49
Inline: False
```
**Symbols:**

```
ffffffff81a9b020-ffffffff81a9b0c8: vchan_tx_desc_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int vchan_tx_desc_free(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffff8000107fe8e0)
Location: drivers/dma/virt-dma.c:49
Inline: False
```
**Symbols:**

```
ffff8000107fe8e0-ffff8000107fea08: vchan_tx_desc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vchan_tx_desc_free(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (c091f768)
Location: drivers/dma/virt-dma.c:49
Inline: False
```
**Symbols:**

```
c091f768-c091f814: vchan_tx_desc_free (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
