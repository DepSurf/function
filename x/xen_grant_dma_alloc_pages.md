# Function: <code>xen_grant_dma_alloc_pages</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-dma-ops.c (0)
Location: drivers/xen/grant-dma-ops.c:129
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *xen_grant_dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-dma-ops.c (ffffffff81a35090)
Location: drivers/xen/grant-dma-ops.c:145
Inline: False
```
**Symbols:**

```
ffffffff81a35090-ffffffff81a350ed: xen_grant_dma_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *xen_grant_dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-dma-ops.c (ffffffff81a7eaa0)
Location: drivers/xen/grant-dma-ops.c:145
Inline: False
```
**Symbols:**

```
ffffffff81a7eaa0-ffffffff81a7eafd: xen_grant_dma_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *xen_grant_dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-dma-ops.c (ffffffff81ad1010)
Location: drivers/xen/grant-dma-ops.c:145
Inline: False
```
**Symbols:**

```
ffffffff81ad1010-ffffffff81ad106d: xen_grant_dma_alloc_pages (STB_LOCAL)
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
