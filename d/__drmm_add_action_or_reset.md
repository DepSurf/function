# Function: <code>__drmm_add_action_or_reset</code>

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
int __drmm_add_action_or_reset(struct drm_device *dev, drmres_release_t action, void *data, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_managed.c (ffffffff81ca04b0)
Location: drivers/gpu/drm/drm_managed.c:165
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_connector.c:drmm_connector_init
  - drivers/gpu/drm/drm_crtc.c:__drmm_crtc_init_with_planes
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_minor_alloc
  - drivers/gpu/drm/drm_encoder.c:__drmm_encoder_init
  - drivers/gpu/drm/drm_mode_config.c:drmm_mode_config_init
  - drivers/gpu/drm/drm_plane.c:__drmm_universal_plane_alloc
  - drivers/gpu/drm/bridge/panel.c:drmm_panel_bridge_add
```
**Symbols:**

```
ffffffff81ca04b0-ffffffff81ca04f7: __drmm_add_action_or_reset (STB_GLOBAL)
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
