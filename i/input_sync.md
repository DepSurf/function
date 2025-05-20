# Function: <code>input_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void input_sync(struct input_dev *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff814aaed6)
Location: include/linux/input.h:412
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_send_state
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81670684)
Location: include/linux/input.h:412
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff814aaed6-ffffffff814aaee7: input_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void input_sync(struct input_dev *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff814fa120)
Location: include/linux/input.h:412
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816d09b5)
Location: include/linux/input.h:412
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff814fa120-ffffffff814fa131: input_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void input_sync(struct input_dev *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8151cca3)
Location: include/linux/input.h:412
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816fe895)
Location: include/linux/input.h:412
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8170161e)
Location: include/linux/input.h:412
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff8151cca3-ffffffff8151ccb4: input_sync (STB_LOCAL)
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
In drivers/acpi/button.c (ffffffff8152da38)
Location: include/linux/input.h:417
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81713c30)
Location: include/linux/input.h:417
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81716e52)
Location: include/linux/input.h:417
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/acpi/button.c (ffffffff8158e948)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81784e73)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81788022)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/acpi/button.c (ffffffff815c5ceb)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c5f10)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c90b6)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/acpi/button.c (ffffffff815df2ab)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ed4e0)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f0756)
Location: include/linux/input.h:421
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/acpi/button.c (ffffffff81610e0e)
Location: include/linux/input.h:418
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182e01b)
Location: include/linux/input.h:418
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81830abc)
Location: include/linux/input.h:418
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/acpi/button.c (ffffffff816322be)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185f94b)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818623ec)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/acpi/button.c (ffffffff816df294)
Location: include/linux/input.h:440
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81933861)
Location: include/linux/input.h:440
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81934d95)
Location: include/linux/input.h:440
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
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
In drivers/acpi/button.c (ffffffff816fd2f4)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193aab1)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193be05)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
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
In drivers/acpi/button.c (ffffffff816df089)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191dbb0)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f389)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
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
In drivers/acpi/button.c (ffffffff81757252)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819c10d8)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2133)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
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
In drivers/acpi/button.c (ffffffff8188a3f5)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1fb93)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b224c9)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
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
In drivers/acpi/button.c (ffffffff819d0e63)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb1dc5)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb49e9)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
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
In drivers/acpi/button.c (ffffffff81a179e3)
Location: include/linux/input.h:448
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d1940b)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1c03a)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
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
In drivers/acpi/button.c (ffffffff81a639aa)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcf12b)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd1d8a)
Location: include/linux/input.h:448
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
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
In drivers/acpi/button.c (ffff8000107a0894)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa1c24)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In drivers/input/keyboard/atkbd.c (c0b81d14)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In sound/core/jack.c (c0c8b784)
Location: include/linux/input.h:439
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (c000000000b829a0)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffe0006afd4e)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In drivers/acpi/button.c (ffffffff81602739)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8181495b)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In drivers/acpi/button.c (ffffffff815edbe9)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dc08b)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In drivers/acpi/button.c (ffffffff8162659e)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81853adb)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8185657c)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/acpi/button.c (ffffffff8164044e)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186eeab)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818716ac)
Location: include/linux/input.h:439
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
</ul>
