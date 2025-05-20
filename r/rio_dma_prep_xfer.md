# Function: <code>rio_dma_prep_xfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81459dc0)
Location: drivers/rapidio/rio.c:1572
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff81459dc0-ffffffff81459e41: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814a76b0)
Location: drivers/rapidio/rio.c:1889
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff814a76b0-ffffffff814a773f: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814c97c0)
Location: drivers/rapidio/rio.c:1889
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff814c97c0-ffffffff814c984f: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814d5770)
Location: drivers/rapidio/rio.c:1886
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff814d5770-ffffffff814d57ff: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81515c20)
Location: drivers/rapidio/rio.c:1886
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff81515c20-ffffffff81515cb1: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1885
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff8154ce92-ffffffff8154ceac: rio_dma_prep_xfer.cold.19 (STB_LOCAL)
ffffffff8154ada0-ffffffff8154ae1e: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815642d2)
Location: drivers/rapidio/rio.c:1885
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff815642d2-ffffffff815642ec: rio_dma_prep_xfer.cold.20 (STB_LOCAL)
ffffffff81562500-ffffffff8156257e: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81594658)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff81594658-ffffffff81594672: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff81592920-ffffffff815929a0: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815b58e8)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff815b58e8-ffffffff815b5902: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff815b3ba0-ffffffff815b3c20: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8165dba3)
Location: drivers/rapidio/rio.c:1881
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff8165f558-ffffffff8165f572: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff8165d0b0-ffffffff8165d12d: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8167f2c3)
Location: drivers/rapidio/rio.c:1816
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff81bfe3cb-ffffffff81bfe3e5: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff8167e590-ffffffff8167e60d: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81661fd9)
Location: drivers/rapidio/rio.c:1816
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff81beffae-ffffffff81beffc8: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff81661410-ffffffff8166148d: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff816d4ea9)
Location: drivers/rapidio/rio.c:1816
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff81ceb618-ffffffff81ceb632: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff816d41a0-ffffffff816d421d: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff817fef0f)
Location: drivers/rapidio/rio.c:1816
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff81eb2a30-ffffffff81eb2a4a: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff817fe250-ffffffff817fe301: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8192c1f9)
Location: drivers/rapidio/rio.c:1816
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff8192b4a0-ffffffff8192b55c: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81970469)
Location: drivers/rapidio/rio.c:1816
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff8196f710-ffffffff8196f7cc: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff819ba4d9)
Location: drivers/rapidio/rio.c:1816
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff819b9600-ffffffff819b96bc: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffff80001073b520)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffff80001073b520-ffff80001073b604: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c08c1868)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
c08c1868-c08c1928: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c000000000894e80)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
c000000000894e80-c000000000894f78: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffe0004ebc8c)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffe0004ebc8c-ffffffe0004ebd1e: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a9b58)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff815a9b58-ffffffff815a9b72: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff815a7e10-ffffffff815a7e90: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81598cf8)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff81598cf8-ffffffff81598d12: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff81596fb0-ffffffff81597030: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815aa0e8)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff815aa0e8-ffffffff815aa102: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff815a83a0-ffffffff815a8420: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_async_tx_descriptor *rio_dma_prep_xfer(struct dma_chan *dchan, u16 destid, struct rio_dma_data *data, enum dma_transfer_direction direction, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815c3a97)
Location: drivers/rapidio/rio.c:1881
Inline: True
Direct callers:
  - drivers/rapidio/rio.c:rio_dma_prep_slave_sg
```
**Symbols:**

```
ffffffff815c3a97-ffffffff815c3ab1: rio_dma_prep_xfer.cold (STB_LOCAL)
ffffffff815c26d0-ffffffff815c2750: rio_dma_prep_xfer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
