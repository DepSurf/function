# Function: <code>drm_syncobj_replace_fence</code>

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
void drm_syncobj_replace_fence(struct drm_syncobj *syncobj, struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81caf6a0)
Location: drivers/gpu/drm/drm_syncobj.c:371
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_reset_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_free
```
**Symbols:**

```
ffffffff81caf6a0-ffffffff81caf7fa: drm_syncobj_replace_fence (STB_GLOBAL)
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
