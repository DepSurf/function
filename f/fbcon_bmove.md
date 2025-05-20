# Function: <code>fbcon_bmove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fbcon_bmove(struct vc_data *vc, int sy, int sx, int dy, int dx, int height, int width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff8145fd10)
Location: drivers/video/console/fbcon.c:2003
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff8145fd10-ffffffff8145fdd3: fbcon_bmove (STB_LOCAL)
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
In drivers/video/console/fbcon.c (ffffffff814b2160)
Location: drivers/video/console/fbcon.c:2002
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff814b2160-ffffffff814b221f: fbcon_bmove.constprop.28 (STB_LOCAL)
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
In drivers/video/console/fbcon.c (ffffffff814d4140)
Location: drivers/video/console/fbcon.c:2005
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff814d4140-ffffffff814d41ff: fbcon_bmove.constprop.28 (STB_LOCAL)
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
In drivers/video/console/fbcon.c (ffffffff814de710)
Location: drivers/video/console/fbcon.c:2003
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff814de710-ffffffff814de7cb: fbcon_bmove.constprop.29 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff81526a40)
Location: drivers/video/fbdev/core/fbcon.c:2019
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff81526a40-ffffffff81526afb: fbcon_bmove.constprop.29 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155c700)
Location: drivers/video/fbdev/core/fbcon.c:2026
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff8155c700-ffffffff8155c7ac: fbcon_bmove.constprop.28 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff81574880)
Location: drivers/video/fbdev/core/fbcon.c:2045
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff81574880-ffffffff815748fe: fbcon_bmove.constprop.27 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815a4ca0)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff815a4ca0-ffffffff815a4d27: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815c5b70)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff815c5b70-ffffffff815c5bf7: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8166f330)
Location: drivers/video/fbdev/core/fbcon.c:1897
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff8166f330-ffffffff8166f3b7: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8168f850)
Location: drivers/video/fbdev/core/fbcon.c:1893
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff8168f850-ffffffff8168f8d7: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff81672560)
Location: drivers/video/fbdev/core/fbcon.c:1885
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff81672560-ffffffff816725ef: fbcon_bmove.constprop.0 (STB_LOCAL)
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
Location: drivers/video/fbdev/core/fbcon.c:1885
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
Location: drivers/video/fbdev/core/fbcon.c:1718
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
Location: drivers/video/fbdev/core/fbcon.c:1713
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
Location: drivers/video/fbdev/core/fbcon.c:1711
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
Location: drivers/video/fbdev/core/fbcon.c:1713
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
In drivers/video/fbdev/core/fbcon.c (ffff80001074f510)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffff80001074f510-ffff80001074f5d4: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (c08d164c)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
c08d164c-c08d1700: fbcon_bmove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b3c70)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
c0000000008b3c70-c0000000008b3d50: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fdd24)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffe0004fdd24-ffffffe0004fddd2: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815b9c70)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff815b9c70-ffffffff815b9cf7: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815a8a50)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff815a8a50-ffffffff815a8ad7: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815ba200)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff815ba200-ffffffff815ba287: fbcon_bmove.constprop.0 (STB_LOCAL)
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815d3cb0)
Location: drivers/video/fbdev/core/fbcon.c:2073
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
```
**Symbols:**

```
ffffffff815d3cb0-ffffffff815d3d37: fbcon_bmove.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
