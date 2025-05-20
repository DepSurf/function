# Function: <code>drm_property_blob_get</code>

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
struct drm_property_blob *drm_property_blob_get(struct drm_property_blob *blob);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_property.c (ffffffff81cae642)
Location: drivers/gpu/drm/drm_property.c:632
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id
Direct callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_mode_prop_for_crtc
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_connector_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_duplicate_state
```
**Symbols:**

```
ffffffff81cadc60-ffffffff81cadc81: drm_property_blob_get (STB_GLOBAL)
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
