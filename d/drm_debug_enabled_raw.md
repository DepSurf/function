# Function: <code>drm_debug_enabled_raw</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7b093)
Location: include/drm/drm_print.h:324
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_commit
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c91383)
Location: include/drm/drm_print.h:324
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:connector_bad_edid
```
```
In drivers/gpu/drm/drm_print.c (ffffffff81cada08)
Location: include/drm/drm_print.h:324
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_print.c:___drm_dbg
  - drivers/gpu/drm/drm_print.c:__drm_dev_dbg
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb46d7)
Location: include/drm/drm_print.h:324
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_restore
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_accurate_vblank_count
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
