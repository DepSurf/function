# Function: <code>drm_connector_index</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c78e5f)
Location: include/drm/drm_connector.h:1915
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_connector_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_new_crtc_for_encoder
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_old_crtc_for_encoder
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7d409)
Location: include/drm/drm_connector.h:1915
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cbe955)
Location: include/drm/drm_connector.h:1915
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_wb_connector_state
  - drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (ffffffff81cc4b85)
Location: include/drm/drm_connector.h:1915
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_connector_tv_check
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
