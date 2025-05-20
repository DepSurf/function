# Function: <code>dma_resv_reserve_fences</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dma_resv_reserve_fences(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:177
Inline: False
```
**Symbols:**

```
ffffffff81ed499b-ffffffff81ed49b9: dma_resv_reserve_fences.cold (STB_LOCAL)
ffffffff819f0b60-ffffffff819f0d85: dma_resv_reserve_fences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dma_resv_reserve_fences(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:182
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
```
**Symbols:**

```
ffffffff8209b7c9-ffffffff8209b7e7: dma_resv_reserve_fences.cold (STB_LOCAL)
ffffffff81b6e430-ffffffff81b6e655: dma_resv_reserve_fences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dma_resv_reserve_fences(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:182
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
```
**Symbols:**

```
ffffffff8211c6b6-ffffffff8211c6d4: dma_resv_reserve_fences.cold (STB_LOCAL)
ffffffff81bc1c40-ffffffff81bc1e66: dma_resv_reserve_fences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dma_resv_reserve_fences(struct dma_resv *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-resv.c (0)
Location: drivers/dma-buf/dma-resv.c:182
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
```
**Symbols:**

```
ffffffff821fa552-ffffffff821fa570: dma_resv_reserve_fences.cold (STB_LOCAL)
ffffffff81c163d0-ffffffff81c165f6: dma_resv_reserve_fences (STB_GLOBAL)
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
