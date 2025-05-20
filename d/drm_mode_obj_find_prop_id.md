# Function: <code>drm_mode_obj_find_prop_id</code>

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
struct drm_property *drm_mode_obj_find_prop_id(struct drm_mode_object *obj, uint32_t prop_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca46e4)
Location: drivers/gpu/drm/drm_mode_object.c:470
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
Direct callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_set_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_plane.c:drm_plane_get_damage_clips
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_property_event
```
**Symbols:**

```
ffffffff81ca45a0-ffffffff81ca462f: drm_mode_obj_find_prop_id (STB_GLOBAL)
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
