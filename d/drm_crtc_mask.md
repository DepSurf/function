# Function: <code>drm_crtc_mask</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7ac62)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_check_only
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_check_only
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_check
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c835fa)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_pick_crtcs
```
```
In drivers/gpu/drm/drm_crtc.c (ffffffff81c89eb9)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
```
```
In drivers/gpu/drm/drm_mode_config.c (ffffffff81ca3527)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
```
```
In drivers/gpu/drm/drm_plane.c (ffffffff81caa6cf)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane.c:__setplane_check
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc20ec)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing
```
```
In drivers/gpu/drm/drm_crtc_helper.c (ffffffff81cc7895)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
```
```
In drivers/gpu/drm/drm_probe_helper.c (ffffffff81cce722)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_probe_helper.c:__drm_helper_update_and_validate
```
```
In drivers/gpu/drm/drm_simple_kms_helper.c (ffffffff81cd0501)
Location: include/drm/drm_crtc.h:1277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_simple_kms_helper.c:drm_simple_display_pipe_init
```
```
In drivers/gpu/drm/tiny/simpledrm.c (ffffffff81cd726a)
Location: include/drm/drm_crtc.h:1277
Inline: True
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
