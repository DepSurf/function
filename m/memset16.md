# Function: <code>memset16</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8151a464)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815287e9)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff815f1ea4)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8155003d)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155ef4c)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8162ab0f)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815678e7)
Location: arch/x86/include/asm/string_64.h:37
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81575b9d)
Location: arch/x86/include/asm/string_64.h:37
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff816490ce)
Location: arch/x86/include/asm/string_64.h:37
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff81598220)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a5e8c)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8167db07)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815b95c0)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c6d5c)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff816a0304)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff81664a65)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8166fd82)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81752dfa)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_P
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff816856f5)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff816902a0)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8176e767)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_P
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff81667d97)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672fa8)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff817522cd)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff816daff7)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff816e8006)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff817d54db)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8180314a)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81812f0c)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff819134eb)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff819318ca)
Location: arch/x86/include/asm/string_64.h:37
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81941fdc)
Location: arch/x86/include/asm/string_64.h:37
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81a6e480)
Location: arch/x86/include/asm/string_64.h:37
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff81975d3a)
Location: arch/x86/include/asm/string_64.h:31
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819865bc)
Location: arch/x86/include/asm/string_64.h:31
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81ab88f0)
Location: arch/x86/include/asm/string_64.h:31
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff819bfdaa)
Location: arch/x86/include/asm/string_64.h:31
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d04dc)
Location: arch/x86/include/asm/string_64.h:31
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81b0b5d7)
Location: arch/x86/include/asm/string_64.h:31
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
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
void *memset16(uint16_t *s, uint16_t v, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92c60)
Location: lib/string.c:762
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffff800010d92c60-ffff800010d92c84: memset16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *memset16(uint16_t *s, uint16_t v, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f478)
Location: lib/string.c:762
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
c0e8f478-c0e8f4a8: memset16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (c00000000089bde8)
Location: arch/powerpc/include/asm/string.h:63
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (c0000000008b40b8)
Location: arch/powerpc/include/asm/string.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (c0000000009193a8)
Location: arch/powerpc/include/asm/string.h:63
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memset16(uint16_t *s, uint16_t v, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcd4e)
Location: lib/string.c:762
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffe0008bcd4e-ffffffe0008bcd70: memset16 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815ad710)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bae5c)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81665d64)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8159c8b0)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a9c3c)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff816460e4)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815adca0)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bb3ec)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81694144)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815c7750)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d4e9c)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff816ae724)
Location: arch/x86/include/asm/string_64.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
