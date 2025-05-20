# Function: <code>dma_fence_chain_init</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81743360)
Location: drivers/dma-buf/dma-fence-chain.c:206
Inline: False
```
**Symbols:**

```
ffffffff81743360-ffffffff81743469: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767300)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
ffffffff81767300-ffffffff81767403: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818278a0)
Location: drivers/dma-buf/dma-fence-chain.c:236
Inline: False
```
**Symbols:**

```
ffffffff818278a0-ffffffff81827999: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81838330)
Location: drivers/dma-buf/dma-fence-chain.c:230
Inline: False
```
**Symbols:**

```
ffffffff81838330-ffffffff81838415: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b610)
Location: drivers/dma-buf/dma-fence-chain.c:230
Inline: False
```
**Symbols:**

```
ffffffff8181b610-ffffffff8181b6f2: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: drivers/dma-buf/dma-fence-chain.c:231
Inline: False
```
**Symbols:**

```
ffffffff81d0bb53-ffffffff81d0bb68: dma_fence_chain_init.cold (STB_LOCAL)
ffffffff818a5a80-ffffffff818a5b69: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: drivers/dma-buf/dma-fence-chain.c:229
Inline: False
```
**Symbols:**

```
ffffffff81ed497e-ffffffff81ed499b: dma_fence_chain_init.cold (STB_LOCAL)
ffffffff819ef960-ffffffff819efa93: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: drivers/dma-buf/dma-fence-chain.c:229
Inline: False
```
**Symbols:**

```
ffffffff8209b78f-ffffffff8209b7ac: dma_fence_chain_init.cold (STB_LOCAL)
ffffffff81b6cf80-ffffffff81b6d0b3: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: drivers/dma-buf/dma-fence-chain.c:241
Inline: False
```
**Symbols:**

```
ffffffff8211c67c-ffffffff8211c699: dma_fence_chain_init.cold (STB_LOCAL)
ffffffff81bc06b0-ffffffff81bc07e3: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: drivers/dma-buf/dma-fence-chain.c:241
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
```
**Symbols:**

```
ffffffff821fa518-ffffffff821fa535: dma_fence_chain_init.cold (STB_LOCAL)
ffffffff81c14e30-ffffffff81c14f63: dma_fence_chain_init (STB_GLOBAL)
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
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffff800010968360)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
ffff800010968360-ffff800010968478: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (c0a3e5cc)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
c0a3e5cc-c0a3e6f4: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1fb50)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
c000000000a1fb50-c000000000a1fd34: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d426c)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
ffffffe0005d426c-ffffffe0005d435a: dma_fence_chain_init (STB_GLOBAL)
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
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171b9f0)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
ffffffff8171b9f0-ffffffff8171baf3: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f4e50)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
ffffffff816f4e50-ffffffff816f4f53: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175a7c0)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
ffffffff8175a7c0-ffffffff8175a8c3: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_fence_chain_init(struct dma_fence_chain *chain, struct dma_fence *prev, struct dma_fence *fence, uint64_t seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81775d80)
Location: drivers/dma-buf/dma-fence-chain.c:228
Inline: False
```
**Symbols:**

```
ffffffff81775d80-ffffffff81775e83: dma_fence_chain_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
