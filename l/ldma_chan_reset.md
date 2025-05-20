# Function: <code>ldma_chan_reset</code>

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
int ldma_chan_reset(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff817079d0)
Location: drivers/dma/lgm/lgm-dma.c:694
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
```
**Symbols:**

```
ffffffff817079d0-ffffffff81707aab: ldma_chan_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ldma_chan_reset(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff817832a0)
Location: drivers/dma/lgm/lgm-dma.c:694
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
```
**Symbols:**

```
ffffffff817832a0-ffffffff8178337b: ldma_chan_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ldma_chan_reset(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff818b9e70)
Location: drivers/dma/lgm/lgm-dma.c:694
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
```
**Symbols:**

```
ffffffff818b9e70-ffffffff818b9f63: ldma_chan_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ldma_chan_reset(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a087d0)
Location: drivers/dma/lgm/lgm-dma.c:694
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
```
**Symbols:**

```
ffffffff81a087d0-ffffffff81a088c3: ldma_chan_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ldma_chan_reset(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a515c0)
Location: drivers/dma/lgm/lgm-dma.c:694
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
```
**Symbols:**

```
ffffffff81a515c0-ffffffff81a516b5: ldma_chan_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ldma_chan_reset(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d310)
Location: drivers/dma/lgm/lgm-dma.c:694
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
```
**Symbols:**

```
ffffffff81a9d310-ffffffff81a9d405: ldma_chan_reset (STB_LOCAL)
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
