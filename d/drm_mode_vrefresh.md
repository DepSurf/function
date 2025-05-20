# Function: <code>drm_mode_vrefresh</code>

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
int drm_mode_vrefresh(const struct drm_display_mode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_modes.c (ffffffff81ca4c30)
Location: drivers/gpu/drm/drm_modes.c:1286
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_client_modeset.c:drm_connector_pick_cmdline_mode
  - drivers/gpu/drm/drm_edid.c:drm_add_modes_noedid
  - drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes
  - drivers/gpu/drm/drm_edid.c:cea_mode_alternate_clock
  - drivers/gpu/drm/drm_edid.c:valid_inferred_mode
  - drivers/gpu/drm/drm_edid.c:valid_inferred_mode
  - drivers/gpu/drm/drm_edid.c:mode_in_range
  - drivers/gpu/drm/drm_edid.c:drm_mode_std
  - drivers/gpu/drm/drm_edid.c:drm_mode_find_dmt
  - drivers/gpu/drm/drm_modes.c:drm_mode_convert_to_umode
  - drivers/gpu/drm/drm_modes.c:drm_mode_compare
  - drivers/gpu/drm/drm_modes.c:drm_mode_compare
  - drivers/gpu/drm/drm_modes.c:drm_mode_prune_invalid
  - drivers/gpu/drm/drm_modes.c:fill_analog_mode
  - drivers/gpu/drm/drm_modes.c:drm_mode_debug_printmodeline
  - drivers/gpu/drm/drm_probe_helper.c:drm_connector_helper_get_modes_fixed
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
```
**Symbols:**

```
ffffffff81ca4c30-ffffffff81ca4c96: drm_mode_vrefresh (STB_GLOBAL)
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
