# Function: <code>dma_resv_get_fences</code>

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
int dma_resv_get_fences(struct dma_resv *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff818a6ec0)
Location: drivers/dma-buf/dma-resv.c:411
Inline: False
```
**Symbols:**

```
ffffffff818a6ec0-ffffffff818a72cf: dma_resv_get_fences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dma_resv_get_fences(struct dma_resv *obj, enum dma_resv_usage usage, unsigned int *num_fences, struct dma_fence ***fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:555
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
```
**Symbols:**

```
ffffffff81ed49d4-ffffffff81ed49ef: dma_resv_get_fences.cold (STB_LOCAL)
ffffffff819f13e0-ffffffff819f1614: dma_resv_get_fences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dma_resv_get_fences(struct dma_resv *obj, enum dma_resv_usage usage, unsigned int *num_fences, struct dma_fence ***fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:561
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
```
**Symbols:**

```
ffffffff8209b840-ffffffff8209b85b: dma_resv_get_fences.cold (STB_LOCAL)
ffffffff81b6f040-ffffffff81b6f274: dma_resv_get_fences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dma_resv_get_fences(struct dma_resv *obj, enum dma_resv_usage usage, unsigned int *num_fences, struct dma_fence ***fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:561
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
```
**Symbols:**

```
ffffffff8211c72d-ffffffff8211c748: dma_resv_get_fences.cold (STB_LOCAL)
ffffffff81bc2910-ffffffff81bc2b50: dma_resv_get_fences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dma_resv_get_fences(struct dma_resv *obj, enum dma_resv_usage usage, unsigned int *num_fences, struct dma_fence ***fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:561
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
```
**Symbols:**

```
ffffffff821fa5c9-ffffffff821fa5e4: dma_resv_get_fences.cold (STB_LOCAL)
ffffffff81c170a0-ffffffff81c172e0: dma_resv_get_fences (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int *num_fences</code>
</li>
<li>
<b>Param added. </b>
<code>struct dma_fence ***fences</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dma_fence **pfence_excl</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *pshared_count</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dma_fence ***pshared</code>
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
