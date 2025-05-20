# Function: <code>drm_modeset_acquire_fini</code>

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
void drm_modeset_acquire_fini(struct drm_modeset_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_modeset_lock.c (ffffffff81ca85f0)
Location: drivers/gpu/drm/drm_modeset_lock.c:262
Inline: True
Direct callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_atomic
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb
  - drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_cursor_common
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_resume
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_shutdown
  - drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_detect_ctx
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_entry_work
```
**Symbols:**

```
ffffffff81ca85f0-ffffffff81ca85ff: drm_modeset_acquire_fini (STB_GLOBAL)
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
