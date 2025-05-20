# Function: <code>drm_mode_copy</code>

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
void drm_mode_copy(struct drm_display_mode *dst, const struct drm_display_mode *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_modes.c (ffffffff81ca5c43)
Location: drivers/gpu/drm/drm_modes.c:1416
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modes.c:drm_connector_list_update
  - drivers/gpu/drm/drm_modes.c:drm_mode_duplicate
  - drivers/gpu/drm/drm_modes.c:drm_mode_init
Direct callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_for_crtc
  - drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants
  - drivers/gpu/drm/drm_atomic_helper.c:mode_fixup
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_mode
```
**Symbols:**

```
ffffffff81ca4e60-ffffffff81ca4f05: drm_mode_copy (STB_GLOBAL)
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
