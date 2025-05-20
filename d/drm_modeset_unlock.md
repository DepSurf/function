# Function: <code>drm_modeset_unlock</code>

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
void drm_modeset_unlock(struct drm_modeset_lock *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_modeset_lock.c (ffffffff81ca8cf6)
Location: drivers/gpu/drm/drm_modeset_lock.c:422
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_unlock_all
Direct callers:
  - drivers/gpu/drm/drm_atomic.c:__drm_state_dump
  - drivers/gpu/drm/drm_atomic.c:__drm_state_dump
  - drivers/gpu/drm/drm_atomic.c:__drm_state_dump
  - drivers/gpu/drm/drm_atomic.c:__drm_state_dump
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_get_ioctl
  - drivers/gpu/drm/drm_connector.c:drm_mode_getconnector
  - drivers/gpu/drm/drm_connector.c:drm_connector_privacy_screen_notifier
  - drivers/gpu/drm/drm_connector.c:drm_connector_set_link_status_property
  - drivers/gpu/drm/drm_crtc.c:drm_mode_getcrtc
  - drivers/gpu/drm/drm_crtc.c:drm_mode_getcrtc
  - drivers/gpu/drm/drm_encoder.c:drm_mode_getencoder
  - drivers/gpu/drm/drm_plane.c:drm_mode_getplane
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_open
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_open
  - drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb
```
**Symbols:**

```
ffffffff81ca86a0-ffffffff81ca86d7: drm_modeset_unlock (STB_GLOBAL)
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
