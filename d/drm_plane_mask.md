# Function: <code>drm_plane_mask</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7a233)
Location: include/drm/drm_plane.h:903
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_add_affected_planes
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7c68c)
Location: include/drm/drm_plane.h:903
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_plane
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_plane
```
```
In drivers/gpu/drm/drm_blend.c (ffffffff81c7f69c)
Location: include/drm/drm_plane.h:903
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_blend.c:drm_atomic_helper_crtc_normalize_zpos
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c998ae)
Location: include/drm/drm_plane.h:903
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb
```
```
In drivers/gpu/drm/drm_mode_config.c (ffffffff81ca3542)
Location: include/drm/drm_plane.h:903
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc15a7)
Location: include/drm/drm_plane.h:903
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_disable_planes_on_crtc
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_planes_on_crtc
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_crtc_primary_plane
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
