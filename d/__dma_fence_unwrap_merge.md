# Function: <code>__dma_fence_unwrap_merge</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dma_fence *__dma_fence_unwrap_merge(unsigned int num_fences, struct dma_fence **fences, struct dma_fence_unwrap *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: drivers/dma-buf/dma-fence-unwrap.c:63
Inline: False
```
**Symbols:**

```
ffffffff8209b7ac-ffffffff8209b7c9: __dma_fence_unwrap_merge.cold (STB_LOCAL)
ffffffff81b6dd00-ffffffff81b6e028: __dma_fence_unwrap_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dma_fence *__dma_fence_unwrap_merge(unsigned int num_fences, struct dma_fence **fences, struct dma_fence_unwrap *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: drivers/dma-buf/dma-fence-unwrap.c:63
Inline: False
```
**Symbols:**

```
ffffffff8211c699-ffffffff8211c6b6: __dma_fence_unwrap_merge.cold (STB_LOCAL)
ffffffff81bc14c0-ffffffff81bc1838: __dma_fence_unwrap_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dma_fence *__dma_fence_unwrap_merge(unsigned int num_fences, struct dma_fence **fences, struct dma_fence_unwrap *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: drivers/dma-buf/dma-fence-unwrap.c:63
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
```
**Symbols:**

```
ffffffff821fa535-ffffffff821fa552: __dma_fence_unwrap_merge.cold (STB_LOCAL)
ffffffff81c15c40-ffffffff81c15fca: __dma_fence_unwrap_merge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
