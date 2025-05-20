# Function: <code>___drm_dbg</code>

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
void ___drm_dbg(struct _ddebug *desc, enum drm_debug_category category, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/drm/drm_print.c (0)
Location: drivers/gpu/drm/drm_print.c:307
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_target_preferred
  - drivers/gpu/drm/drm_color_mgmt.c:drm_color_lut_check
  - drivers/gpu/drm/drm_color_mgmt.c:drm_color_lut_check
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_displayid.c:__displayid_iter_next
  - drivers/gpu/drm/drm_drv.c:drm_core_init
  - drivers/gpu/drm/drm_drv.c:drm_stub_open
  - drivers/gpu/drm/drm_drv.c:drm_minor_register
  - drivers/gpu/drm/drm_drv.c:drm_minor_register
  - drivers/gpu/drm/drm_edid.c:drm_detect_monitor_audio
  - drivers/gpu/drm/drm_edid.c:drm_detect_monitor_audio
  - drivers/gpu/drm/drm_edid.c:drm_edid_to_speaker_allocation
  - drivers/gpu/drm/drm_edid.c:_drm_edid_to_sad
  - drivers/gpu/drm/drm_edid.c:drm_do_probe_ddc_edid
  - drivers/gpu/drm/drm_edid.c:drm_edid_block_valid
  - drivers/gpu/drm/drm_gem.c:drm_gem_dma_resv_wait
  - drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup
  - drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:fill_object_idr
  - drivers/gpu/drm/drm_modes.c:drm_mode_prune_invalid
  - drivers/gpu/drm/drm_modes.c:drm_mode_debug_printmodeline
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_cursor_common
  - drivers/gpu/drm/drm_plane.c:drm_mode_cursor_universal
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
  - drivers/gpu/drm/drm_plane.c:__setplane_check
  - drivers/gpu/drm/drm_plane.c:__setplane_check
  - drivers/gpu/drm/drm_plane.c:__setplane_check
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_hotplug_event
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_lease_event
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_remove
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add
  - drivers/gpu/drm/drm_sysfs.c:status_store
  - drivers/gpu/drm/drm_sysfs.c:status_store
  - drivers/gpu/drm/drm_debugfs_crc.c:crc_control_write
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode
  - drivers/gpu/drm/drm_probe_helper.c:output_poll_execute
  - drivers/gpu/drm/drm_probe_helper.c:output_poll_execute
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
```
**Symbols:**

```
ffffffff821fd649-ffffffff821fd661: ___drm_dbg.cold (STB_LOCAL)
ffffffff81cad9b0-ffffffff81cada85: ___drm_dbg (STB_GLOBAL)
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
