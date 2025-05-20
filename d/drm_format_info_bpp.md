# Function: <code>drm_format_info_bpp</code>

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
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int drm_format_info_bpp(const struct drm_format_info *info, int plane);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_fourcc.c (ffffffff81c98590)
Location: drivers/gpu/drm/drm_fourcc.c:427
Inline: True
Direct callers:
  - drivers/gpu/drm/drm_client.c:drm_client_framebuffer_create
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_swab
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_memcpy
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_afbc_min_size
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_damage_blit_real
  - drivers/gpu/drm/drm_fb_helper.c:__drm_fb_helper_find_sizes
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_check_var
  - drivers/gpu/drm/drm_fb_helper.c:__fill_var
  - drivers/gpu/drm/tiny/simpledrm.c:simpledrm_probe
```
**Symbols:**

```
ffffffff81c98590-ffffffff81c986d9: drm_format_info_bpp (STB_GLOBAL)
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
</ul>
