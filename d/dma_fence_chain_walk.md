# Function: <code>dma_fence_chain_walk</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817434b0)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff817434b0-ffffffff81743671: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff81743700-ffffffff8174373a: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767450)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff81767450-ffffffff8176761e: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff817676e0-ffffffff81767722: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827ef0)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff81827b00-ffffffff81827dd3: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff81827de0-ffffffff81827e3a: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81838ad0)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff81838580-ffffffff81838861: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff81838870-ffffffff818388ca: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181bd8c)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff8181b860-ffffffff8181bb2e: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff8181bb30-ffffffff8181bb8a: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a621c)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff818a5cf0-ffffffff818a5fbe: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff818a5fc0-ffffffff818a601a: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efc60)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
**Symbols:**

```
ffffffff819efc60-ffffffff819eff52: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff819eff60-ffffffff819effd8: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d2b0)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
**Symbols:**

```
ffffffff81b6d2b0-ffffffff81b6d5a2: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff81b6d5c0-ffffffff81b6d638: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc09e0)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
**Symbols:**

```
ffffffff81bc09e0-ffffffff81bc0cc4: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff81bc0ce0-ffffffff81bc0d58: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15160)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
```
**Symbols:**

```
ffffffff81c15160-ffffffff81c15444: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff81c15460-ffffffff81c154d8: dma_fence_chain_walk (STB_GLOBAL)
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
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffff8000109684d8)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffff8000109684d8-ffff800010968718: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffff800010968818-ffff800010968888: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (c0a3e824)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
c0a3e824-c0a3ea90: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1ff80)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
c000000000a1ff80-c000000000a203dc: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d435a)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffe0005d435a-ffffffe0005d4542: dma_fence_chain_walk (STB_GLOBAL)
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
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bb40)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff8171bb40-ffffffff8171bd0e: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff8171bdd0-ffffffff8171be12: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f4fa0)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff816f4fa0-ffffffff816f516e: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff816f5230-ffffffff816f5272: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175a910)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff8175a910-ffffffff8175aade: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff8175aba0-ffffffff8175abe2: dma_fence_chain_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dma_fence *dma_fence_chain_walk(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81775ed0)
Location: drivers/dma-buf/dma-fence-chain.c:39
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
**Symbols:**

```
ffffffff81775ed0-ffffffff817760be: dma_fence_chain_walk.part.0 (STB_LOCAL)
ffffffff81776180-ffffffff817761c2: dma_fence_chain_walk (STB_GLOBAL)
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
