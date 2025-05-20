# Function: <code>drm_edid_free</code>

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
void drm_edid_free(const struct drm_edid *drm_edid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_edid.c (ffffffff81c95c32)
Location: drivers/gpu/drm/drm_edid.c:2594
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:drm_edid_connector_add_modes
  - drivers/gpu/drm/drm_edid.c:drm_edid_connector_add_modes
  - drivers/gpu/drm/drm_edid.c:_drm_do_get_edid
  - drivers/gpu/drm/drm_edid.c:_drm_do_get_edid
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_connector_update
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_connector_update
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_reset
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_reset
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_set
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_set
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_set
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_set
Direct callers:
  - drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware
  - drivers/gpu/drm/drm_probe_helper.c:drm_connector_helper_get_modes
```
**Symbols:**

```
ffffffff81c8f6f0-ffffffff81c8f726: drm_edid_free (STB_GLOBAL)
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
