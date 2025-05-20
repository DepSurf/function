# Function: <code>devm_aperture_acquire_for_platform_device</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_aperture_acquire_for_platform_device(struct platform_device *pdev, resource_size_t base, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff8192ec80)
Location: drivers/video/aperture.c:239
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff8192ec80-ffffffff8192ee09: devm_aperture_acquire_for_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_aperture_acquire_for_platform_device(struct platform_device *pdev, resource_size_t base, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff81972f50)
Location: drivers/video/aperture.c:239
Inline: False
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
```
**Symbols:**

```
ffffffff81972f50-ffffffff819730e0: devm_aperture_acquire_for_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_aperture_acquire_for_platform_device(struct platform_device *pdev, resource_size_t base, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff819bcfc0)
Location: drivers/video/aperture.c:239
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_aperture.c:devm_aperture_acquire_from_firmware
```
**Symbols:**

```
ffffffff819bcfc0-ffffffff819bd150: devm_aperture_acquire_for_platform_device (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
