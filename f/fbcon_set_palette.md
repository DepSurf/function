# Function: <code>fbcon_set_palette</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fbcon_set_palette(struct vc_data *vc, unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814605c0)
Location: drivers/video/console/fbcon.c:2655
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_debug_enter
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff814605c0-ffffffff8146071f: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814ae4c0)
Location: drivers/video/console/fbcon.c:2654
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_debug_enter
  - drivers/video/console/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff814ae4c0-ffffffff814ae61f: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814d05b0)
Location: drivers/video/console/fbcon.c:2665
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_debug_enter
  - drivers/video/console/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff814d05b0-ffffffff814d070f: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814dec30)
Location: drivers/video/console/fbcon.c:2663
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_debug_enter
  - drivers/video/console/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff814dec30-ffffffff814ded8c: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81526f60)
Location: drivers/video/fbdev/core/fbcon.c:2679
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff81526f60-ffffffff815270bc: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155cbf0)
Location: drivers/video/fbdev/core/fbcon.c:2687
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff8155cbf0-ffffffff8155cd40: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81572940)
Location: drivers/video/fbdev/core/fbcon.c:2706
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff81572940-ffffffff81572a72: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a3000)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff815a3000-ffffffff815a3116: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c3e80)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff815c3e80-ffffffff815c3f96: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8166e210)
Location: drivers/video/fbdev/core/fbcon.c:2556
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff8166e210-ffffffff8166e326: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8168e7c0)
Location: drivers/video/fbdev/core/fbcon.c:2518
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff8168e7c0-ffffffff8168e8d6: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816714c0)
Location: drivers/video/fbdev/core/fbcon.c:2510
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff816714c0-ffffffff816715d6: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2555
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff816e5340-ffffffff816e55c2: fbcon_set_palette (STB_LOCAL)
ffffffff81cec6bc-ffffffff81cec6db: fbcon_set_palette.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2570
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff81812610-ffffffff818128cb: fbcon_set_palette (STB_LOCAL)
ffffffff81eb3cd9-ffffffff81eb3cf8: fbcon_set_palette.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2568
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff819416a0-ffffffff8194195b: fbcon_set_palette (STB_LOCAL)
ffffffff820907b2-ffffffff820907d1: fbcon_set_palette.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2561
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff81985c80-ffffffff81985f3b: fbcon_set_palette (STB_LOCAL)
ffffffff82110ab9-ffffffff82110ad8: fbcon_set_palette.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2561
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff819cfba0-ffffffff819cfe5b: fbcon_set_palette (STB_LOCAL)
ffffffff821ee8eb-ffffffff821ee90a: fbcon_set_palette.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff80001074cde8)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffff80001074cde8-ffff80001074cf04: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08cfe40)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
c08cfe40-c08cff4c: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008af960)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
c0000000008af960-c0000000008afb0c: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fad00)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffe0004fad00-ffffffe0004fae0e: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815b7fd0)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff815b7fd0-ffffffff815b80e6: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a6db0)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff815a6db0-ffffffff815a6ec6: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815b8560)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff815b8560-ffffffff815b8676: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_set_palette(struct vc_data *vc, const unsigned char *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d1fc0)
Location: drivers/video/fbdev/core/fbcon.c:2723
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff815d1fc0-ffffffff815d20d6: fbcon_set_palette (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char *table</code> ➡️ <code>const unsigned char *table</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
