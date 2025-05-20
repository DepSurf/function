# Function: <code>dma_free_wc</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160c718)
Location: include/linux/dma-mapping.h:787
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8164183c)
Location: include/linux/dma-mapping.h:793
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816629dc)
Location: include/linux/dma-mapping.h:789
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8171213c)
Location: include/linux/dma-mapping.h:875
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172eecc)
Location: include/linux/dma-mapping.h:529
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8171291c)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8178f463)
Location: include/linux/dma-mapping.h:567
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c775f)
Location: include/linux/dma-mapping.h:567
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a182cf)
Location: include/linux/dma-mapping.h:572
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a6135d)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab3b8d)
Location: include/linux/dma-mapping.h:568
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/mx3fb.c (ffff80001075f168)
Location: include/linux/dma-mapping.h:789
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_unmap_video_memory
```
```
In drivers/xen/grant-table.c (ffff80001082cbf8)
Location: include/linux/dma-mapping.h:789
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/mx3fb.c (c08e20c0)
Location: include/linux/dma-mapping.h:789
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_unmap_video_memory
```
```
In sound/soc/fsl/imx-pcm-fiq.c (c0cc25f4)
Location: include/linux/dma-mapping.h:789
Inline: True
Inline callers:
  - sound/soc/fsl/imx-pcm-fiq.c:imx_pcm_fiq_free
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8162884c)
Location: include/linux/dma-mapping.h:789
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8165681c)
Location: include/linux/dma-mapping.h:789
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81670dfc)
Location: include/linux/dma-mapping.h:789
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
</details>
</li>
</ul>

## Differences
