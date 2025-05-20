# Function: <code>drm_dev_is_unplugged</code>

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
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c5a8)
Location: include/drm/drm_drv.h:506
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9d1b2)
Location: include/drm/drm_drv.h:506
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
```
```
In drivers/gpu/drm/drm_ioctl.c (ffffffff81c9e7a7)
Location: include/drm/drm_drv.h:506
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl_kernel
```
```
In drivers/accel/drm_accel.c (ffffffff81cbcbf2)
Location: include/drm/drm_drv.h:506
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_minor_acquire
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
