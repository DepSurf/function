# Function: <code>drm_crtc_commit_put</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7a581)
Location: include/drm/drm_atomic.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc2f23)
Location: include/drm/drm_atomic.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_hw_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:release_crtc_commit
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (ffffffff81cc58b9)
Location: include/drm/drm_atomic.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_connector_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state
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
