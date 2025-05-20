# Function: <code>drm_property_create_range</code>

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
struct drm_property *drm_property_create_range(struct drm_device *dev, u32 flags, const char *name, uint64_t min, uint64_t max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_property.c (ffffffff81cae125)
Location: drivers/gpu/drm/drm_property.c:277
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_create_bool
Direct callers:
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_zpos_immutable_property
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_zpos_property
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_alpha_property
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_max_bpc_property
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_suggested_offset_properties
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_suggested_offset_properties
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_properties_legacy
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_margin_properties
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_margin_properties
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_margin_properties
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tv_margin_properties
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder
```
**Symbols:**

```
ffffffff81cae4f0-ffffffff81cae537: drm_property_create_range (STB_GLOBAL)
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
