# Function: <code>dma_buf_begin_cpu_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, size_t start, size_t len, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff815a2610)
Location: drivers/dma-buf/dma-buf.c:548
Inline: False
```
**Symbols:**

```
ffffffff815a2610-ffffffff815a2647: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff815f95d0)
Location: drivers/dma-buf/dma-buf.c:600
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff815f95d0-ffffffff815f9607: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81627ef0)
Location: drivers/dma-buf/dma-buf.c:616
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81627ef0-ffffffff81627f75: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8163d9f0)
Location: drivers/dma-buf/dma-buf.c:814
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff8163d9f0-ffffffff8163da57: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816a6770)
Location: drivers/dma-buf/dma-buf.c:814
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff816a6770-ffffffff816a67de: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816e2a40)
Location: drivers/dma-buf/dma-buf.c:814
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff816e2a40-ffffffff816e2aab: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81705ef0)
Location: drivers/dma-buf/dma-buf.c:800
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81705ef0-ffffffff81705f5b: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81740f37)
Location: drivers/dma-buf/dma-buf.c:938
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81741d10-ffffffff81741d28: dma_buf_begin_cpu_access.cold (STB_LOCAL)
ffffffff81740f00-ffffffff81740f6d: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff817651c0)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff817651c0-ffffffff8176522b: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81824fb0)
Location: drivers/dma-buf/dma-buf.c:1082
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81824fb0-ffffffff8182501b: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81835980)
Location: drivers/dma-buf/dma-buf.c:1116
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81835980-ffffffff818359eb: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81818de0)
Location: drivers/dma-buf/dma-buf.c:1177
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81818de0-ffffffff81818e48: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff818a32d0)
Location: drivers/dma-buf/dma-buf.c:1182
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff818a32d0-ffffffff818a3338: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff819ed050)
Location: drivers/dma-buf/dma-buf.c:1175
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff819ed050-ffffffff819ed0d3: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81b69f10)
Location: drivers/dma-buf/dma-buf.c:1396
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81b69f10-ffffffff81b69f90: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81bbd360)
Location: drivers/dma-buf/dma-buf.c:1396
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81bbd360-ffffffff81bbd3e0: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81c11a50)
Location: drivers/dma-buf/dma-buf.c:1391
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_begin_cpu_access
```
**Symbols:**

```
ffffffff81c11a50-ffffffff81c11ad0: dma_buf_begin_cpu_access (STB_GLOBAL)
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
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffff8000109653b0)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffff8000109653b0-ffff80001096542c: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (c0a3bf48)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
c0a3bf48-c0a3bfc8: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (c000000000a1c4f0)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
c000000000a1c4f0-c000000000a1c5ac: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffe0005d221c)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffe0005d221c-ffffffe0005d2282: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff817198b0)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff817198b0-ffffffff8171991b: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816f2d20)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff816f2d20-ffffffff816f2d8b: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81758680)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81758680-ffffffff817586eb: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81773b00)
Location: drivers/dma-buf/dma-buf.c:939
Inline: True
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81773b00-ffffffff81773b6b: dma_buf_begin_cpu_access (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t start</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t len</code>
</li>
<li>
<b>Param reordered. </b>
<code>dmabuf, start, len, direction</code> ➡️ <code>dmabuf, direction</code>
</li>
</ul>
</details>
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
