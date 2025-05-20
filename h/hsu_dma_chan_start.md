# Function: <code>hsu_dma_chan_start</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hsu_dma_chan_start(struct hsu_dma_chan *hsuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/hsu/hsu.c (0)
Location: drivers/dma/hsu/hsu.c:62
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
**Symbols:**

```
ffffffff81a075b0-ffffffff81a07742: hsu_dma_chan_start (STB_LOCAL)
ffffffff820937ea-ffffffff82093826: hsu_dma_chan_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hsu_dma_chan_start(struct hsu_dma_chan *hsuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/hsu/hsu.c (0)
Location: drivers/dma/hsu/hsu.c:62
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
**Symbols:**

```
ffffffff81a50440-ffffffff81a505d2: hsu_dma_chan_start (STB_LOCAL)
ffffffff821144f6-ffffffff82114532: hsu_dma_chan_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hsu_dma_chan_start(struct hsu_dma_chan *hsuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/hsu/hsu.c (0)
Location: drivers/dma/hsu/hsu.c:62
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
**Symbols:**

```
ffffffff81a9c110-ffffffff81a9c2a2: hsu_dma_chan_start (STB_LOCAL)
ffffffff821f1ee0-ffffffff821f1f1c: hsu_dma_chan_start.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
