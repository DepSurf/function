# Function: <code>dma_fence_wait_any_timeout</code>

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
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81629c70)
Location: drivers/dma-buf/dma-fence.c:440
Inline: True
```
**Symbols:**

```
ffffffff81629c70-ffffffff81629f45: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8163f600)
Location: drivers/dma-buf/dma-fence.c:469
Inline: False
```
**Symbols:**

```
ffffffff8163f600-ffffffff8163f8cd: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816a8180)
Location: drivers/dma-buf/dma-fence.c:468
Inline: False
```
**Symbols:**

```
ffffffff816a8180-ffffffff816a8435: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816e4460)
Location: drivers/dma-buf/dma-fence.c:469
Inline: False
```
**Symbols:**

```
ffffffff816e4460-ffffffff816e471e: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff817078b0)
Location: drivers/dma-buf/dma-fence.c:567
Inline: False
```
**Symbols:**

```
ffffffff817078b0-ffffffff81707b03: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence.c (0)
Location: drivers/dma-buf/dma-fence.c:577
Inline: False
```
**Symbols:**

```
ffffffff81742fcc-ffffffff81742fe6: dma_fence_wait_any_timeout.cold (STB_LOCAL)
ffffffff81742af0-ffffffff81742d36: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81766ac0)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
ffffffff81766ac0-ffffffff81766d09: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81827170)
Location: drivers/dma-buf/dma-fence.c:554
Inline: False
```
**Symbols:**

```
ffffffff81827170-ffffffff81827402: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81837c10)
Location: drivers/dma-buf/dma-fence.c:764
Inline: False
```
**Symbols:**

```
ffffffff81837c10-ffffffff81837eac: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181aef0)
Location: drivers/dma-buf/dma-fence.c:845
Inline: False
```
**Symbols:**

```
ffffffff8181aef0-ffffffff8181b194: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a5370)
Location: drivers/dma-buf/dma-fence.c:845
Inline: False
```
**Symbols:**

```
ffffffff818a5370-ffffffff818a55f5: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819eefb0)
Location: drivers/dma-buf/dma-fence.c:843
Inline: False
```
**Symbols:**

```
ffffffff819eefb0-ffffffff819ef239: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c4e0)
Location: drivers/dma-buf/dma-fence.c:847
Inline: False
```
**Symbols:**

```
ffffffff81b6c4e0-ffffffff81b6c769: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbfb70)
Location: drivers/dma-buf/dma-fence.c:848
Inline: False
```
**Symbols:**

```
ffffffff81bbfb70-ffffffff81bbfdf9: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c142f0)
Location: drivers/dma-buf/dma-fence.c:848
Inline: False
```
**Symbols:**

```
ffffffff81c142f0-ffffffff81c14579: dma_fence_wait_any_timeout (STB_GLOBAL)
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
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffff800010967248)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
ffff800010967248-ffff8000109674c4: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c0a3db78)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
c0a3db78-c0a3de8c: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c000000000a1edc0)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
c000000000a1edc0-c000000000a1f128: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffe0005d3a78)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
ffffffe0005d3a78-ffffffe0005d3c20: dma_fence_wait_any_timeout (STB_GLOBAL)
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
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8171b1b0)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
ffffffff8171b1b0-ffffffff8171b3f9: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816f4610)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
ffffffff816f4610-ffffffff816f4859: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81759f80)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
ffffffff81759f80-ffffffff8175a1c9: dma_fence_wait_any_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence **fences, uint32_t count, bool intr, long int timeout, uint32_t *idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81775540)
Location: drivers/dma-buf/dma-fence.c:562
Inline: False
```
**Symbols:**

```
ffffffff81775540-ffffffff81775789: dma_fence_wait_any_timeout (STB_GLOBAL)
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
