# Function: <code>vc_resize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f8f10)
Location: drivers/tty/vt/vt.c:981
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_set_all_vcs
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_startup
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff814f8f10-ffffffff814f8f31: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81549590)
Location: drivers/tty/vt/vt.c:980
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/console/fbcon.c:fbcon_set_all_vcs
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81549590-ffffffff815495b1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81575fc0)
Location: drivers/tty/vt/vt.c:974
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/console/fbcon.c:fbcon_set_all_vcs
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81575fc0-ffffffff81575fe1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81589e50)
Location: drivers/tty/vt/vt.c:982
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/console/fbcon.c:fbcon_set_all_vcs
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81589e50-ffffffff81589e71: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ef5a0)
Location: drivers/tty/vt/vt.c:984
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff815ef5a0-ffffffff815ef5c1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81628cc0)
Location: drivers/tty/vt/vt.c:984
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81628cc0-ffffffff81628ce1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816466c0)
Location: drivers/tty/vt/vt.c:1305
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff816466c0-ffffffff816466e1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167acd0)
Location: drivers/tty/vt/vt.c:1313
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff8167acd0-ffffffff8167acf1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169d4c0)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff8169d4c0-ffffffff8169d4e1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174fc00)
Location: drivers/tty/vt/vt.c:1350
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff8174fc00-ffffffff8174fc21: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176bcf0)
Location: drivers/tty/vt/vt.c:1355
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff8176bcf0-ffffffff8176bd11: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174ec00)
Location: drivers/tty/vt/vt.c:1354
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
```
**Symbols:**

```
ffffffff8174ec00-ffffffff8174ec21: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d0aa0)
Location: drivers/tty/vt/vt.c:1360
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
```
**Symbols:**

```
ffffffff817d0aa0-ffffffff817d0ac1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190e9a0)
Location: drivers/tty/vt/vt.c:1360
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
```
**Symbols:**

```
ffffffff8190e9a0-ffffffff8190e9cd: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a69890)
Location: drivers/tty/vt/vt.c:1360
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
```
**Symbols:**

```
ffffffff81a69890-ffffffff81a698bd: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab3f70)
Location: drivers/tty/vt/vt.c:1310
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
```
**Symbols:**

```
ffffffff81ab3f70-ffffffff81ab3f9d: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b06c50)
Location: drivers/tty/vt/vt.c:1309
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
```
**Symbols:**

```
ffffffff81b06c50-ffffffff81b06c7d: vc_resize (STB_GLOBAL)
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
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010874c50)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffff800010874c50-ffff800010874c98: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0977a90)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
c0977a90-c0977abc: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000916160)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
c000000000916160-c000000000916188: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000546538)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffe000546538-ffffffe000546574: vc_resize (STB_GLOBAL)
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
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81662f20)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81662f20-ffffffff81662f41: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816432a0)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff816432a0-ffffffff816432c1: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81691300)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff81691300-ffffffff81691321: vc_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vc_resize(struct vc_data *vc, unsigned int cols, unsigned int rows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816ab8f0)
Location: drivers/tty/vt/vt.c:1337
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
**Symbols:**

```
ffffffff816ab8f0-ffffffff816ab911: vc_resize (STB_GLOBAL)
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
