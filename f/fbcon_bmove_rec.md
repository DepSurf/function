# Function: <code>fbcon_bmove_rec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fbcon_bmove_rec(struct vc_data *vc, struct display *p, int sy, int sx, int dy, int dx, int height, int width, u_int y_break);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff8145faa0)
Location: drivers/video/console/fbcon.c:2026
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_bmove_rec
  - drivers/video/console/fbcon.c:fbcon_bmove_rec
  - drivers/video/console/fbcon.c:fbcon_bmove_rec
  - drivers/video/console/fbcon.c:fbcon_bmove_rec
  - drivers/video/console/fbcon.c:fbcon_bmove_rec
  - drivers/video/console/fbcon.c:fbcon_bmove_rec
  - drivers/video/console/fbcon.c:fbcon_bmove_rec
  - drivers/video/console/fbcon.c:fbcon_bmove
```
**Symbols:**

```
ffffffff8145faa0-ffffffff8145fd0d: fbcon_bmove_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814b1f70)
Location: drivers/video/console/fbcon.c:2025
Inline: True
```
**Symbols:**

```
ffffffff814b1f70-ffffffff814b215c: fbcon_bmove_rec.constprop.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814d3f50)
Location: drivers/video/console/fbcon.c:2028
Inline: True
```
**Symbols:**

```
ffffffff814d3f50-ffffffff814d413c: fbcon_bmove_rec.constprop.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814dd330)
Location: drivers/video/console/fbcon.c:2026
Inline: True
```
**Symbols:**

```
ffffffff814dd330-ffffffff814dd4eb: fbcon_bmove_rec.constprop.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81526430)
Location: drivers/video/fbdev/core/fbcon.c:2042
Inline: True
```
**Symbols:**

```
ffffffff81526430-ffffffff815265f0: fbcon_bmove_rec.constprop.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155c0f0)
Location: drivers/video/fbdev/core/fbcon.c:2049
Inline: True
```
**Symbols:**

```
ffffffff8155c0f0-ffffffff8155c2c0: fbcon_bmove_rec.constprop.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815746b0)
Location: drivers/video/fbdev/core/fbcon.c:2068
Inline: True
```
**Symbols:**

```
ffffffff815746b0-ffffffff81574880: fbcon_bmove_rec.constprop.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a4ac0)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
ffffffff815a4ac0-ffffffff815a4c96: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c5990)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
ffffffff815c5990-ffffffff815c5b66: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8166f150)
Location: drivers/video/fbdev/core/fbcon.c:1920
Inline: True
```
**Symbols:**

```
ffffffff8166f150-ffffffff8166f325: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8168f670)
Location: drivers/video/fbdev/core/fbcon.c:1916
Inline: True
```
**Symbols:**

```
ffffffff8168f670-ffffffff8168f845: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672390)
Location: drivers/video/fbdev/core/fbcon.c:1908
Inline: True
```
**Symbols:**

```
ffffffff81672390-ffffffff8167255f: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:1908
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:1676
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:1671
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:1669
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:1671
Inline: False
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff80001074f2f8)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
ffff80001074f2f8-ffff80001074f510: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d147c)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
c08d147c-c08d164c: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_bmove_rec(struct vc_data *vc, struct fbcon_display *p, int sy, int sx, int dy, int dx, int height, int width, u_int y_break);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008ae540)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_bmove_rec
  - drivers/video/fbdev/core/fbcon.c:fbcon_bmove_rec
  - drivers/video/fbdev/core/fbcon.c:fbcon_bmove_rec
  - drivers/video/fbdev/core/fbcon.c:fbcon_bmove_rec
```
**Symbols:**

```
c0000000008ae540-c0000000008ae7fc: fbcon_bmove_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fdb90)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
ffffffe0004fdb90-ffffffe0004fdd24: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815b9a90)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
ffffffff815b9a90-ffffffff815b9c66: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a8870)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
ffffffff815a8870-ffffffff815a8a46: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ba020)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
ffffffff815ba020-ffffffff815ba1f6: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d3ad0)
Location: drivers/video/fbdev/core/fbcon.c:2096
Inline: True
```
**Symbols:**

```
ffffffff815d3ad0-ffffffff815d3ca6: fbcon_bmove_rec.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
