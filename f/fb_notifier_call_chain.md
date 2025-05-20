# Function: <code>fb_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff8146bcc0)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff8146bcc0-ffffffff8146bcdd: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff814ba180)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff814ba180-ffffffff814ba19d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff814dc180)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff814dc180-ffffffff814dc19d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff814e7d90)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff814e7d90-ffffffff814e7dad: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff8151c890)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff8151c890-ffffffff8151c8ad: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff81552550)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81552550-ffffffff8155256d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff81569dd0)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81569dd0-ffffffff81569ded: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff8159a680)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff8159a680-ffffffff8159a69d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff815bba80)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815bba80-ffffffff815bba9d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff816659a0)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff816659a0-ffffffff816659bd: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff81686620)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81686620-ffffffff8168663d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff81669420)
Location: drivers/video/fbdev/core/fb_notify.c:50
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81669420-ffffffff8166943d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff816dc860)
Location: drivers/video/fbdev/core/fb_notify.c:50
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff816dc860-ffffffff816dc87d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff81806630)
Location: drivers/video/fbdev/core/fb_notify.c:50
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81806630-ffffffff81806657: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff819350e0)
Location: drivers/video/fbdev/core/fb_notify.c:50
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff819350e0-ffffffff81935107: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff819793d0)
Location: drivers/video/fbdev/core/fb_notify.c:50
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff819793d0-ffffffff819793f7: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff819c34f0)
Location: drivers/video/fbdev/core/fb_notify.c:50
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff819c34f0-ffffffff819c3517: fb_notifier_call_chain (STB_GLOBAL)
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
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffff8000107427d8)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffff8000107427d8-ffff800010742814: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (c08c7100)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
c08c7100-c08c712c: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (c0000000008a32e0)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
c0000000008a32e0-c0000000008a3328: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffe0004f35d8)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffe0004f35d8-ffffffe0004f3612: fb_notifier_call_chain (STB_GLOBAL)
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
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff815afbd0)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815afbd0-ffffffff815afbed: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff8159ed60)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff8159ed60-ffffffff8159ed7d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff815b0160)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815b0160-ffffffff815b017d: fb_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fb_notifier_call_chain(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_notify.c (ffffffff815c9bd0)
Location: drivers/video/fbdev/core/fb_notify.c:43
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_blank
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815c9bd0-ffffffff815c9bed: fb_notifier_call_chain (STB_GLOBAL)
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
