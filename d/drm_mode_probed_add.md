# Function: <code>drm_mode_probed_add</code>

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
void drm_mode_probed_add(struct drm_connector *connector, struct drm_display_mode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_modes.c (ffffffff81ca51d0)
Location: drivers/gpu/drm/drm_modes.c:111
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_edid.c:drm_add_modes_noedid
  - drivers/gpu/drm/drm_edid.c:add_cea_modes
  - drivers/gpu/drm/drm_edid.c:add_cea_modes
  - drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes
  - drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes
  - drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes
  - drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes
  - drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes
  - drivers/gpu/drm/drm_edid.c:add_alternate_cea_modes
  - drivers/gpu/drm/drm_edid.c:drm_cvt_modes
  - drivers/gpu/drm/drm_edid.c:do_standard_modes
  - drivers/gpu/drm/drm_probe_helper.c:drm_connector_helper_tv_get_modes
  - drivers/gpu/drm/drm_probe_helper.c:drm_connector_helper_tv_get_modes
  - drivers/gpu/drm/drm_probe_helper.c:drm_connector_helper_get_modes_fixed
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
```
**Symbols:**

```
ffffffff81ca51d0-ffffffff81ca522e: drm_mode_probed_add (STB_GLOBAL)
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
