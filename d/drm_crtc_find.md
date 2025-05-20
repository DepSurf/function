# Function: <code>drm_crtc_find</code>

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
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7cd92)
Location: include/drm/drm_crtc.h:1295
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property
```
```
In drivers/gpu/drm/drm_color_mgmt.c (ffffffff81c854c7)
Location: include/drm/drm_crtc.h:1295
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_get_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
```
```
In drivers/gpu/drm/drm_crtc.c (ffffffff81c8a771)
Location: include/drm/drm_crtc.h:1295
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_getcrtc
```
```
In drivers/gpu/drm/drm_plane.c (ffffffff81cab51c)
Location: include/drm/drm_crtc.h:1295
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_cursor_common
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb7465)
Location: include/drm/drm_crtc.h:1295
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl
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
