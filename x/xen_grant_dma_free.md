# Function: <code>xen_grant_dma_free</code>

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
Location: drivers/xen/grant-dma-ops.c:100
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_grant_dma_free(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-dma-ops.c (0)
Location: drivers/xen/grant-dma-ops.c:116
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free_pages
```
**Symbols:**

```
ffffffff81a34b40-ffffffff81a34c52: xen_grant_dma_free (STB_LOCAL)
ffffffff82094a51-ffffffff82094a66: xen_grant_dma_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_grant_dma_free(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-dma-ops.c (0)
Location: drivers/xen/grant-dma-ops.c:116
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free_pages
```
**Symbols:**

```
ffffffff81a7e550-ffffffff81a7e662: xen_grant_dma_free (STB_LOCAL)
ffffffff82115875-ffffffff8211588a: xen_grant_dma_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_grant_dma_free(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-dma-ops.c (0)
Location: drivers/xen/grant-dma-ops.c:116
Inline: False
Direct callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free_pages
```
**Symbols:**

```
ffffffff81ad0ac0-ffffffff81ad0bd2: xen_grant_dma_free (STB_LOCAL)
ffffffff821f3518-ffffffff821f352d: xen_grant_dma_free.cold (STB_LOCAL)
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
