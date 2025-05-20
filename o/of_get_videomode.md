# Function: <code>of_get_videomode</code>

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
int of_get_videomode(struct device_node *np, struct videomode *vm, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/of_videomode.c (ffff8000107622c0)
Location: drivers/video/of_videomode.c:30
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmon.c:of_get_fb_videomode
```
**Symbols:**

```
ffff8000107622c0-ffff800010762348: of_get_videomode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_get_videomode(struct device_node *np, struct videomode *vm, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/of_videomode.c (c08e49b8)
Location: drivers/video/of_videomode.c:30
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmon.c:of_get_fb_videomode
```
**Symbols:**

```
c08e49b8-c08e4a28: of_get_videomode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_get_videomode(struct device_node *np, struct videomode *vm, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/of_videomode.c (c0000000008c6070)
Location: drivers/video/of_videomode.c:30
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmon.c:of_get_fb_videomode
```
**Symbols:**

```
c0000000008c6070-c0000000008c6120: of_get_videomode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_get_videomode(struct device_node *np, struct videomode *vm, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/of_videomode.c (ffffffe000508e1e)
Location: drivers/video/of_videomode.c:30
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmon.c:of_get_fb_videomode
```
**Symbols:**

```
ffffffe000508e1e-ffffffe000508e98: of_get_videomode (STB_GLOBAL)
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
