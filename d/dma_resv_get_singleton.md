# Function: <code>dma_resv_get_singleton</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_resv_get_singleton(struct dma_resv *obj, enum dma_resv_usage usage, struct dma_fence **fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff819f1620)
Location: drivers/dma-buf/dma-resv.c:608
Inline: False
```
**Symbols:**

```
ffffffff819f1620-ffffffff819f1764: dma_resv_get_singleton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_resv_get_singleton(struct dma_resv *obj, enum dma_resv_usage usage, struct dma_fence **fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81b6f290)
Location: drivers/dma-buf/dma-resv.c:614
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
```
**Symbols:**

```
ffffffff81b6f290-ffffffff81b6f3d4: dma_resv_get_singleton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_resv_get_singleton(struct dma_resv *obj, enum dma_resv_usage usage, struct dma_fence **fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2b60)
Location: drivers/dma-buf/dma-resv.c:619
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
```
**Symbols:**

```
ffffffff81bc2b60-ffffffff81bc2ca4: dma_resv_get_singleton (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_resv_get_singleton(struct dma_resv *obj, enum dma_resv_usage usage, struct dma_fence **fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81c172f0)
Location: drivers/dma-buf/dma-resv.c:619
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
```
**Symbols:**

```
ffffffff81c172f0-ffffffff81c17434: dma_resv_get_singleton (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
