# Function: <code>iosys_map_is_null</code>

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
In drivers/dma-buf/dma-buf.c (ffffffff819ed52b)
Location: include/linux/iosys-map.h:221
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
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
In drivers/dma-buf/dma-buf.c (ffffffff81b6a7eb)
Location: include/linux/iosys-map.h:235
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
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
In drivers/dma-buf/dma-buf.c (ffffffff81bbdc3b)
Location: include/linux/iosys-map.h:235
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81c1238b)
Location: include/linux/iosys-map.h:235
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9ba05)
Location: include/linux/iosys-map.h:235
Inline: True
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (ffffffff81ccbd93)
Location: include/linux/iosys-map.h:235
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_vunmap
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_vmap
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
