# Function: <code>drm_core_check_all_features</code>

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
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:__drm_state_dump
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_check
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_check
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7db85)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e3fe)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_destroy
  - drivers/gpu/drm/drm_auth.c:drm_master_release
```
```
In drivers/gpu/drm/drm_client.c (ffffffff81c82015)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client.c:drm_client_dev_restore
  - drivers/gpu/drm/drm_client.c:drm_client_dev_unregister
  - drivers/gpu/drm/drm_client.c:drm_client_init
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c83235)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_dpms
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_locked
```
```
In drivers/gpu/drm/drm_color_mgmt.c (ffffffff81c85485)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_get_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c8912b)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_getconnector
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
```
```
In drivers/gpu/drm/drm_crtc.c (ffffffff81c8a706)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:__drm_mode_set_config_internal
  - drivers/gpu/drm/drm_crtc.c:drm_mode_getcrtc
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_crtc.c:drm_crtc_force_disable
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8bf36)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_dev_unregister
  - drivers/gpu/drm/drm_drv.c:drm_dev_register
  - drivers/gpu/drm/drm_drv.c:drm_dev_register
  - drivers/gpu/drm/drm_drv.c:drm_dev_register
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
```
```
In drivers/gpu/drm/drm_encoder.c (ffffffff81c9663e)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_encoder.c:drm_mode_getencoder
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c9795a)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_free
  - drivers/gpu/drm/drm_file.c:drm_file_free
  - drivers/gpu/drm/drm_file.c:drm_file_free
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c99b0e)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_dirtyfb_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb2_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_closefb_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_addfb2
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_addfb
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9d874)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_flink_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_close_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_private_object_init
```
```
In drivers/gpu/drm/drm_ioctl.c (ffffffff81c9e175)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioctl.c:drm_setclientcap
  - drivers/gpu/drm/drm_ioctl.c:drm_setclientcap
  - drivers/gpu/drm/drm_ioctl.c:drm_setclientcap
  - drivers/gpu/drm/drm_ioctl.c:drm_getcap
  - drivers/gpu/drm/drm_ioctl.c:drm_getcap
  - drivers/gpu/drm/drm_ioctl.c:drm_getcap
  - drivers/gpu/drm/drm_ioctl.c:drm_getcap
```
```
In drivers/gpu/drm/drm_lease.c (ffffffff81ca01eb)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_lease.c:drm_mode_revoke_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
```
```
In drivers/gpu/drm/drm_mode_config.c (ffffffff81ca3325)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_getresources
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca472f)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_object_property_get_default_value
  - drivers/gpu/drm/drm_mode_object.c:drm_object_property_get_value
  - drivers/gpu/drm/drm_mode_object.c:__drm_object_property_get_value
  - drivers/gpu/drm/drm_mode_object.c:drm_object_property_set_value
```
```
In drivers/gpu/drm/drm_plane.c (ffffffff81cab477)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_cursor_common
  - drivers/gpu/drm/drm_plane.c:drm_mode_cursor_universal
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:__setplane_atomic
  - drivers/gpu/drm/drm_plane.c:__setplane_internal
  - drivers/gpu/drm/drm_plane.c:drm_mode_getplane
  - drivers/gpu/drm/drm_plane.c:drm_mode_getplane_res
  - drivers/gpu/drm/drm_plane.c:drm_mode_getplane_res
  - drivers/gpu/drm/drm_plane.c:drm_plane_force_disable
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
```
```
In drivers/gpu/drm/drm_property.c (ffffffff81caebf5)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_createblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_getblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_getproperty_ioctl
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1f39)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_timeline_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_reset_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_eventfd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_timeline_wait_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_wait_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_destroy_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create_ioctl
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb740b)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_enable
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_init_release
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_disable_and_save
  - drivers/gpu/drm/drm_vblank.c:__get_vblank_counter
```
```
In drivers/gpu/drm/drm_debugfs.c (ffffffff81cbad0b)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_register
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_register
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_create_files
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (ffffffff81cbbaf5)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_open
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3900)
Location: include/drm/drm_drv.h:529
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
Location: include/drm/drm_drv.h:529
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
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
```
```
In drivers/gpu/drm/drm_plane_helper.c (ffffffff81cccfff)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane_helper.c:drm_plane_helper_disable_primary
  - drivers/gpu/drm/drm_plane_helper.c:drm_plane_helper_update_primary
```
```
In drivers/gpu/drm/drm_simple_kms_helper.c (ffffffff81cd025b)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_simple_kms_helper.c:drm_simple_kms_plane_prepare_fb
```
```
In drivers/gpu/drm/drm_fbdev_generic.c (ffffffff81cd106a)
Location: include/drm/drm_drv.h:529
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_client_hotplug
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd3b14)
Location: include/drm/drm_drv.h:529
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
