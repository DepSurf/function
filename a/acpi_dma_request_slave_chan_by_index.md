# Function: <code>acpi_dma_request_slave_chan_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff814be2f0)
Location: drivers/dma/acpi-dma.c:348
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff814be2f0-ffffffff814be47c: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff8150dfb0)
Location: drivers/dma/acpi-dma.c:351
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff8150dfb0-ffffffff8150e152: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff8153a110)
Location: drivers/dma/acpi-dma.c:351
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff8153a110-ffffffff8153a2b2: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff8154d960)
Location: drivers/dma/acpi-dma.c:351
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff8154d960-ffffffff8154dae8: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff815b129f)
Location: drivers/dma/acpi-dma.c:351
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff815b10b0-ffffffff815b124b: acpi_dma_request_slave_chan_by_index.part.6 (STB_LOCAL)
ffffffff815b1250-ffffffff815b126d: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff815e96bf)
Location: drivers/dma/acpi-dma.c:351
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff815e94d0-ffffffff815e966c: acpi_dma_request_slave_chan_by_index.part.8 (STB_LOCAL)
ffffffff815e9670-ffffffff815e968d: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81603b9f)
Location: drivers/dma/acpi-dma.c:351
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff816039b0-ffffffff81603b4c: acpi_dma_request_slave_chan_by_index.part.6 (STB_LOCAL)
ffffffff81603b50-ffffffff81603b6d: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff816365a3)
Location: drivers/dma/acpi-dma.c:348
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff816363b0-ffffffff81636545: acpi_dma_request_slave_chan_by_index.part.0 (STB_LOCAL)
ffffffff81636550-ffffffff8163656d: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff816582c3)
Location: drivers/dma/acpi-dma.c:356
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff816580d0-ffffffff81658265: acpi_dma_request_slave_chan_by_index.part.0 (STB_LOCAL)
ffffffff81658270-ffffffff8165828d: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81708ea2)
Location: drivers/dma/acpi-dma.c:358
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff81708ce0-ffffffff81708e66: acpi_dma_request_slave_chan_by_index.part.0.isra.0 (STB_LOCAL)
ffffffff81708f40-ffffffff81708f64: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81725a50)
Location: drivers/dma/acpi-dma.c:358
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff81725a50-ffffffff81725bd6: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff817072e0)
Location: drivers/dma/acpi-dma.c:358
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff817072e0-ffffffff81707470: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81782be0)
Location: drivers/dma/acpi-dma.c:370
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff81782be0-ffffffff81782d70: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff818b96b0)
Location: drivers/dma/acpi-dma.c:370
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff818b96b0-ffffffff818b9863: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81a06dc0)
Location: drivers/dma/acpi-dma.c:370
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff81a06dc0-ffffffff81a06f73: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81a4fc50)
Location: drivers/dma/acpi-dma.c:370
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff81a4fc50-ffffffff81a4fe03: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81a9b8f0)
Location: drivers/dma/acpi-dma.c:370
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff81a9b8f0-ffffffff81a9baa3: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffff8000107fee34)
Location: drivers/dma/acpi-dma.c:356
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffff8000107fec18-ffff8000107fedb0: acpi_dma_request_slave_chan_by_index.part.0 (STB_LOCAL)
ffff8000107fedb0-ffff8000107fedec: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff8161e163)
Location: drivers/dma/acpi-dma.c:356
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff8161df70-ffffffff8161e105: acpi_dma_request_slave_chan_by_index.part.0 (STB_LOCAL)
ffffffff8161e110-ffffffff8161e12d: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff81612853)
Location: drivers/dma/acpi-dma.c:356
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff81612660-ffffffff816127f5: acpi_dma_request_slave_chan_by_index.part.0 (STB_LOCAL)
ffffffff81612800-ffffffff8161281d: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff8164c103)
Location: drivers/dma/acpi-dma.c:356
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff8164bf10-ffffffff8164c0a5: acpi_dma_request_slave_chan_by_index.part.0 (STB_LOCAL)
ffffffff8164c0b0-ffffffff8164c0cd: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_chan *acpi_dma_request_slave_chan_by_index(struct device *dev, size_t index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/acpi-dma.c (ffffffff816666a3)
Location: drivers/dma/acpi-dma.c:356
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_name
```
**Symbols:**

```
ffffffff816664b0-ffffffff81666645: acpi_dma_request_slave_chan_by_index.part.0 (STB_LOCAL)
ffffffff81666650-ffffffff8166666d: acpi_dma_request_slave_chan_by_index (STB_GLOBAL)
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
