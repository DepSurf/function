# Function: <code>update_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f7920)
Location: drivers/tty/vt/vt.c:400
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff814f7920-ffffffff814f79a4: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815487c0)
Location: drivers/tty/vt/vt.c:400
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff815487c0-ffffffff81548849: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81575280)
Location: drivers/tty/vt/vt.c:389
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81575280-ffffffff81575309: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81589120)
Location: drivers/tty/vt/vt.c:389
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81589120-ffffffff8158919a: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815edc40)
Location: drivers/tty/vt/vt.c:391
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff815edc40-ffffffff815edcba: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81627110)
Location: drivers/tty/vt/vt.c:391
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81627110-ffffffff81627178: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816446a0)
Location: drivers/tty/vt/vt.c:693
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vt.c:csi_J
```
**Symbols:**

```
ffffffff816446a0-ffffffff81644714: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:693
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff8167f088-ffffffff8167f09b: update_region.cold (STB_LOCAL)
ffffffff816792c0-ffffffff81679331: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169bab0)
Location: drivers/tty/vt/vt.c:693
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff8169bab0-ffffffff8169bb1f: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174e4a0)
Location: drivers/tty/vt/vt.c:699
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff8174e4a0-ffffffff8174e50f: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81769a70)
Location: drivers/tty/vt/vt.c:692
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81769a70-ffffffff81769adf: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174d660)
Location: drivers/tty/vt/vt.c:692
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff8174d660-ffffffff8174d6cf: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817cf7a0)
Location: drivers/tty/vt/vt.c:688
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff817cf7a0-ffffffff817cf82b: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190d640)
Location: drivers/tty/vt/vt.c:688
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff8190d640-ffffffff8190d6d4: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a68330)
Location: drivers/tty/vt/vt.c:688
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81a68330-ffffffff81a683c4: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab2a10)
Location: drivers/tty/vt/vt.c:636
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81ab2a10-ffffffff81ab2aa4: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b056f0)
Location: drivers/tty/vt/vt.c:635
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81b056f0-ffffffff81b05784: update_region (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010873018)
Location: drivers/tty/vt/vt.c:693
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffff800010873018-ffff8000108730b0: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0975e2c)
Location: drivers/tty/vt/vt.c:693
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
c0975e2c-c0975ed8: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000913710)
Location: drivers/tty/vt/vt.c:693
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
c000000000913710-c0000000009137f8: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000545750)
Location: drivers/tty/vt/vt.c:693
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffe000545750-ffffffe0005457d8: update_region (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81661510)
Location: drivers/tty/vt/vt.c:693
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81661510-ffffffff8166157f: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81641890)
Location: drivers/tty/vt/vt.c:693
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff81641890-ffffffff816418ff: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168f8f0)
Location: drivers/tty/vt/vt.c:693
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff8168f8f0-ffffffff8168f95f: update_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void update_region(struct vc_data *vc, long unsigned int start, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a9ef0)
Location: drivers/tty/vt/vt.c:693
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/tty/vt/vc_screen.c:vcs_write
```
**Symbols:**

```
ffffffff816a9ef0-ffffffff816a9f5f: update_region (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
