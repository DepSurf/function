# Function: <code>drm_dev_put</code>

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
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void drm_dev_put(struct drm_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c776)
Location: drivers/gpu/drm/drm_drv.c:816
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_stub_open
  - drivers/gpu/drm/drm_drv.c:devm_drm_dev_init_release
  - drivers/gpu/drm/drm_drv.c:devm_drm_dev_init_release
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
Direct callers:
  - drivers/gpu/drm/drm_atomic.c:__drm_atomic_state_free
  - drivers/gpu/drm/drm_atomic.c:__drm_atomic_state_free
  - drivers/gpu/drm/drm_client.c:drm_client_release
  - drivers/gpu/drm/drm_drv.c:drm_stub_open
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release
  - drivers/accel/drm_accel.c:accel_stub_open
  - drivers/accel/drm_accel.c:accel_open
  - drivers/accel/drm_accel.c:accel_minor_acquire
```
**Symbols:**

```
ffffffff81c8c200-ffffffff81c8c289: drm_dev_put.part.0 (STB_LOCAL)
ffffffff81c8c490-ffffffff81c8c51e: drm_dev_put (STB_GLOBAL)
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
