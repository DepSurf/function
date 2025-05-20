# Function: <code>drm_mode_object_get</code>

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
void drm_mode_object_get(struct drm_mode_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca38a0)
Location: drivers/gpu/drm/drm_mode_object.c:211
Inline: True
Direct callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_connector_state
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_connector
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_fb_for_plane
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_crtc.c:__drm_mode_set_config_internal
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_cursor_universal
  - drivers/gpu/drm/drm_plane.c:__setplane_internal
  - drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_set_fb
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_connector_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_duplicate_state
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_hpd_irq_event
```
**Symbols:**

```
ffffffff81ca38a0-ffffffff81ca3924: drm_mode_object_get (STB_GLOBAL)
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
