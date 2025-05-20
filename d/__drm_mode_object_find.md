# Function: <code>__drm_mode_object_find</code>

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
struct drm_mode_object *__drm_mode_object_find(struct drm_device *dev, struct drm_file *file_priv, uint32_t id, uint32_t type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca4100)
Location: drivers/gpu/drm/drm_mode_object.c:136
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_dirtyfb_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb2_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_getfb
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_closefb_ioctl
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_get_properties_ioctl
  - drivers/gpu/drm/drm_property.c:drm_property_change_valid_get
  - drivers/gpu/drm/drm_property.c:drm_property_change_valid_get
  - drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_getblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_property_replace_blob_from_id
```
**Symbols:**

```
ffffffff81ca4100-ffffffff81ca4208: __drm_mode_object_find (STB_GLOBAL)
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
