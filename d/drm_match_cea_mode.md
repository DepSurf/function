# Function: <code>drm_match_cea_mode</code>

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
u8 drm_match_cea_mode(const struct drm_display_mode *to_match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_edid.c (ffffffff81c8dca0)
Location: drivers/gpu/drm/drm_edid.c:4298
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_edid.c:drm_hdmi_avi_infoframe_quant_range
  - drivers/gpu/drm/drm_edid.c:drm_hdmi_avi_infoframe_from_display_mode
  - drivers/gpu/drm/drm_edid.c:drm_hdmi_avi_infoframe_from_display_mode
  - drivers/gpu/drm/drm_edid.c:add_alternate_cea_modes
  - drivers/gpu/drm/drm_modes.c:drm_mode_is_420
  - drivers/gpu/drm/drm_modes.c:drm_mode_is_420_also
```
**Symbols:**

```
ffffffff81c8dca0-ffffffff81c8de77: drm_match_cea_mode (STB_GLOBAL)
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
