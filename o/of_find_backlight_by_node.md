# Function: <code>of_find_backlight_by_node</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight_by_node(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (ffff800010741c24)
Location: drivers/video/backlight/backlight.c:592
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:of_find_backlight
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
**Symbols:**

```
ffff800010741b98-ffff800010741be4: of_find_backlight_by_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight_by_node(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (c08c667c)
Location: drivers/video/backlight/backlight.c:592
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:of_find_backlight
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
**Symbols:**

```
c08c65fc-c08c663c: of_find_backlight_by_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct backlight_device *of_find_backlight_by_node(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/backlight/backlight.c (c0000000008a1e40)
Location: drivers/video/backlight/backlight.c:592
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:of_find_backlight
```
**Symbols:**

```
c0000000008a1d90-c0000000008a1de8: of_find_backlight_by_node (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
