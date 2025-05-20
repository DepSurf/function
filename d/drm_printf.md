# Function: <code>drm_printf</code>

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
void drm_printf(struct drm_printer *p, const char *f, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_print.c (ffffffff81cad210)
Location: drivers/gpu/drm/drm_print.c:220
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_connector_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_plane_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_crtc_print_state
  - drivers/gpu/drm/drm_client.c:drm_client_debugfs_internal_clients
  - drivers/gpu/drm/drm_file.c:drm_show_fdinfo
  - drivers/gpu/drm/drm_file.c:drm_show_fdinfo
  - drivers/gpu/drm/drm_file.c:drm_show_fdinfo
  - drivers/gpu/drm/drm_file.c:print_size
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
  - drivers/gpu/drm/drm_mm.c:drm_mm_print
  - drivers/gpu/drm/drm_mm.c:drm_mm_print
  - drivers/gpu/drm/drm_mm.c:drm_mm_print
  - drivers/gpu/drm/drm_mm.c:drm_mm_print
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/gpu/drm/drm_print.c:drm_print_regset32
  - drivers/gpu/drm/drm_print.c:drm_print_bits
  - drivers/gpu/drm/drm_print.c:drm_print_bits
  - drivers/gpu/drm/drm_debugfs.c:bridges_show
  - drivers/gpu/drm/drm_debugfs.c:bridges_show
  - drivers/gpu/drm/drm_debugfs.c:bridges_show
```
**Symbols:**

```
ffffffff81cad210-ffffffff81cad2a9: drm_printf (STB_GLOBAL)
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
