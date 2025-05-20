# Function: <code>vchan_dma_desc_free_list</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan *vc, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81706f40)
Location: drivers/dma/virt-dma.c:112
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81706f40-ffffffff81707033: vchan_dma_desc_free_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan *vc, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff817827f0)
Location: drivers/dma/virt-dma.c:112
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff817827f0-ffffffff817828e3: vchan_dma_desc_free_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan *vc, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff818b9260)
Location: drivers/dma/virt-dma.c:112
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff818b9260-ffffffff818b9367: vchan_dma_desc_free_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan *vc, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a06920)
Location: drivers/dma/virt-dma.c:112
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81a06920-ffffffff81a06a27: vchan_dma_desc_free_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan *vc, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a4f7b0)
Location: drivers/dma/virt-dma.c:112
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81a4f7b0-ffffffff81a4f8b7: vchan_dma_desc_free_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan *vc, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a9b450)
Location: drivers/dma/virt-dma.c:112
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81a9b450-ffffffff81a9b557: vchan_dma_desc_free_list (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan *vc, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffff8000107fe3b8)
Location: drivers/dma/virt-dma.c:112
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
```
**Symbols:**

```
ffff8000107fe3b8-ffff8000107fe4c4: vchan_dma_desc_free_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vchan_dma_desc_free_list(struct virt_dma_chan *vc, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (c091f814)
Location: drivers/dma/virt-dma.c:112
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
```
**Symbols:**

```
c091f814-c091f910: vchan_dma_desc_free_list (STB_GLOBAL)
```
</details>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Arch</b>
<ul>
</ul>
