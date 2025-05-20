# Function: <code>drm_gem_fb_get_obj</code>

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
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct drm_gem_object *drm_gem_fb_get_obj(struct drm_framebuffer *fb, unsigned int plane);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (0)
Location: drivers/gpu/drm/drm_gem_framebuffer_helper.c:53
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_begin_cpu_access
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:__drm_gem_fb_end_cpu_access
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_vunmap
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_vmap
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_vmap
```
**Symbols:**

```
ffffffff821fe7b6-ffffffff821fe7de: drm_gem_fb_get_obj.cold (STB_LOCAL)
ffffffff81ccb820-ffffffff81ccb94b: drm_gem_fb_get_obj (STB_GLOBAL)
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
