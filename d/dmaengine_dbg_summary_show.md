# Function: <code>dmaengine_dbg_summary_show</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void dmaengine_dbg_summary_show(struct seq_file *s, struct dma_device *dma_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81706870)
Location: drivers/dma/dmaengine.c:83
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaengine_summary_show
```
**Symbols:**

```
ffffffff81706870-ffffffff8170691b: dmaengine_dbg_summary_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dmaengine_dbg_summary_show(struct seq_file *s, struct dma_device *dma_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81723bb0)
Location: drivers/dma/dmaengine.c:83
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaengine_summary_show
```
**Symbols:**

```
ffffffff81723bb0-ffffffff81723c5b: dmaengine_dbg_summary_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81704edc)
Location: drivers/dma/dmaengine.c:83
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_summary_show
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
In drivers/dma/dmaengine.c (ffffffff817805cc)
Location: drivers/dma/dmaengine.c:83
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff818b708b)
Location: drivers/dma/dmaengine.c:83
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a03f0b)
Location: drivers/dma/dmaengine.c:83
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a4cd6b)
Location: drivers/dma/dmaengine.c:83
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a989bb)
Location: drivers/dma/dmaengine.c:83
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_summary_show
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
</ul>
