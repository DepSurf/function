# Function: <code>drm_property_replace_blob</code>

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
bool drm_property_replace_blob(struct drm_property_blob **blob, struct drm_property_blob *new_blob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_property.c (ffffffff81cae62f)
Location: drivers/gpu/drm/drm_property.c:739
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id
Direct callers:
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
  - drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb
```
**Symbols:**

```
ffffffff81cadca0-ffffffff81cadcf6: drm_property_replace_blob (STB_GLOBAL)
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
