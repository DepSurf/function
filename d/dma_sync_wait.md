# Function: <code>dma_sync_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff814bd390)
Location: drivers/dma/dmaengine.c:279
Inline: True
```
**Symbols:**

```
ffffffff814bd390-ffffffff814bd42f: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8150d2b0)
Location: drivers/dma/dmaengine.c:283
Inline: True
```
**Symbols:**

```
ffffffff8150d2b0-ffffffff8150d354: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815393e0)
Location: drivers/dma/dmaengine.c:283
Inline: True
```
**Symbols:**

```
ffffffff815393e0-ffffffff81539484: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8154cc50)
Location: drivers/dma/dmaengine.c:283
Inline: True
```
**Symbols:**

```
ffffffff8154cc50-ffffffff8154ccf4: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815b01c0)
Location: drivers/dma/dmaengine.c:283
Inline: True
```
**Symbols:**

```
ffffffff815b01c0-ffffffff815b0270: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815e85a0)
Location: drivers/dma/dmaengine.c:283
Inline: True
```
**Symbols:**

```
ffffffff815e85a0-ffffffff815e8650: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff816025e0)
Location: drivers/dma/dmaengine.c:281
Inline: True
```
**Symbols:**

```
ffffffff816025e0-ffffffff81602690: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff816360c9)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
ffffffff816360c9-ffffffff816360ed: dma_sync_wait.cold (STB_LOCAL)
ffffffff81634ea0-ffffffff81634f35: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81657de9)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
ffffffff81657de9-ffffffff81657e0d: dma_sync_wait.cold (STB_LOCAL)
ffffffff81656bc0-ffffffff81656c55: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:519
Inline: False
```
**Symbols:**

```
ffffffff81708586-ffffffff817085aa: dma_sync_wait.cold (STB_LOCAL)
ffffffff81706510-ffffffff817065a5: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:519
Inline: False
```
**Symbols:**

```
ffffffff81c04354-ffffffff81c04378: dma_sync_wait.cold (STB_LOCAL)
ffffffff81723880-ffffffff81723915: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:519
Inline: False
```
**Symbols:**

```
ffffffff81bf5daf-ffffffff81bf5dd3: dma_sync_wait.cold (STB_LOCAL)
ffffffff81704ad0-ffffffff81704b65: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:519
Inline: False
```
**Symbols:**

```
ffffffff81cf3d64-ffffffff81cf3d88: dma_sync_wait.cold (STB_LOCAL)
ffffffff81780110-ffffffff817801a5: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:519
Inline: False
```
**Symbols:**

```
ffffffff81ebbf1d-ffffffff81ebbf41: dma_sync_wait.cold (STB_LOCAL)
ffffffff818b6930-ffffffff818b69e7: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a03b10)
Location: drivers/dma/dmaengine.c:520
Inline: False
```
**Symbols:**

```
ffffffff81a03b10-ffffffff81a03be2: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a4c970)
Location: drivers/dma/dmaengine.c:520
Inline: False
```
**Symbols:**

```
ffffffff81a4c970-ffffffff81a4ca42: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a985c0)
Location: drivers/dma/dmaengine.c:520
Inline: False
```
**Symbols:**

```
ffffffff81a985c0-ffffffff81a98692: dma_sync_wait (STB_GLOBAL)
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
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffff8000107fca08)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
ffff8000107fca08-ffff8000107fcae4: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c091dd20)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
c091dd20-c091de1c: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c0000000008c7c60)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
c0000000008c7c60-c0000000008c7d70: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffe000516874)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
ffffffe000516874-ffffffe00051690a: dma_sync_wait (STB_GLOBAL)
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
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8161dc89)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
ffffffff8161dc89-ffffffff8161dcad: dma_sync_wait.cold (STB_LOCAL)
ffffffff8161ca60-ffffffff8161caf5: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81612379)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
ffffffff81612379-ffffffff8161239d: dma_sync_wait.cold (STB_LOCAL)
ffffffff81611150-ffffffff816111e5: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8164bc29)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
ffffffff8164bc29-ffffffff8164bc4d: dma_sync_wait.cold (STB_LOCAL)
ffffffff8164aa00-ffffffff8164aa95: dma_sync_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum dma_status dma_sync_wait(struct dma_chan *chan, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff816661c9)
Location: drivers/dma/dmaengine.c:270
Inline: True
```
**Symbols:**

```
ffffffff816661c9-ffffffff816661ed: dma_sync_wait.cold (STB_LOCAL)
ffffffff81664fa0-ffffffff81665035: dma_sync_wait (STB_GLOBAL)
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
