# Function: <code>min_chan</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff814bcc85)
Location: drivers/dma/dmaengine.c:400
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8150c707)
Location: drivers/dma/dmaengine.c:404
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81538815)
Location: drivers/dma/dmaengine.c:404
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8154c160)
Location: drivers/dma/dmaengine.c:404
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815afc83)
Location: drivers/dma/dmaengine.c:404
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815e8059)
Location: drivers/dma/dmaengine.c:404
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81602089)
Location: drivers/dma/dmaengine.c:402
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81634966)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81656686)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_chan *min_chan(enum dma_transaction_type cap, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81706e10)
Location: drivers/dma/dmaengine.c:320
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
**Symbols:**

```
ffffffff81706e10-ffffffff81706ef3: min_chan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_chan *min_chan(enum dma_transaction_type cap, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81724250)
Location: drivers/dma/dmaengine.c:320
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
**Symbols:**

```
ffffffff81724250-ffffffff81724333: min_chan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_chan *min_chan(enum dma_transaction_type cap, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff817054c0)
Location: drivers/dma/dmaengine.c:320
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
**Symbols:**

```
ffffffff817054c0-ffffffff817055a3: min_chan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dma_chan *min_chan(enum dma_transaction_type cap, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81780c90)
Location: drivers/dma/dmaengine.c:320
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
**Symbols:**

```
ffffffff81780c90-ffffffff81780dc4: min_chan (STB_LOCAL)
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
In drivers/dma/dmaengine.c (ffffffff818b78f3)
Location: drivers/dma/dmaengine.c:320
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
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
In drivers/dma/dmaengine.c (ffffffff81a04b0f)
Location: drivers/dma/dmaengine.c:320
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
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
In drivers/dma/dmaengine.c (ffffffff81a4d96f)
Location: drivers/dma/dmaengine.c:320
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
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
In drivers/dma/dmaengine.c (ffffffff81a9960f)
Location: drivers/dma/dmaengine.c:320
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffff8000107fc3c0)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c091e350)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c0000000008c7310)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffe0005164f4)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8161c526)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81610c16)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8164a4c6)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81664a66)
Location: drivers/dma/dmaengine.c:392
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
