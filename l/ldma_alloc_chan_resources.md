# Function: <code>ldma_alloc_chan_resources</code>

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
int ldma_alloc_chan_resources(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1269
Inline: False
```
**Symbols:**

```
ffffffff81707ab0-ffffffff81707b2c: ldma_alloc_chan_resources (STB_LOCAL)
ffffffff81bf6022-ffffffff81bf603b: ldma_alloc_chan_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ldma_alloc_chan_resources(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1269
Inline: False
```
**Symbols:**

```
ffffffff81783380-ffffffff817833fc: ldma_alloc_chan_resources (STB_LOCAL)
ffffffff81cf4033-ffffffff81cf404c: ldma_alloc_chan_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ldma_alloc_chan_resources(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1269
Inline: False
```
**Symbols:**

```
ffffffff818b9f70-ffffffff818ba019: ldma_alloc_chan_resources (STB_LOCAL)
ffffffff81ebc195-ffffffff81ebc1ae: ldma_alloc_chan_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ldma_alloc_chan_resources(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a088e0)
Location: drivers/dma/lgm/lgm-dma.c:1269
Inline: False
```
**Symbols:**

```
ffffffff81a088e0-ffffffff81a0899e: ldma_alloc_chan_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ldma_alloc_chan_resources(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a51760)
Location: drivers/dma/lgm/lgm-dma.c:1269
Inline: False
```
**Symbols:**

```
ffffffff81a51760-ffffffff81a5181e: ldma_alloc_chan_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ldma_alloc_chan_resources(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d4b0)
Location: drivers/dma/lgm/lgm-dma.c:1269
Inline: False
```
**Symbols:**

```
ffffffff81a9d4b0-ffffffff81a9d56e: ldma_alloc_chan_resources (STB_LOCAL)
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
