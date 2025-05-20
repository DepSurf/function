# Function: <code>con_is_bound</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f6e10)
Location: drivers/tty/vt/vt.c:3487
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_unregister_con_driver
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:set_con2fb_map
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_event_notify
```
**Symbols:**

```
ffffffff814f6e10-ffffffff814f6e3e: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81547be9)
Location: drivers/tty/vt/vt.c:3486
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_unregister_con_driver
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81547a40-ffffffff81547a72: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815744e9)
Location: drivers/tty/vt/vt.c:3485
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_unregister_con_driver
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81574240-ffffffff81574272: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815887fa)
Location: drivers/tty/vt/vt.c:3494
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff815881f0-ffffffff81588222: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ed4fa)
Location: drivers/tty/vt/vt.c:3499
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff815ecd20-ffffffff815ecd52: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816268d3)
Location: drivers/tty/vt/vt.c:3497
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81626120-ffffffff81626152: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81643f23)
Location: drivers/tty/vt/vt.c:3812
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81643610-ffffffff81643642: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3852
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8167f016-ffffffff8167f029: con_is_bound.cold (STB_LOCAL)
ffffffff81677d10-ffffffff81677d61: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169a4a0)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8169a4a0-ffffffff8169a4ef: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174cb30)
Location: drivers/tty/vt/vt.c:3893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_select_primary
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8174cb30-ffffffff8174cb89: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81768160)
Location: drivers/tty/vt/vt.c:3982
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_select_primary
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81768160-ffffffff817681b9: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174bd80)
Location: drivers/tty/vt/vt.c:3982
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8174bd80-ffffffff8174bdd9: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817cd8c0)
Location: drivers/tty/vt/vt.c:3987
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff817cd8c0-ffffffff817cd92a: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190b4e0)
Location: drivers/tty/vt/vt.c:3987
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8190b4e0-ffffffff8190b55a: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a65db0)
Location: drivers/tty/vt/vt.c:3986
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81a65db0-ffffffff81a65e2a: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab04a0)
Location: drivers/tty/vt/vt.c:3935
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81ab04a0-ffffffff81ab051a: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b03150)
Location: drivers/tty/vt/vt.c:3935
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81b03150-ffffffff81b031ca: con_is_bound (STB_GLOBAL)
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
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff8000108717d8)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffff8000108717d8-ffff800010871864: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0974758)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
c0974758-c09747e8: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000911a80)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
c000000000911a80-c000000000911b4c: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000543754)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffe000543754-ffffffe0005437c4: con_is_bound (STB_GLOBAL)
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
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8165ff00)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8165ff00-ffffffff8165ff4f: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81640280)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81640280-ffffffff816402cf: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168e2e0)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8168e2e0-ffffffff8168e32f: con_is_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int con_is_bound(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a88e0)
Location: drivers/tty/vt/vt.c:3883
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff816a88e0-ffffffff816a892f: con_is_bound (STB_GLOBAL)
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
