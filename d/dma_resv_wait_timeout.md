# Function: <code>dma_resv_wait_timeout</code>

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
long int dma_resv_wait_timeout(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff818a72d0)
Location: drivers/dma-buf/dma-resv.c:512
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access
```
**Symbols:**

```
ffffffff818a72d0-ffffffff818a763d: dma_resv_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int dma_resv_wait_timeout(struct dma_resv *obj, enum dma_resv_usage usage, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff819f0d90)
Location: drivers/dma-buf/dma-resv.c:659
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access
  - drivers/dma-buf/dma-buf.c:__map_dma_buf
```
**Symbols:**

```
ffffffff819f0d90-ffffffff819f0e7b: dma_resv_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int dma_resv_wait_timeout(struct dma_resv *obj, enum dma_resv_usage usage, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e960)
Location: drivers/dma-buf/dma-resv.c:665
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access
  - drivers/dma-buf/dma-buf.c:__map_dma_buf
```
**Symbols:**

```
ffffffff81b6e960-ffffffff81b6ea4b: dma_resv_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int dma_resv_wait_timeout(struct dma_resv *obj, enum dma_resv_usage usage, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2250)
Location: drivers/dma-buf/dma-resv.c:670
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access
  - drivers/dma-buf/dma-buf.c:__map_dma_buf
```
**Symbols:**

```
ffffffff81bc2250-ffffffff81bc233b: dma_resv_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int dma_resv_wait_timeout(struct dma_resv *obj, enum dma_resv_usage usage, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81c169e0)
Location: drivers/dma-buf/dma-resv.c:670
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access
  - drivers/dma-buf/dma-buf.c:__map_dma_buf
  - drivers/gpu/drm/drm_gem.c:drm_gem_dma_resv_wait
```
**Symbols:**

```
ffffffff81c169e0-ffffffff81c16acb: dma_resv_wait_timeout (STB_GLOBAL)
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
<code>bool wait_all</code>
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
