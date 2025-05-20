# Function: <code>drm_encoder_mask</code>

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
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c835d7)
Location: include/drm/drm_encoder.h:284
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_pick_crtcs
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c8958c)
Location: include/drm/drm_encoder.h:284
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_getconnector
  - drivers/gpu/drm/drm_connector.c:drm_connector_has_possible_encoder
  - drivers/gpu/drm/drm_connector.c:drm_connector_attach_encoder
```
```
In drivers/gpu/drm/drm_mode_config.c (ffffffff81ca3398)
Location: include/drm/drm_encoder.h:284
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_validate
  - drivers/gpu/drm/drm_mode_config.c:validate_encoder_possible_clones
  - drivers/gpu/drm/drm_mode_config.c:validate_encoder_possible_clones
  - drivers/gpu/drm/drm_mode_config.c:validate_encoder_possible_clones
  - drivers/gpu/drm/drm_mode_config.c:validate_encoder_possible_clones
  - drivers/gpu/drm/drm_mode_config.c:validate_encoder_possible_clones
  - drivers/gpu/drm/drm_mode_config.c:validate_encoder_possible_clones
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc1f2d)
Location: include/drm/drm_encoder.h:284
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:set_best_encoder
  - drivers/gpu/drm/drm_atomic_helper.c:set_best_encoder
  - drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders
  - drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders
  - drivers/gpu/drm/drm_atomic_helper.c:handle_conflicting_encoders
```
```
In drivers/gpu/drm/drm_crtc_helper.c (ffffffff81cc73e2)
Location: include/drm/drm_encoder.h:284
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc_helper.c:drm_connector_get_single_encoder
```
```
In drivers/gpu/drm/drm_probe_helper.c (ffffffff81cce66d)
Location: include/drm/drm_encoder.h:284
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_probe_helper.c:__drm_helper_update_and_validate
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
