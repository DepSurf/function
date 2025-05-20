# Function: <code>pnp_resource_valid</code>

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
In drivers/pnp/support.c (ffffffff814b9eb9)
Location: include/linux/pnp.h:36
Inline: True
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8150577c)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81529c2f)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff81665b0e)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81677008)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff81509929)
Location: include/linux/pnp.h:36
Inline: True
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81556ec1)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8157d067)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff816c5dae)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff816d7bc8)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff8152db49)
Location: include/linux/pnp.h:36
Inline: True
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff815836c1)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815a9527)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff816f3dce)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81707b08)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff81540be9)
Location: include/linux/pnp.h:36
Inline: True
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81597adf)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815bf067)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff817097ae)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171d728)
Location: include/linux/pnp.h:36
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff815a3d09)
Location: include/linux/pnp.h:37
Inline: True
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff815fc70f)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81625667)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff8177a95e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178e9a8)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff815db939)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81635a89)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8165f977)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff817bb2de)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d100d)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff815f50e9)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81653d39)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8167de47)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff817e274e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f833d)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff8162700a)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff816887d1)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816b4b98)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff81822fee)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81838f6e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff81648afa)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff816aae61)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816d7878)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff818544ae)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186a8de)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff816f7b2a)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8175dac4)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8178bd48)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff8192673e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193e55e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff8171487a)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81778944)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff817a22c8)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff8192e300)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8194537e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff816f5bca)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8175c374)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81784fce)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff819116f0)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81928b7e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff8177021a)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff817dffc8)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8180bafe)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff819b2e70)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cb53e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff818a56a9)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8191ec96)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8194c06f)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff81b11380)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2d1dd)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff819ef529)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81a7b066)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81ab013f)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff81ca1e1e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc153b)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff81a37d09)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81ac68d6)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81afbf8f)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff81d09390)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d28f0b)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff81a834c9)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81b19906)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81b4f61f)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff81dbf020)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81dded8b)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffff8000107b5d30)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffff800010885728)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c2b78)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/pnp.h:37
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
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/pnp.h:37
Inline: True
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
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/pnp.h:37
Inline: True
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
In drivers/pnp/support.c (ffffffff8160eb5a)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff816708d1)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8169d2c8)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff818094be)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181d58e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff816030aa)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8164f9d1)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8167acb8)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff817d0c5e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e4c6e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff8163c93a)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8169eca1)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816cb538)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff8184863e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185ea6e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
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
In drivers/pnp/support.c (ffffffff81656c8a)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff816b9161)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816e5a08)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/input/serio/i8042.c (ffffffff8186385e)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8187a8ae)
Location: include/linux/pnp.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
</details>
</li>
</ul>

## Differences
