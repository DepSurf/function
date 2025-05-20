# Function: <code>dma_resv_test_signaled</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dma_resv_test_signaled(struct dma_resv *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff818a6980)
Location: drivers/dma-buf/dma-resv.c:616
Inline: False
```
**Symbols:**

```
ffffffff818a6980-ffffffff818a6c1e: dma_resv_test_signaled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dma_resv_test_signaled(struct dma_resv *obj, enum dma_resv_usage usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff819f1080)
Location: drivers/dma-buf/dma-resv.c:695
Inline: False
```
**Symbols:**

```
ffffffff819f1080-ffffffff819f1152: dma_resv_test_signaled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dma_resv_test_signaled(struct dma_resv *obj, enum dma_resv_usage usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81b6ea60)
Location: drivers/dma-buf/dma-resv.c:701
Inline: False
```
**Symbols:**

```
ffffffff81b6ea60-ffffffff81b6eb32: dma_resv_test_signaled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dma_resv_test_signaled(struct dma_resv *obj, enum dma_resv_usage usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2350)
Location: drivers/dma-buf/dma-resv.c:728
Inline: False
```
**Symbols:**

```
ffffffff81bc2350-ffffffff81bc2422: dma_resv_test_signaled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dma_resv_test_signaled(struct dma_resv *obj, enum dma_resv_usage usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81c16ae0)
Location: drivers/dma-buf/dma-resv.c:728
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_file.c:drm_show_memory_stats
  - drivers/gpu/drm/drm_file.c:drm_show_memory_stats
  - drivers/gpu/drm/drm_gem.c:drm_gem_evict
```
**Symbols:**

```
ffffffff81c16ae0-ffffffff81c16bb2: dma_resv_test_signaled (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum dma_resv_usage usage</code>
</li>
<li>
<b>Param removed. </b>
<code>bool test_all</code>
</li>
</ul>
</details>
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
