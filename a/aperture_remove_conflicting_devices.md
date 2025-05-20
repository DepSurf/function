# Function: <code>aperture_remove_conflicting_devices</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int aperture_remove_conflicting_devices(resource_size_t base, resource_size_t size, bool primary, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff8192eba9)
Location: drivers/video/aperture.c:285
Inline: True
Inline callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
```
**Symbols:**

```
ffffffff8192eab0-ffffffff8192eb0f: aperture_remove_conflicting_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aperture_remove_conflicting_devices(resource_size_t base, resource_size_t size, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff81972cc0)
Location: drivers/video/aperture.c:284
Inline: False
```
**Symbols:**

```
ffffffff81972cc0-ffffffff81972cf1: aperture_remove_conflicting_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aperture_remove_conflicting_devices(resource_size_t base, resource_size_t size, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff819bcd30)
Location: drivers/video/aperture.c:284
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_aperture.c:drm_aperture_remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff819bcd30-ffffffff819bcd61: aperture_remove_conflicting_devices (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool primary</code>
</li>
<li>
<b>Param reordered. </b>
<code>base, size, primary, name</code> ➡️ <code>base, size, name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
