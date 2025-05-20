# Function: <code>drm_plane_index</code>

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
In drivers/gpu/drm/drm_atomic.c (ffffffff81c788f5)
Location: include/drm/drm_plane.h:894
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_plane_state
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (0)
Location: include/drm/drm_plane.h:894
Inline: True
```
```
In drivers/gpu/drm/drm_blend.c (0)
Location: include/drm/drm_plane.h:894
Inline: True
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c8263f)
Location: include/drm/drm_plane.h:894
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_atomic
```
```
In drivers/gpu/drm/drm_framebuffer.c (0)
Location: include/drm/drm_plane.h:894
Inline: True
```
```
In drivers/gpu/drm/drm_mode_config.c (0)
Location: include/drm/drm_plane.h:894
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cbf94a)
Location: include/drm/drm_plane.h:894
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_update_legacy_modeset_state
```
```
In drivers/gpu/drm/drm_simple_kms_helper.c (ffffffff81ccfdb5)
Location: include/drm/drm_plane.h:894
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_simple_kms_helper.c:drm_simple_kms_plane_atomic_update
  - drivers/gpu/drm/drm_simple_kms_helper.c:drm_simple_kms_plane_atomic_check
```
```
In drivers/gpu/drm/tiny/simpledrm.c (ffffffff81cd6955)
Location: include/drm/drm_plane.h:894
Inline: True
Inline callers:
  - drivers/gpu/drm/tiny/simpledrm.c:simpledrm_primary_plane_helper_atomic_update
  - drivers/gpu/drm/tiny/simpledrm.c:simpledrm_primary_plane_helper_atomic_check
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
