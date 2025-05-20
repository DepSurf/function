# Function: <code>xen_swiotlb_get_sgtable</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_swiotlb_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81565cb0)
Location: drivers/xen/swiotlb-xen.c:687
Inline: False
```
**Symbols:**

```
ffffffff81565cb0-ffffffff81565cc0: xen_swiotlb_get_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_swiotlb_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815c9e50)
Location: drivers/xen/swiotlb-xen.c:687
Inline: False
```
**Symbols:**

```
ffffffff815c9e50-ffffffff815c9e60: xen_swiotlb_get_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_swiotlb_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816026c0)
Location: drivers/xen/swiotlb-xen.c:673
Inline: False
```
**Symbols:**

```
ffffffff816026c0-ffffffff816026d0: xen_swiotlb_get_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_swiotlb_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161d790)
Location: drivers/xen/swiotlb-xen.c:661
Inline: False
```
**Symbols:**

```
ffffffff8161d790-ffffffff8161d7a0: xen_swiotlb_get_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_swiotlb_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816509c0)
Location: drivers/xen/swiotlb-xen.c:573
Inline: False
```
**Symbols:**

```
ffffffff816509c0-ffffffff816509d0: xen_swiotlb_get_sgtable (STB_LOCAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
