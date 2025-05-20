# Function: <code>drm_framebuffer_lookup</code>

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
struct drm_framebuffer *drm_framebuffer_lookup(struct drm_device *dev, struct drm_file *file_priv, uint32_t id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9ae77)
Location: drivers/gpu/drm/drm_framebuffer.c:899
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_dirtyfb_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb2_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_closefb_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb
Direct callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_connector_set_property
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property
  - drivers/gpu/drm/drm_client.c:drm_client_buffer_addfb
  - drivers/gpu/drm/drm_crtc.c:drm_mode_setcrtc
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
  - drivers/gpu/drm/drm_plane.c:drm_mode_setplane
```
**Symbols:**

```
ffffffff81c98ed0-ffffffff81c98efc: drm_framebuffer_lookup (STB_GLOBAL)
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
