# Function: <code>fb_mode_is_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff81472020)
Location: drivers/video/fbdev/core/modedb.c:954
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
```
**Symbols:**

```
ffffffff81472020-ffffffff8147206d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff814c1187)
Location: drivers/video/fbdev/core/modedb.c:954
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff814c04e0-ffffffff814c052d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff814e3177)
Location: drivers/video/fbdev/core/modedb.c:954
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff814e24d0-ffffffff814e251d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff814eef5a)
Location: drivers/video/fbdev/core/modedb.c:954
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff814ee200-ffffffff814ee24d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff81523ada)
Location: drivers/video/fbdev/core/modedb.c:954
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
```
**Symbols:**

```
ffffffff81522d80-ffffffff81522dcd: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8155982a)
Location: drivers/video/fbdev/core/modedb.c:973
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
```
**Symbols:**

```
ffffffff81558a10-ffffffff81558a5d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8157113a)
Location: drivers/video/fbdev/core/modedb.c:975
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
```
**Symbols:**

```
ffffffff815703a0-ffffffff815703ed: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815a1626)
Location: drivers/video/fbdev/core/modedb.c:978
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff815a0830-ffffffff815a087d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815c24a6)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff815c16b0-ffffffff815c16fd: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8166c83b)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff8166ba30-ffffffff8166ba7d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8168d18b)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff8168c380-ffffffff8168c3cd: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8166fe6b)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff8166f050-ffffffff8166f09d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff816e408b)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff816e3270-ffffffff816e32bd: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8180e68b)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_add_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff8180d790-ffffffff8180d7f5: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8193d2bb)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_add_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff8193c370-ffffffff8193c3d5: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8198129b)
Location: drivers/video/fbdev/core/modedb.c:930
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_add_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff81980350-ffffffff819803b5: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff819c660b)
Location: drivers/video/fbdev/core/modedb.c:930
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_add_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff819c5690-ffffffff819c56f5: fb_mode_is_equal (STB_GLOBAL)
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
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffff80001074b408)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffff80001074a660-ffff80001074a6f4: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (c08ccfc4)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
c08ccfc4-c08cd098: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (c0000000008ad044)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
c0000000008abd10-c0000000008abd9c: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffe0004f931a)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffe0004f8866-ffffffe0004f88d0: fb_mode_is_equal (STB_GLOBAL)
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
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815b65f6)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff815b5800-ffffffff815b584d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815a53d6)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff815a45e0-ffffffff815a462d: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815b6b86)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff815b5d90-ffffffff815b5ddd: fb_mode_is_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fb_mode_is_equal(const struct fb_videomode *mode1, const struct fb_videomode *mode2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815d05f6)
Location: drivers/video/fbdev/core/modedb.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_delete_videomode
  - drivers/video/fbdev/core/modedb.c:fb_match_mode
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_mode_deleted
```
**Symbols:**

```
ffffffff815cf800-ffffffff815cf84d: fb_mode_is_equal (STB_GLOBAL)
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
