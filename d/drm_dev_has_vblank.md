# Function: <code>drm_dev_has_vblank</code>

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
bool drm_dev_has_vblank(const struct drm_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb745c)
Location: drivers/gpu/drm/drm_vblank.c:566
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_handle_vblank
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_get
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_send_vblank_event
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_next_vblank_start
  - drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants
Direct callers:
  - drivers/gpu/drm/drm_atomic_helper.c:disable_outputs
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_crtc_reset
```
**Symbols:**

```
ffffffff81cb3dc0-ffffffff81cb3ddc: drm_dev_has_vblank (STB_GLOBAL)
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
