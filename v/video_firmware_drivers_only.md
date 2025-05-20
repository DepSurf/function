# Function: <code>video_firmware_drivers_only</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool video_firmware_drivers_only();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/nomodeset.c (0)
Location: drivers/video/nomodeset.c:10
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_modesetting_disabled
```
**Symbols:**

```
ffffffff820902c0-ffffffff820902ea: video_firmware_drivers_only.cold (STB_LOCAL)
ffffffff8192ee20-ffffffff8192ee42: video_firmware_drivers_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool video_firmware_drivers_only();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/nomodeset.c (0)
Location: drivers/video/nomodeset.c:10
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_modesetting_disabled
```
**Symbols:**

```
ffffffff82110620-ffffffff8211064a: video_firmware_drivers_only.cold (STB_LOCAL)
ffffffff81973290-ffffffff819732b2: video_firmware_drivers_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool video_firmware_drivers_only();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/nomodeset.c (0)
Location: drivers/video/nomodeset.c:10
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_modesetting_disabled
```
**Symbols:**

```
ffffffff821ee41d-ffffffff821ee447: video_firmware_drivers_only.cold (STB_LOCAL)
ffffffff819bd300-ffffffff819bd322: video_firmware_drivers_only (STB_GLOBAL)
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
