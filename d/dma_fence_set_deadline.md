# Function: <code>dma_fence_set_deadline</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_set_deadline(struct dma_fence *fence, ktime_t deadline);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf8a0)
Location: drivers/dma-buf/dma-fence.c:968
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-resv.c:dma_resv_set_deadline
```
**Symbols:**

```
ffffffff81bbf8a0-ffffffff81bbf93c: dma_fence_set_deadline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_set_deadline(struct dma_fence *fence, ktime_t deadline);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c14020)
Location: drivers/dma-buf/dma-fence.c:969
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-resv.c:dma_resv_set_deadline
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_fences
```
**Symbols:**

```
ffffffff81c14020-ffffffff81c140bc: dma_fence_set_deadline (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
