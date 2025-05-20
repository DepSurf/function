# Function: <code>dma_fence_array_create</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff8162a350)
Location: drivers/dma-buf/dma-fence-array.c:122
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8162a350-ffffffff8162a3e3: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff8163ff00)
Location: drivers/dma-buf/dma-fence-array.c:122
Inline: False
```
**Symbols:**

```
ffffffff8163ff00-ffffffff8163ff8f: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff816a8770)
Location: drivers/dma-buf/dma-fence-array.c:131
Inline: False
```
**Symbols:**

```
ffffffff816a8770-ffffffff816a8815: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff816e4ae0)
Location: drivers/dma-buf/dma-fence-array.c:131
Inline: False
```
**Symbols:**

```
ffffffff816e4ae0-ffffffff816e4b85: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81707e50)
Location: drivers/dma-buf/dma-fence-array.c:130
Inline: False
```
**Symbols:**

```
ffffffff81707e50-ffffffff81707ef5: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff817430f0)
Location: drivers/dma-buf/dma-fence-array.c:122
Inline: False
```
**Symbols:**

```
ffffffff817430f0-ffffffff81743197: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81767060)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffff81767060-ffffffff8176710a: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff818274f0)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffff818274f0-ffffffff8182759b: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81837f70)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffff81837f70-ffffffff81838024: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b260)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffff8181b260-ffffffff8181b314: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a56d0)
Location: drivers/dma-buf/dma-fence-array.c:154
Inline: False
```
**Symbols:**

```
ffffffff818a56d0-ffffffff818a5784: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef4c0)
Location: drivers/dma-buf/dma-fence-array.c:154
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
```
**Symbols:**

```
ffffffff819ef4c0-ffffffff819ef5d3: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6ca70)
Location: drivers/dma-buf/dma-fence-array.c:154
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
```
**Symbols:**

```
ffffffff81b6ca70-ffffffff81b6cb83: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc01b0)
Location: drivers/dma-buf/dma-fence-array.c:165
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
```
**Symbols:**

```
ffffffff81bc01b0-ffffffff81bc02c3: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14930)
Location: drivers/dma-buf/dma-fence-array.c:165
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
```
**Symbols:**

```
ffffffff81c14930-ffffffff81c14a43: dma_fence_array_create (STB_GLOBAL)
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
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffff800010967e00)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffff800010967e00-ffff800010967ea8: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (c0a3e1d0)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
c0a3e1d0-c0a3e27c: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f670)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
c000000000a1f670-c000000000a1f768: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffe0005d3f56)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffe0005d3f56-ffffffe0005d3ff4: dma_fence_array_create (STB_GLOBAL)
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
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff8171b750)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffff8171b750-ffffffff8171b7fa: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff816f4bb0)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffff816f4bb0-ffffffff816f4c5a: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff8175a520)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffff8175a520-ffffffff8175a5ca: dma_fence_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dma_fence_array *dma_fence_array_create(int num_fences, struct dma_fence **fences, u64 context, unsigned int seqno, bool signal_on_any);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81775ae0)
Location: drivers/dma-buf/dma-fence-array.c:150
Inline: False
```
**Symbols:**

```
ffffffff81775ae0-ffffffff81775b8a: dma_fence_array_create (STB_GLOBAL)
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
