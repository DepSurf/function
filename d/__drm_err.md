# Function: <code>__drm_err</code>

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
<summary>In <code>6.8</code>: ✅</summary>

```c
void __drm_err(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_print.c (ffffffff81cad380)
Location: drivers/gpu/drm/drm_print.c:326
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_bridge.c:drm_bridge_attach
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_drv.c:drm_core_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_minor_register
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove
  - drivers/gpu/drm/drm_gem.c:drm_gem_init
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/gpu/drm/drm_modes.c:fill_analog_mode
  - drivers/gpu/drm/drm_modes.c:fill_analog_mode
  - drivers/gpu/drm/drm_modes.c:fill_analog_mode
  - drivers/gpu/drm/drm_modes.c:fill_analog_mode
  - drivers/gpu/drm/drm_modes.c:fill_analog_mode
  - drivers/gpu/drm/drm_modes.c:fill_analog_mode
  - drivers/gpu/drm/drm_modes.c:fill_analog_mode
  - drivers/gpu/drm/drm_plane.c:drm_plane_force_disable
  - drivers/gpu/drm/drm_debugfs_crc.c:drm_crtc_add_crc_entry
  - drivers/accel/drm_accel.c:accel_core_init
  - drivers/accel/drm_accel.c:accel_core_init
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_resume_force_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_modeset_helper.c:drm_mode_config_helper_resume
  - drivers/gpu/drm/bridge/panel.c:panel_bridge_attach
  - drivers/gpu/drm/bridge/panel.c:panel_bridge_attach
```
**Symbols:**

```
ffffffff81cad380-ffffffff81cad426: __drm_err (STB_GLOBAL)
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
