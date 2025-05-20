# Function: <code>dma_buf_end_cpu_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dma_buf_end_cpu_access(struct dma_buf *dmabuf, size_t start, size_t len, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff815a2650)
Location: drivers/dma-buf/dma-buf.c:576
Inline: False
```
**Symbols:**

```
ffffffff815a2650-ffffffff815a26aa: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff815f9610)
Location: drivers/dma-buf/dma-buf.c:625
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff815f9610-ffffffff815f9656: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81627850)
Location: drivers/dma-buf/dma-buf.c:648
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81627850-ffffffff81627896: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8163d4a0)
Location: drivers/dma-buf/dma-buf.c:848
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff8163d4a0-ffffffff8163d4c6: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816a61e0)
Location: drivers/dma-buf/dma-buf.c:848
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff816a61e0-ffffffff816a620a: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816e24e0)
Location: drivers/dma-buf/dma-buf.c:848
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff816e24e0-ffffffff816e2508: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81705900)
Location: drivers/dma-buf/dma-buf.c:834
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81705900-ffffffff81705928: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:972
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81741c0a-ffffffff81741c23: dma_buf_end_cpu_access.cold (STB_LOCAL)
ffffffff81740630-ffffffff8174066b: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81765322)
Location: drivers/dma-buf/dma-buf.c:973
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81764810-ffffffff81764839: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8182586c)
Location: drivers/dma-buf/dma-buf.c:1116
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81824820-ffffffff81824849: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8183624c)
Location: drivers/dma-buf/dma-buf.c:1150
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff818351a0-ffffffff818351c9: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff818197ac)
Location: drivers/dma-buf/dma-buf.c:1213
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81818370-ffffffff81818399: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff818a3f1c)
Location: drivers/dma-buf/dma-buf.c:1218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff818a29f0-ffffffff818a2a19: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff819ed8d5)
Location: drivers/dma-buf/dma-buf.c:1211
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff819ec250-ffffffff819ec28d: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81b6ac3c)
Location: drivers/dma-buf/dma-buf.c:1432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81b68f10-ffffffff81b68f4d: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81bbe09c)
Location: drivers/dma-buf/dma-buf.c:1432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81bbc330-ffffffff81bbc36d: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81c127ec)
Location: drivers/dma-buf/dma-buf.c:1427
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
Direct callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:__drm_gem_fb_end_cpu_access
```
**Symbols:**

```
ffffffff81c10b30-ffffffff81c10b6d: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffff8000109649e8)
Location: drivers/dma-buf/dma-buf.c:973
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffff8000109649e8-ffff800010964a38: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (c0a3b468)
Location: drivers/dma-buf/dma-buf.c:973
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
c0a3b468-c0a3b4cc: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (c000000000a1b590)
Location: drivers/dma-buf/dma-buf.c:973
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
c000000000a1b590-c000000000a1b5f8: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffe0005d1990)
Location: drivers/dma-buf/dma-buf.c:973
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffe0005d1990-ffffffe0005d19ca: dma_buf_end_cpu_access (STB_GLOBAL)
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
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81719a12)
Location: drivers/dma-buf/dma-buf.c:973
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81718f00-ffffffff81718f29: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816f2e82)
Location: drivers/dma-buf/dma-buf.c:973
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff816f2370-ffffffff816f2399: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff817587e2)
Location: drivers/dma-buf/dma-buf.c:973
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81757cd0-ffffffff81757cf9: dma_buf_end_cpu_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81773c62)
Location: drivers/dma-buf/dma-buf.c:973
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff817731b0-ffffffff817731d9: dma_buf_end_cpu_access (STB_GLOBAL)
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
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
