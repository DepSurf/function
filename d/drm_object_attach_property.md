# Function: <code>drm_object_attach_property</code>

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
void drm_object_attach_property(struct drm_mode_object *obj, struct drm_property *property, uint64_t init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/drm/drm_mode_object.c (0)
Location: drivers/gpu/drm/drm_mode_object.c:233
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_blend_mode_property
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_zpos_immutable_property
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_zpos_property
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_rotation_property
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_alpha_property
  - drivers/gpu/drm/drm_color_mgmt.c:drm_plane_create_color_properties
  - drivers/gpu/drm/drm_color_mgmt.c:drm_plane_create_color_properties
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_enable_color_mgmt
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_enable_color_mgmt
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_enable_color_mgmt
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_enable_color_mgmt
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_enable_color_mgmt
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_privacy_screen_provider
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_privacy_screen_provider
  - drivers/gpu/drm/drm_connector.c:drm_connector_set_orientation_from_panel
  - drivers/gpu/drm/drm_connector.c:drm_connector_set_panel_orientation_with_quirk
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_colorspace_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_hdr_output_metadata_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_max_bpc_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_scaling_mode_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_vrr_capable_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_tv_margin_properties
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_tv_margin_properties
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_tv_margin_properties
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_tv_margin_properties
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_dp_subconnector_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_dp_subconnector_property
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_crtc.c:drm_crtc_create_scaling_filter_property
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_plane.c:drm_plane_create_scaling_filter_property
  - drivers/gpu/drm/drm_plane.c:drm_plane_enable_fb_damage_clips
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder
```
**Symbols:**

```
ffffffff821fd277-ffffffff821fd28c: drm_object_attach_property.cold (STB_LOCAL)
ffffffff81ca3790-ffffffff81ca388c: drm_object_attach_property (STB_GLOBAL)
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
