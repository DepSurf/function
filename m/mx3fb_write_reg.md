# Function: <code>mx3fb_write_reg</code>

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
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/mx3fb.c (ffff8000107609ac)
Location: drivers/video/fbdev/mx3fb.c:348
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:sdc_set_brightness
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/mx3fb.c (c08e3350)
Location: drivers/video/fbdev/mx3fb.c:348
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:sdc_set_brightness
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
</details>
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
