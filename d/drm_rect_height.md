# Function: <code>drm_rect_height</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c795b8)
Location: include/drm/drm_rect.h:196
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
```
```
In drivers/gpu/drm/drm_format_helper.c (ffffffff81cc9a0f)
Location: include/drm/drm_rect.h:196
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_xrgb8888_to_mono
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_memcpy
```
```
In drivers/gpu/drm/drm_plane_helper.c (ffffffff81cccbb5)
Location: include/drm/drm_rect.h:196
Inline: True
```
```
In drivers/gpu/drm/drm_rect.c (ffffffff81ccf345)
Location: include/drm/drm_rect.h:196
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_rect.c:drm_rect_calc_vscale
  - drivers/gpu/drm/drm_rect.c:drm_rect_calc_vscale
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
  - drivers/gpu/drm/drm_rect.c:drm_rect_clip_scaled
  - drivers/gpu/drm/drm_rect.c:drm_rect_intersect
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd416b)
Location: include/drm/drm_rect.h:196
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_deferred_io
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_damage_range
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
