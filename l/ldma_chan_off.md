# Function: <code>ldma_chan_off</code>

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
int ldma_chan_off(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81707910)
Location: drivers/dma/lgm/lgm-dma.c:613
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_pause_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
```
**Symbols:**

```
ffffffff81707910-ffffffff817079be: ldma_chan_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ldma_chan_off(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff817831e0)
Location: drivers/dma/lgm/lgm-dma.c:613
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_pause_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
```
**Symbols:**

```
ffffffff817831e0-ffffffff8178328e: ldma_chan_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ldma_chan_off(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff818b9d90)
Location: drivers/dma/lgm/lgm-dma.c:613
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_pause_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
```
**Symbols:**

```
ffffffff818b9d90-ffffffff818b9e4a: ldma_chan_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ldma_chan_off(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a086d0)
Location: drivers/dma/lgm/lgm-dma.c:613
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_pause_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
```
**Symbols:**

```
ffffffff81a086d0-ffffffff81a0878a: ldma_chan_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ldma_chan_off(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a51420)
Location: drivers/dma/lgm/lgm-dma.c:613
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_pause_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
```
**Symbols:**

```
ffffffff81a51420-ffffffff81a514df: ldma_chan_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ldma_chan_off(struct ldma_chan *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d170)
Location: drivers/dma/lgm/lgm-dma.c:613
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_pause_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
```
**Symbols:**

```
ffffffff81a9d170-ffffffff81a9d22f: ldma_chan_off (STB_LOCAL)
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
