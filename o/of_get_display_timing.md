# Function: <code>of_get_display_timing</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_get_display_timing(const struct device_node *np, const char *name, struct display_timing *dt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (ffff800010761f40)
Location: drivers/video/of_display_timing.c:118
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_get_dpi_panel_mode
```
**Symbols:**

```
ffff800010761f40-ffff800010761fb8: of_get_display_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_get_display_timing(const struct device_node *np, const char *name, struct display_timing *dt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (c08e4690)
Location: drivers/video/of_display_timing.c:118
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_get_dpi_panel_mode
```
**Symbols:**

```
c08e4690-c08e46ec: of_get_display_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_get_display_timing(const struct device_node *np, const char *name, struct display_timing *dt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (c0000000008c5be0)
Location: drivers/video/of_display_timing.c:118
Inline: False
```
**Symbols:**

```
c0000000008c5be0-c0000000008c5c74: of_get_display_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_get_display_timing(const struct device_node *np, const char *name, struct display_timing *dt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (ffffffe000508aa2)
Location: drivers/video/of_display_timing.c:118
Inline: False
```
**Symbols:**

```
ffffffe000508aa2-ffffffe000508b02: of_get_display_timing (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
