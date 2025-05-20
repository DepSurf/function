# Function: <code>vchan_tx_submit</code>

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
dma_cookie_t vchan_tx_submit(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81706a90)
Location: drivers/dma/virt-dma.c:19
Inline: False
```
**Symbols:**

```
ffffffff81706a90-ffffffff81706b53: vchan_tx_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
dma_cookie_t vchan_tx_submit(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81782350)
Location: drivers/dma/virt-dma.c:19
Inline: False
```
**Symbols:**

```
ffffffff81782350-ffffffff81782410: vchan_tx_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
dma_cookie_t vchan_tx_submit(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff818b8d70)
Location: drivers/dma/virt-dma.c:19
Inline: False
```
**Symbols:**

```
ffffffff818b8d70-ffffffff818b8e54: vchan_tx_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
dma_cookie_t vchan_tx_submit(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a063f0)
Location: drivers/dma/virt-dma.c:19
Inline: False
```
**Symbols:**

```
ffffffff81a063f0-ffffffff81a064d4: vchan_tx_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
dma_cookie_t vchan_tx_submit(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a4f280)
Location: drivers/dma/virt-dma.c:19
Inline: False
```
**Symbols:**

```
ffffffff81a4f280-ffffffff81a4f364: vchan_tx_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
dma_cookie_t vchan_tx_submit(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a9af20)
Location: drivers/dma/virt-dma.c:19
Inline: False
```
**Symbols:**

```
ffffffff81a9af20-ffffffff81a9b004: vchan_tx_submit (STB_GLOBAL)
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
dma_cookie_t vchan_tx_submit(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffff8000107fe560)
Location: drivers/dma/virt-dma.c:19
Inline: False
```
**Symbols:**

```
ffff8000107fe560-ffff8000107fe694: vchan_tx_submit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
dma_cookie_t vchan_tx_submit(struct dma_async_tx_descriptor *tx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (c091f6a0)
Location: drivers/dma/virt-dma.c:19
Inline: False
```
**Symbols:**

```
c091f6a0-c091f768: vchan_tx_submit (STB_GLOBAL)
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
