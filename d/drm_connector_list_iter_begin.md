# Function: <code>drm_connector_list_iter_begin</code>

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
void drm_connector_list_iter_begin(struct drm_device *dev, struct drm_connector_list_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_connector.c (ffffffff81c888e8)
Location: drivers/gpu/drm/drm_connector.c:792
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_connector_register_all
  - drivers/gpu/drm/drm_connector.c:drm_connector_register_all
Direct callers:
  - drivers/gpu/drm/drm_atomic.c:__drm_state_dump
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_add_affected_connectors
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_encoder.c:drm_mode_getencoder
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_reset
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_getresources
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_duplicate_state
  - drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_resume_force_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_connector_dpms
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_choose_crtc_dpms
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_encoder_in_use
  - drivers/gpu/drm/drm_plane_helper.c:get_connectors_for_crtc
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_hpd_irq_event
  - drivers/gpu/drm/drm_probe_helper.c:output_poll_execute
  - drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_enable
  - drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_disable_hpd
  - drivers/gpu/drm/drm_fb_helper.c:drm_setup_crtcs_fb
  - drivers/gpu/drm/drm_fb_helper.c:__drm_fb_helper_find_sizes
```
**Symbols:**

```
ffffffff81c85780-ffffffff81c8579e: drm_connector_list_iter_begin (STB_GLOBAL)
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
