# Function: <code>drm_drv_uses_atomic_modeset</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c79e22)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:__drm_state_dump
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c83235)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_locked
```
```
In drivers/gpu/drm/drm_color_mgmt.c (ffffffff81c8524f)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87bb3)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
```
```
In drivers/gpu/drm/drm_crtc.c (ffffffff81c8a7e5)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:__drm_mode_set_config_internal
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_crtc.c:drm_crtc_force_disable
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c99b0e)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca472f)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_object_property_get_default_value
  - drivers/gpu/drm/drm_mode_object.c:drm_object_property_get_value
  - drivers/gpu/drm/drm_mode_object.c:__drm_object_property_get_value
  - drivers/gpu/drm/drm_mode_object.c:drm_object_property_set_value
```
```
In drivers/gpu/drm/drm_plane.c (ffffffff81caabea)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane.c:drm_mode_cursor_universal
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:__setplane_atomic
  - drivers/gpu/drm/drm_plane.c:__setplane_internal
  - drivers/gpu/drm/drm_plane.c:drm_plane_force_disable
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb5729)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
```
```
In drivers/gpu/drm/drm_debugfs.c (ffffffff81cbad3b)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_register
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (ffffffff81cbbaf5)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_open
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3900)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_resume
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_resume
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_shutdown
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_shutdown
```
```
In drivers/gpu/drm/drm_crtc_helper.c (ffffffff81cc7149)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_resume_force_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_connector_dpms
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_disable_unused_functions
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_crtc_in_use
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_encoder_in_use
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (ffffffff81ccbe60)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
```
```
In drivers/gpu/drm/drm_plane_helper.c (ffffffff81cccfff)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane_helper.c:drm_plane_helper_disable_primary
  - drivers/gpu/drm/drm_plane_helper.c:drm_plane_helper_update_primary
```
```
In drivers/gpu/drm/drm_fbdev_generic.c (ffffffff81cd106a)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_client_hotplug
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd3b14)
Location: include/drm/drm_drv.h:561
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_pan_display
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_setcmap
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_debug_leave
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_debug_enter
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
