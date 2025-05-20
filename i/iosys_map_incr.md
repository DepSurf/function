# Function: <code>iosys_map_incr</code>

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
In drivers/gpu/drm/drm_format_helper.c (ffffffff81cc984b)
Location: include/linux/iosys-map.h:323
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_memcpy
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_memcpy
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_memcpy
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (ffffffff81ccbc31)
Location: include/linux/iosys-map.h:323
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_vmap
```
```
In drivers/gpu/drm/drm_fbdev_generic.c (ffffffff81cd1848)
Location: include/linux/iosys-map.h:323
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_damage_blit_real
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_damage_blit_real
```
```
In drivers/gpu/drm/tiny/simpledrm.c (ffffffff81cd6a9d)
Location: include/linux/iosys-map.h:323
Inline: True
Inline callers:
  - drivers/gpu/drm/tiny/simpledrm.c:simpledrm_primary_plane_helper_atomic_update
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
