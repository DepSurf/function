# Function: <code>dma_buf_kunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff815a2790)
Location: drivers/dma-buf/dma-buf.c:646
Inline: False
```
**Symbols:**

```
ffffffff815a2790-ffffffff815a27e4: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff815f9740)
Location: drivers/dma-buf/dma-buf.c:699
Inline: False
```
**Symbols:**

```
ffffffff815f9740-ffffffff815f9794: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81627980)
Location: drivers/dma-buf/dma-buf.c:722
Inline: False
```
**Symbols:**

```
ffffffff81627980-ffffffff816279d4: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff8163d560)
Location: drivers/dma-buf/dma-buf.c:922
Inline: False
```
**Symbols:**

```
ffffffff8163d560-ffffffff8163d585: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816a62a0)
Location: drivers/dma-buf/dma-buf.c:922
Inline: False
```
**Symbols:**

```
ffffffff816a62a0-ffffffff816a62c6: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816e25a0)
Location: drivers/dma-buf/dma-buf.c:922
Inline: False
```
**Symbols:**

```
ffffffff816e25a0-ffffffff816e25c6: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81705960)
Location: drivers/dma-buf/dma-buf.c:875
Inline: False
```
**Symbols:**

```
ffffffff81705960-ffffffff81705986: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:1013
Inline: False
```
**Symbols:**

```
ffffffff81741c3e-ffffffff81741c61: dma_buf_kunmap.cold (STB_LOCAL)
ffffffff817406b0-ffffffff817406e9: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81764870)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81764870-ffffffff81764897: dma_buf_kunmap (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffff800010964a90)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
ffff800010964a90-ffff800010964aec: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (c0a3b530)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
c0a3b530-c0a3b594: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (c000000000a1b670)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
c000000000a1b670-c000000000a1b6c8: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffe0005d1a06)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
ffffffe0005d1a06-ffffffe0005d1a46: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81718f60)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81718f60-ffffffff81718f87: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff816f23d0)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
ffffffff816f23d0-ffffffff816f23f7: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81757d30)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81757d30-ffffffff81757d57: dma_buf_kunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_buf_kunmap(struct dma_buf *dmabuf, long unsigned int page_num, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81773210)
Location: drivers/dma-buf/dma-buf.c:1014
Inline: False
```
**Symbols:**

```
ffffffff81773210-ffffffff81773237: dma_buf_kunmap (STB_GLOBAL)
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
