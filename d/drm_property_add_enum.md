# Function: <code>drm_property_add_enum</code>

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
int drm_property_add_enum(struct drm_property *property, uint64_t value, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_property.c (ffffffff81cae1d0)
Location: drivers/gpu/drm/drm_property.c:390
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_blend_mode_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_scaling_mode_property
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy
  - drivers/gpu/drm/drm_plane.c:drm_create_scaling_filter_prop
  - drivers/gpu/drm/drm_plane.c:drm_create_scaling_filter_prop
  - drivers/gpu/drm/drm_property.c:drm_property_create_bitmask
  - drivers/gpu/drm/drm_property.c:drm_property_create_enum
```
**Symbols:**

```
ffffffff81cae1d0-ffffffff81cae372: drm_property_add_enum (STB_GLOBAL)
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
