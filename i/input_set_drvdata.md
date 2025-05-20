# Function: <code>input_set_drvdata</code>

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
In drivers/input/keyboard/atkbd.c (ffffffff8166f625)
Location: include/linux/input.h:353
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81672296)
Location: include/linux/input.h:353
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/keyboard/atkbd.c (ffffffff816cf985)
Location: include/linux/input.h:353
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff816d32bf)
Location: include/linux/input.h:353
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/keyboard/atkbd.c (ffffffff816fd865)
Location: include/linux/input.h:353
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81701220)
Location: include/linux/input.h:353
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81703009)
Location: include/linux/input.h:353
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
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
In drivers/input/keyboard/atkbd.c (ffffffff81713158)
Location: include/linux/input.h:358
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff817173bf)
Location: include/linux/input.h:358
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_allocate_device
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
In drivers/acpi/button.c (ffffffff8158ee4a)
Location: include/linux/input.h:362
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81784398)
Location: include/linux/input.h:362
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff817890c4)
Location: include/linux/input.h:362
Inline: True
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
In drivers/acpi/button.c (ffffffff815c6216)
Location: include/linux/input.h:362
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c54a7)
Location: include/linux/input.h:362
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff817c9d1d)
Location: include/linux/input.h:362
Inline: True
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
In drivers/acpi/button.c (ffffffff815df7d6)
Location: include/linux/input.h:362
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817eca77)
Location: include/linux/input.h:362
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff817f13dd)
Location: include/linux/input.h:362
Inline: True
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
In drivers/acpi/button.c (ffffffff81611351)
Location: include/linux/input.h:359
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182d617)
Location: include/linux/input.h:359
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81832c7e)
Location: include/linux/input.h:359
Inline: True
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
In drivers/acpi/button.c (ffffffff81632801)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185ef47)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff818645b8)
Location: include/linux/input.h:371
Inline: True
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
In drivers/acpi/button.c (ffffffff816dedb5)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819319f7)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81936961)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
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
In drivers/acpi/button.c (ffffffff816fcde5)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81938c77)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff8193cd51)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
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
In drivers/acpi/button.c (ffffffff816dea51)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191c4e7)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81920971)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
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
In drivers/acpi/button.c (ffffffff81756bf1)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bed81)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff819c36d1)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
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
In drivers/acpi/button.c (ffffffff81889d34)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1efe1)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81b2415d)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
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
In drivers/acpi/button.c (ffffffff819d0730)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb0e91)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81cb75ad)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
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
In drivers/acpi/button.c (ffffffff81a17d28)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d184ec)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81d1eb8d)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
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
In drivers/acpi/button.c (ffffffff81a62f89)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dce19c)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81dd488d)
Location: include/linux/input.h:379
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
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
In drivers/acpi/button.c (ffff8000107a0e40)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa12ec)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffff800010aa5c28)
Location: include/linux/input.h:371
Inline: True
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
In drivers/input/keyboard/atkbd.c (c0b810cc)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (c0b84980)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
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
In drivers/input/keyboard/atkbd.c (c000000000b818b4)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (c000000000b86150)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
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
In drivers/input/keyboard/atkbd.c (ffffffe0006af3cc)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffe0006b1bf6)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
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
In drivers/acpi/button.c (ffffffff81602c71)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81813f57)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81817268)
Location: include/linux/input.h:371
Inline: True
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
In drivers/acpi/button.c (ffffffff815ee121)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817db687)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff817de958)
Location: include/linux/input.h:371
Inline: True
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
In drivers/acpi/button.c (ffffffff81626ae1)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff818530d7)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81858748)
Location: include/linux/input.h:371
Inline: True
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
In drivers/acpi/button.c (ffffffff81640991)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186e327)
Location: include/linux/input.h:371
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
```
```
In drivers/input/misc/uinput.c (ffffffff81873828)
Location: include/linux/input.h:371
Inline: True
```
</details>
</li>
</ul>

## Differences
