# Function: <code>ldma_issue_pending</code>

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
void ldma_issue_pending(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81708070)
Location: drivers/dma/lgm/lgm-dma.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81708070-ffffffff817081f5: ldma_issue_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ldma_issue_pending(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81783980-ffffffff81783b24: ldma_issue_pending (STB_LOCAL)
ffffffff81cf40ca-ffffffff81cf40f1: ldma_issue_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ldma_issue_pending(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1014
Inline: False
```
**Symbols:**

```
ffffffff818ba5e0-ffffffff818ba77c: ldma_issue_pending (STB_LOCAL)
ffffffff81ebc22c-ffffffff81ebc253: ldma_issue_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ldma_issue_pending(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81a09050-ffffffff81a091ec: ldma_issue_pending (STB_LOCAL)
ffffffff820938a4-ffffffff820938cb: ldma_issue_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ldma_issue_pending(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81a51ed0-ffffffff81a5206c: ldma_issue_pending (STB_LOCAL)
ffffffff821145b0-ffffffff821145d7: ldma_issue_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ldma_issue_pending(struct dma_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81a9dc20-ffffffff81a9ddbc: ldma_issue_pending (STB_LOCAL)
ffffffff821f1f9a-ffffffff821f1fc1: ldma_issue_pending.cold (STB_LOCAL)
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
