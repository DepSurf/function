# Function: <code>drm_atomic_get_crtc_state</code>

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
struct drm_crtc_state *drm_atomic_get_crtc_state(struct drm_atomic_state *state, struct drm_crtc *crtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c78790)
Location: drivers/gpu/drm/drm_atomic.c:346
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_atomic.c:__drm_atomic_helper_set_config
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_add_affected_connectors
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_connector_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_plane_state
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_property
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_commit_dpms
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_connector
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_plane
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_plane
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_atomic_helper.c:page_flip_common
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_duplicate_state
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_disable_all
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_entry_work
```
**Symbols:**

```
ffffffff81c78790-ffffffff81c788d8: drm_atomic_get_crtc_state (STB_GLOBAL)
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
