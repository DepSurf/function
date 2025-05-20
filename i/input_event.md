# Function: <code>input_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81669fa0)
Location: drivers/input/input.c:429
Inline: True
Direct callers:
  - drivers/acpi/button.c:input_sync
  - drivers/acpi/button.c:acpi_lid_send_state
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81669fa0-ffffffff8166a017: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816ca260)
Location: drivers/input/input.c:428
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:input_sync
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff816ca260-ffffffff816ca2d3: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816f8240)
Location: drivers/input/input.c:428
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:input_sync
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff816f8240-ffffffff816f82b3: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8170dd50)
Location: drivers/input/input.c:428
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff8170dd50-ffffffff8170ddc4: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8177ef90)
Location: drivers/input/input.c:428
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff8177ef90-ffffffff8177f004: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817bff90)
Location: drivers/input/input.c:428
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff817bff90-ffffffff817c0001: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817e74a0)
Location: drivers/input/input.c:428
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff817e74a0-ffffffff817e7511: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81827f00)
Location: drivers/input/input.c:424
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81827f00-ffffffff81827f6b: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81859490)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81859490-ffffffff818594fb: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8192b8f0)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/misc/uinput.c:uinput_inject_events
```
**Symbols:**

```
ffffffff8192b8f0-ffffffff8192b958: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81933020)
Location: drivers/input/input.c:438
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/misc/uinput.c:uinput_inject_events
```
**Symbols:**

```
ffffffff81933020-ffffffff81933088: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81915550)
Location: drivers/input/input.c:438
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81915550-ffffffff819155b8: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819b7760)
Location: drivers/input/input.c:438
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff819b7760-ffffffff819b77c8: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81b17620)
Location: drivers/input/input.c:449
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81b17620-ffffffff81b17699: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81ca9850)
Location: drivers/input/input.c:424
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81ca9850-ffffffff81ca98c9: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81d10e20)
Location: drivers/input/input.c:427
Inline: True
Direct callers:
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81d10e20-ffffffff81d10e99: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81dc6a20)
Location: drivers/input/input.c:427
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/input-mt.c:input_mt_report_slot_state
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81dc6a20-ffffffff81dc6a99: input_event (STB_GLOBAL)
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
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffff800010a98f70)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffff800010a98f70-ffff800010a99060: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b7b27c)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
c0b7b27c-c0b7b2ec: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b79190)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
c000000000b79190-c000000000b7923c: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006aa0fe)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffe0006aa0fe-ffffffe0006aa178: input_event (STB_GLOBAL)
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
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8180e4a0)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff8180e4a0-ffffffff8180e50b: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817d5bf0)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff817d5bf0-ffffffff817d5c5b: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8184d620)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff8184d620-ffffffff8184d68b: input_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void input_event(struct input_dev *dev, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff818687f0)
Location: drivers/input/input.c:433
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:__input_mt_drop_unused
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_pointer_emulation
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/input-mt.c:input_mt_report_finger_count
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff818687f0-ffffffff8186885b: input_event (STB_GLOBAL)
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
