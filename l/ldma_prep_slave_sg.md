# Function: <code>ldma_prep_slave_sg</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *ldma_prep_slave_sg(struct dma_chan *chan, struct scatterlist *sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1157
Inline: False
```
**Symbols:**

```
ffffffff81708610-ffffffff81708985: ldma_prep_slave_sg (STB_LOCAL)
ffffffff81bf603b-ffffffff81bf609b: ldma_prep_slave_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *ldma_prep_slave_sg(struct dma_chan *chan, struct scatterlist *sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1157
Inline: False
```
**Symbols:**

```
ffffffff81784430-ffffffff817847a2: ldma_prep_slave_sg (STB_LOCAL)
ffffffff81cf417a-ffffffff81cf41da: ldma_prep_slave_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *ldma_prep_slave_sg(struct dma_chan *chan, struct scatterlist *sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1157
Inline: False
```
**Symbols:**

```
ffffffff818bb100-ffffffff818bb455: ldma_prep_slave_sg (STB_LOCAL)
ffffffff81ebc2da-ffffffff81ebc332: ldma_prep_slave_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dma_async_tx_descriptor *ldma_prep_slave_sg(struct dma_chan *chan, struct scatterlist *sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a09bc0)
Location: drivers/dma/lgm/lgm-dma.c:1157
Inline: False
```
**Symbols:**

```
ffffffff81a09bc0-ffffffff81a09f64: ldma_prep_slave_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dma_async_tx_descriptor *ldma_prep_slave_sg(struct dma_chan *chan, struct scatterlist *sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a52a50)
Location: drivers/dma/lgm/lgm-dma.c:1157
Inline: False
```
**Symbols:**

```
ffffffff81a52a50-ffffffff81a52df4: ldma_prep_slave_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dma_async_tx_descriptor *ldma_prep_slave_sg(struct dma_chan *chan, struct scatterlist *sgl, unsigned int sglen, enum dma_transfer_direction dir, long unsigned int flags, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9e7a0)
Location: drivers/dma/lgm/lgm-dma.c:1157
Inline: False
```
**Symbols:**

```
ffffffff81a9e7a0-ffffffff81a9eba2: ldma_prep_slave_sg (STB_LOCAL)
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
