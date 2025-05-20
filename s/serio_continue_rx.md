# Function: <code>serio_continue_rx</code>

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
In drivers/input/serio/serio.c (ffffffff81663f47)
Location: include/linux/serio.h:147
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff8166616a)
Location: include/linux/serio.h:147
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81670f6f)
Location: include/linux/serio.h:147
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
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
In drivers/input/serio/serio.c (ffffffff816c4149)
Location: include/linux/serio.h:161
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff816c6704)
Location: include/linux/serio.h:161
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816d1411)
Location: include/linux/serio.h:161
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff816f2109)
Location: include/linux/serio.h:161
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff816f470b)
Location: include/linux/serio.h:161
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816ff2f1)
Location: include/linux/serio.h:161
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff817079f9)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff8170a2c0)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81714c71)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff81778bdc)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff8177b470)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81785e91)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff817b989f)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff817bc360)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c6f6c)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff817e0caf)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff817e37c0)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ee53c)
Location: include/linux/serio.h:162
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff8182158d)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff81824129)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182efd9)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff818529fd)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff81855610)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81860909)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff81924b2d)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff81927b30)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81933574)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff8192c8dd)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff8192f040)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193a7c4)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff8190fcbd)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff819123fe)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191e9d4)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
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
In drivers/input/serio/serio.c (ffffffff819b0bad)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff819b43c2)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819c1748)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
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
In drivers/input/serio/serio.c (ffffffff81b0e99d)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff81b1325e)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b214e8)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
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
In drivers/input/serio/serio.c (ffffffff81c9ec1d)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff81ca418e)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb3898)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
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
In drivers/input/serio/serio.c (ffffffff81d05f5d)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff81d0b863)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d1aee8)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
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
In drivers/input/serio/serio.c (ffffffff81dbbb5d)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff81dc14f3)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dd0c38)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
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
In drivers/input/serio/serio.c (ffff800010a92484)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffff800010a94438)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa2d58)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (c0b753c0)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_set_drv
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (c0b76f58)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (c0b82b5c)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (c000000000b6ee74)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (c000000000b7313c)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (c000000000b83e10)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffe0006a5240)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffe0006a64b8)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006b0982)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff81807add)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff8180a620)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81815919)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff817cf1ed)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff817d1db0)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dd039)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff81846b8d)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff818497a0)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81854a99)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
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
In drivers/input/serio/serio.c (ffffffff818612ad)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffff818646d0)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186e7c9)
Location: include/linux/serio.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
```
</details>
</li>
</ul>

## Differences
