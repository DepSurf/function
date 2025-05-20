# Function: <code>dma_fence_free</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81629120)
Location: drivers/dma-buf/dma-fence.c:187
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81629120-ffffffff81629139: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8163eca0)
Location: drivers/dma-buf/dma-fence.c:184
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff8163eca0-ffffffff8163ecb9: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816a799b)
Location: drivers/dma-buf/dma-fence.c:183
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff816a78f0-ffffffff816a7909: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816e3a79)
Location: drivers/dma-buf/dma-fence.c:184
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff816e39d0-ffffffff816e39e9: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81706d29)
Location: drivers/dma-buf/dma-fence.c:275
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81706c80-ffffffff81706c99: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81742372)
Location: drivers/dma-buf/dma-fence.c:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81741e80-ffffffff81741e9f: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8176617e)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81766080-ffffffff8176609f: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81826e4c)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81826810-ffffffff8182682f: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81837a28)
Location: drivers/dma-buf/dma-fence.c:480
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81837330-ffffffff8183734f: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181a9d8)
Location: drivers/dma-buf/dma-fence.c:561
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff8181a4e0-ffffffff8181a4ff: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a4e75)
Location: drivers/dma-buf/dma-fence.c:561
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff818a4990-ffffffff818a49af: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819ee9da)
Location: drivers/dma-buf/dma-fence.c:562
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff819ee3a0-ffffffff819ee3cf: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c0da)
Location: drivers/dma-buf/dma-fence.c:572
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81b6b7f0-ffffffff81b6b81f: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf6fa)
Location: drivers/dma-buf/dma-fence.c:573
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81bbed10-ffffffff81bbed3d: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c13e7a)
Location: drivers/dma-buf/dma-fence.c:573
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81c13460-ffffffff81c1348d: dma_fence_free (STB_GLOBAL)
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
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffff800010966ac8)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffff8000109664b8-ffff8000109664ec: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c0a3d1a8)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
c0a3d10c-c0a3d138: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c000000000a1dea0)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
c000000000a1dd50-c000000000a1dd94: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffe0005d3040)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffe0005d2fb4-ffffffe0005d2fe4: dma_fence_free (STB_GLOBAL)
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
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8171a86e)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff8171a770-ffffffff8171a78f: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816f3cce)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff816f3bd0-ffffffff816f3bef: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8175963e)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81759540-ffffffff8175955f: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_free(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81774b3e)
Location: drivers/dma-buf/dma-fence.c:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/seqno-fence.c:seqno_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff81774a40-ffffffff81774a5f: dma_fence_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
