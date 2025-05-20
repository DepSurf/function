# Function: <code>drm_property_blob_put</code>

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
void drm_property_blob_put(struct drm_property_blob *blob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_property.c (ffffffff81caeee2)
Location: drivers/gpu/drm/drm_property.c:601
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_change_valid_put
  - drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_createblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_getblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id
  - drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id
  - drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id
  - drivers/gpu/drm/drm_property.c:drm_property_replace_global_blob
  - drivers/gpu/drm/drm_property.c:drm_property_replace_global_blob
  - drivers/gpu/drm/drm_property.c:drm_property_destroy_user_blobs
Direct callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_crtc_set_property
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_prop_for_crtc
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_for_crtc
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_for_crtc
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_connector_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state
  - drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb
```
**Symbols:**

```
ffffffff81cadc20-ffffffff81cadc42: drm_property_blob_put (STB_GLOBAL)
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
