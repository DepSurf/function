# Function: <code>private_candidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff814bd590)
Location: drivers/dma/dmaengine.c:508
Inline: True
Direct callers:
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:__dma_request_channel
```
**Symbols:**

```
ffffffff814bd590-ffffffff814bd6f7: private_candidate (STB_LOCAL)
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
In drivers/dma/dmaengine.c (ffffffff8150cb4f)
Location: drivers/dma/dmaengine.c:515
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff81538c5f)
Location: drivers/dma/dmaengine.c:515
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff8154c41f)
Location: drivers/dma/dmaengine.c:515
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff815af75f)
Location: drivers/dma/dmaengine.c:515
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff815e7af5)
Location: drivers/dma/dmaengine.c:515
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff81602f65)
Location: drivers/dma/dmaengine.c:509
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff81635635)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff81657355)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81706c80)
Location: drivers/dma/dmaengine.c:606
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:find_candidate
```
**Symbols:**

```
ffffffff81706c80-ffffffff81706e06: private_candidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff817240c0)
Location: drivers/dma/dmaengine.c:618
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:find_candidate
```
**Symbols:**

```
ffffffff817240c0-ffffffff81724241: private_candidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81705330)
Location: drivers/dma/dmaengine.c:618
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:find_candidate
```
**Symbols:**

```
ffffffff81705330-ffffffff817054b1: private_candidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81780b10)
Location: drivers/dma/dmaengine.c:618
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:find_candidate
```
**Symbols:**

```
ffffffff81780b10-ffffffff81780c88: private_candidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff818b6a80)
Location: drivers/dma/dmaengine.c:618
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:find_candidate
```
**Symbols:**

```
ffffffff818b6a80-ffffffff818b6c14: private_candidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a05600)
Location: drivers/dma/dmaengine.c:619
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:find_candidate
```
**Symbols:**

```
ffffffff81a05600-ffffffff81a057ac: private_candidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a4e0a0)
Location: drivers/dma/dmaengine.c:619
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:find_candidate
```
**Symbols:**

```
ffffffff81a4e0a0-ffffffff81a4e268: private_candidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dma_chan *private_candidate(const dma_cap_mask_t *mask, struct dma_device *dev, dma_filter_fn fn, void *fn_param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a99d40)
Location: drivers/dma/dmaengine.c:619
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:find_candidate
```
**Symbols:**

```
ffffffff81a99d40-ffffffff81a99f08: private_candidate (STB_LOCAL)
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
In drivers/dma/dmaengine.c (ffff8000107fda04)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (c091ed88)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (c0000000008c6b2c)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffe000515d58)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff8161d1f5)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff816118e5)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff8164b195)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
In drivers/dma/dmaengine.c (ffffffff81665735)
Location: drivers/dma/dmaengine.c:499
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
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
