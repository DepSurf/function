# Function: <code>scr_memcpyw</code>

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
In drivers/video/console/vgacon.c (ffffffff8145dc9a)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/console/fbcon.c (ffffffff81461102)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scroll
```
```
In drivers/tty/vt/vt.c (ffffffff814f76a1)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:scrup
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff814abedb)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/console/fbcon.c (ffffffff814b022e)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8154ccd9)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/video/console/vgacon.c (ffffffff814cdfda)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/console/fbcon.c (ffffffff814d233e)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8157953d)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
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
In drivers/video/console/vgacon.c (ffffffff814d9ec9)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/console/fbcon.c (ffffffff814dfa30)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8158d3b6)
Location: include/linux/vt_buffer.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
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
In drivers/video/console/vgacon.c (ffffffff8151a6aa)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81527d9e)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff815f1e8d)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff8154fe64)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155e749)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8162aae9)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff81567bb4)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8157521f)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff816490b1)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff81598434)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a56b1)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8167df31)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff815b97d4)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c6581)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff816a072e)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff81663743)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81671138)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8174e275)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_P
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff816843d3)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81691582)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81769845)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_P
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff81666ba3)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff816741fc)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8174e9ee)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff816d9cc5)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff816e82ec)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff817d082d)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff818032b2)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff818115c1)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8190e711)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff81931a32)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819404db)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81a6960d)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff81975ea2)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819849d4)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81ab3cea)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff819bff12)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819ce8f7)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff81b069ca)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/fbdev/core/fbcon.c (ffff80001074fc78)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffff800010877960)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/fbdev/core/fbcon.c (c08d22d4)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (c097a2f0)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffe0004f0e1c)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fc170)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffe000548442)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff815ad924)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ba681)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8166618e)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff8159cac4)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a9461)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8164650e)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff815adeb4)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bac11)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff8169456e)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/video/console/vgacon.c (ffffffff815c7bd4)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_switch
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d46c1)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
```
In drivers/tty/vt/vt.c (ffffffff816aeb4e)
Location: include/linux/vt_buffer.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
```
</details>
</li>
</ul>

## Differences
