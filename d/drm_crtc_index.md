# Function: <code>drm_crtc_index</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7a195)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_add_affected_planes
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_check
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_crtc_state
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7d137)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_crtc_set_property
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_connector
```
```
In drivers/gpu/drm/drm_blend.c (ffffffff81c7f84a)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_blend.c:drm_atomic_normalize_zpos
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c825eb)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_atomic
```
```
In drivers/gpu/drm/drm_crtc.c (0)
Location: include/drm/drm_crtc.h:1265
Inline: True
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9999b)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb
```
```
In drivers/gpu/drm/drm_mode_config.c (0)
Location: include/drm/drm_crtc.h:1265
Inline: True
```
```
In drivers/gpu/drm/drm_plane.c (0)
Location: include/drm/drm_crtc.h:1265
Inline: True
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb7498)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_get_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_handle_vblank
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_restore
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_on
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_set_max_vblank_count
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_reset
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_wait_one_vblank
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_send_vblank_event
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_arm_vblank_event
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_next_vblank_start
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_count_and_time
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_count
  - drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_waitqueue
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_accurate_vblank_count
```
```
In drivers/gpu/drm/drm_vblank_work.c (ffffffff81cb7b6c)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_init
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3574)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_page_flip_target
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_planes_on_crtc
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:disable_outputs
  - drivers/gpu/drm/drm_atomic_helper.c:disable_outputs
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_planes
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_planes
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset
  - drivers/gpu/drm/drm_atomic_helper.c:mode_valid
  - drivers/gpu/drm/drm_atomic_helper.c:mode_fixup
  - drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing
  - drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing
  - drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing
  - drivers/gpu/drm/drm_atomic_helper.c:update_connector_routing
  - drivers/gpu/drm/drm_atomic_helper.c:set_best_encoder
  - drivers/gpu/drm/drm_atomic_helper.c:set_best_encoder
  - drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (ffffffff81cc4bb6)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_connector_tv_check
```
```
In drivers/gpu/drm/drm_crtc_helper.c (ffffffff81cc6565)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_atomic_check
```
```
In drivers/gpu/drm/drm_damage_helper.c (ffffffff81cc81ae)
Location: include/drm/drm_crtc.h:1265
Inline: True
```
```
In drivers/gpu/drm/drm_probe_helper.c (0)
Location: include/drm/drm_crtc.h:1265
Inline: True
```
```
In drivers/gpu/drm/drm_simple_kms_helper.c (ffffffff81cd03aa)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_simple_kms_helper.c:drm_simple_kms_plane_atomic_check
  - drivers/gpu/drm/drm_simple_kms_helper.c:drm_simple_kms_crtc_check
```
```
In drivers/gpu/drm/bridge/panel.c (ffffffff81cd0743)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/bridge/panel.c:panel_bridge_atomic_post_disable
  - drivers/gpu/drm/bridge/panel.c:panel_bridge_atomic_disable
  - drivers/gpu/drm/bridge/panel.c:panel_bridge_atomic_enable
  - drivers/gpu/drm/bridge/panel.c:panel_bridge_atomic_pre_enable
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd2efe)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fb_helper.c:__drm_fb_helper_find_sizes
```
```
In drivers/gpu/drm/tiny/simpledrm.c (ffffffff81cd6b64)
Location: include/drm/drm_crtc.h:1265
Inline: True
Inline callers:
  - drivers/gpu/drm/tiny/simpledrm.c:simpledrm_primary_plane_helper_atomic_check
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
