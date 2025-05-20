# Function: <code>scr_memsetw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8145e54b)
Location: include/linux/vt_buffer.h:27
Inline: True
```
```
In drivers/video/console/fbcon.c (ffffffff8146117f)
Location: include/linux/vt_buffer.h:27
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
```
```
In drivers/tty/vt/vt.c (ffffffff816f4751)
Location: include/linux/vt_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:scrdown
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:scrup
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff814ac78c)
Location: include/linux/vt_buffer.h:27
Inline: True
```
```
In drivers/video/console/fbcon.c (ffffffff814b234b)
Location: include/linux/vt_buffer.h:27
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8154c231)
Location: include/linux/vt_buffer.h:27
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
  - drivers/tty/vt/vt.c:scrdown
  - drivers/tty/vt/vt.c:scrup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff814ce35e)
Location: include/linux/vt_buffer.h:27
Inline: True
```
```
In drivers/video/console/fbcon.c (ffffffff814d4347)
Location: include/linux/vt_buffer.h:27
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81578a63)
Location: include/linux/vt_buffer.h:27
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff814da277)
Location: include/linux/vt_buffer.h:27
Inline: True
```
```
In drivers/video/console/fbcon.c (ffffffff814e01eb)
Location: include/linux/vt_buffer.h:27
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8158c89d)
Location: include/linux/vt_buffer.h:27
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8151a45e)
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815287e9)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155ef4c)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81575b9d)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a5e8c)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c6d5c)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8166fd82)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff816902a0)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672fa8)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff816e8006)
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff817d54db)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81812f0c)
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff819134eb)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81941fdc)
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81a6e480)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819865bc)
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81ab88f0)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_blank
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d04dc)
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81b0b5d7)
Location: include/linux/vt_buffer.h:29
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010750384)
Location: include/linux/vt_buffer.h:29
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
In drivers/tty/vt/vt.c (ffff800010877898)
Location: include/linux/vt_buffer.h:29
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d298c)
Location: include/linux/vt_buffer.h:29
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (c0979534)
Location: include/linux/vt_buffer.h:29
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (c00000000089bde8)
Location: arch/powerpc/include/asm/vga.h:38
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (c0000000008b40b8)
Location: arch/powerpc/include/asm/vga.h:38
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
Location: arch/powerpc/include/asm/vga.h:38
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffe0004f1934)
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fe174)
Location: include/linux/vt_buffer.h:29
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
In drivers/tty/vt/vt.c (ffffffe000547bba)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bae5c)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a9c3c)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bb3ec)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d4e9c)
Location: include/linux/vt_buffer.h:29
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
Location: include/linux/vt_buffer.h:29
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
