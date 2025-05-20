# Function: <code>drm_connector_put</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7a4ef)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7c52b)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_set_crtc_for_connector
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c845b3)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_release
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c870df)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_connector_oob_hotplug_event
  - drivers/gpu/drm/drm_connector.c:drm_mode_getconnector
```
```
In drivers/gpu/drm/drm_crtc.c (ffffffff81c8ac29)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
```
```
In drivers/gpu/drm/drm_mode_config.c (ffffffff81ca2483)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (ffffffff81cc58a4)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_connector_destroy_state
```
```
In drivers/gpu/drm/drm_crtc_helper.c (ffffffff81cc7a1c)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
  - drivers/gpu/drm/drm_crtc_helper.c:drm_crtc_helper_set_config
```
```
In drivers/gpu/drm/drm_probe_helper.c (ffffffff81cce30c)
Location: include/drm/drm_connector.h:1961
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_hpd_irq_event
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
