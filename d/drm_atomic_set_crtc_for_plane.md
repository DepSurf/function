# Function: <code>drm_atomic_set_crtc_for_plane</code>

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
int drm_atomic_set_crtc_for_plane(struct drm_plane_state *plane_state, struct drm_crtc *crtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/drm/drm_atomic_uapi.c (0)
Location: drivers/gpu/drm/drm_atomic_uapi.c:187
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_atomic.c:__drm_atomic_helper_set_config
  - drivers/gpu/drm/drm_atomic.c:__drm_atomic_helper_set_config
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property
  - drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb
  - drivers/gpu/drm/drm_atomic_helper.c:page_flip_common
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_disable_all
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_update_plane
```
**Symbols:**

```
ffffffff821fbf54-ffffffff821fbfa0: drm_atomic_set_crtc_for_plane.cold (STB_LOCAL)
ffffffff81c7c640-ffffffff81c7c765: drm_atomic_set_crtc_for_plane (STB_GLOBAL)
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
