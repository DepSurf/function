# Function: <code>dma_interrupt</code>

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
irqreturn_t dma_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81708bd0-ffffffff81708d0e: dma_interrupt (STB_LOCAL)
ffffffff81bf609b-ffffffff81bf60b2: dma_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t dma_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81784b00-ffffffff81784c5b: dma_interrupt (STB_LOCAL)
ffffffff81cf41da-ffffffff81cf4243: dma_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t dma_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1117
Inline: False
```
**Symbols:**

```
ffffffff818bb9a0-ffffffff818bbb27: dma_interrupt (STB_LOCAL)
ffffffff81ebc332-ffffffff81ebc399: dma_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t dma_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81a0a1f0-ffffffff81a0a357: dma_interrupt (STB_LOCAL)
ffffffff82093952-ffffffff820939a2: dma_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
irqreturn_t dma_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81a53070-ffffffff81a531d7: dma_interrupt (STB_LOCAL)
ffffffff8211465e-ffffffff821146ae: dma_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t dma_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81a9ee20-ffffffff81a9ef87: dma_interrupt (STB_LOCAL)
ffffffff821f2048-ffffffff821f2098: dma_interrupt.cold (STB_LOCAL)
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
