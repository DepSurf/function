# Function: <code>dma_resv_add_fence</code>

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
void dma_resv_add_fence(struct dma_resv *obj, struct dma_fence *fence, enum dma_resv_usage usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff819f0e80)
Location: drivers/dma-buf/dma-resv.c:275
Inline: False
```
**Symbols:**

```
ffffffff819f0e80-ffffffff819f1076: dma_resv_add_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dma_resv_add_fence(struct dma_resv *obj, struct dma_fence *fence, enum dma_resv_usage usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:280
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
```
**Symbols:**

```
ffffffff8209b7e7-ffffffff8209b825: dma_resv_add_fence.cold (STB_LOCAL)
ffffffff81b6eb50-ffffffff81b6ed85: dma_resv_add_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dma_resv_add_fence(struct dma_resv *obj, struct dma_fence *fence, enum dma_resv_usage usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:280
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
```
**Symbols:**

```
ffffffff8211c6d4-ffffffff8211c712: dma_resv_add_fence.cold (STB_LOCAL)
ffffffff81bc2440-ffffffff81bc2675: dma_resv_add_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_resv_add_fence(struct dma_resv *obj, struct dma_fence *fence, enum dma_resv_usage usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:280
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
```
**Symbols:**

```
ffffffff821fa570-ffffffff821fa5ae: dma_resv_add_fence.cold (STB_LOCAL)
ffffffff81c16bd0-ffffffff81c16e0a: dma_resv_add_fence (STB_GLOBAL)
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
