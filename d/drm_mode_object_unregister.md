# Function: <code>drm_mode_object_unregister</code>

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
void drm_mode_object_unregister(struct drm_device *dev, struct drm_mode_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpu/drm/drm_mode_object.c (0)
Location: drivers/gpu/drm/drm_mode_object.c:104
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_connector.c:drm_connector_cleanup
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:drm_connector_free_work_fn
  - drivers/gpu/drm/drm_connector.c:drm_connector_free
  - drivers/gpu/drm/drm_crtc.c:drm_crtc_cleanup
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_encoder.c:drm_encoder_cleanup
  - drivers/gpu/drm/drm_encoder.c:__drm_encoder_init
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_free
  - drivers/gpu/drm/drm_plane.c:drm_plane_cleanup
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_property.c:drm_property_free_blob
  - drivers/gpu/drm/drm_property.c:drm_property_destroy
```
**Symbols:**

```
ffffffff821fd2b6-ffffffff821fd2cb: drm_mode_object_unregister.cold (STB_LOCAL)
ffffffff81ca4000-ffffffff81ca409c: drm_mode_object_unregister (STB_GLOBAL)
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
