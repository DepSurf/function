# Function: <code>drm_atomic_state_put</code>

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
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7df4f)
Location: include/drm/drm_atomic.h:488
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c82674)
Location: include/drm/drm_atomic.h:488
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_atomic
```
```
In drivers/gpu/drm/drm_color_mgmt.c (ffffffff81c85085)
Location: include/drm/drm_atomic.h:488
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9992d)
Location: include/drm/drm_atomic.h:488
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca480a)
Location: include/drm/drm_atomic.h:488
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc35ab)
Location: include/drm/drm_atomic.h:488
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_page_flip_target
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_page_flip
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_resume
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_duplicate_state
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_disable_all
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_set_config
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_disable_plane
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_update_plane
  - drivers/gpu/drm/drm_atomic_helper.c:commit_tail
```
```
In drivers/gpu/drm/drm_damage_helper.c (ffffffff81cc8404)
Location: include/drm/drm_atomic.h:488
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (ffffffff81ccfb22)
Location: include/drm/drm_atomic.h:488
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_entry_work
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd3735)
Location: include/drm/drm_atomic.h:488
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
