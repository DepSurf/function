# Function: <code>input_get_drvdata</code>

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
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/input.h:348
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/input.h:348
Inline: True
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
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/input.h:348
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/input.h:348
Inline: True
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
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/input.h:348
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/input.h:348
Inline: True
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
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/input.h:353
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/input.h:353
Inline: True
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
In drivers/acpi/button.c (ffffffff8158e84d)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817847a5)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff8178962e)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff815c5bc3)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c5875)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff817ca6f4)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff815df183)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ece45)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff817f1db4)
Location: include/linux/input.h:357
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff81610cf3)
Location: include/linux/input.h:354
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182da05)
Location: include/linux/input.h:354
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81832065)
Location: include/linux/input.h:354
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff816321a3)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185f335)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff818639a5)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff816df3b3)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819326c5)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81937ab5)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff816fd3b3)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81939925)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff8193dea5)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff816df143)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191d045)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff819217d5)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff81757303)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bfa15)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff819c46a5)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff8188a4a3)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b20595)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81b24a15)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff819d0f23)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb28d5)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81cb7e45)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff81a18413)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d19ef5)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81d1f5c5)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff81a63683)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcfc15)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81dd52f5)
Location: include/linux/input.h:374
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffff8000107a0798)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa319c)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffff800010aa4b10)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/input/keyboard/atkbd.c (c0b814b0)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (c0b84080)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/input/keyboard/atkbd.c (c000000000b81eb8)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (c000000000b86d54)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/input/keyboard/atkbd.c (ffffffe0006af724)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffe0006b2782)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff81602663)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81814345)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81816655)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff815edb13)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dba75)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff817ddd55)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff81626483)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff818534c5)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81857b35)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
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
In drivers/acpi/button.c (ffffffff81640333)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186e715)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event
```
```
In drivers/input/misc/uinput.c (ffffffff81872c35)
Location: include/linux/input.h:366
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_dev_erase_effect
  - drivers/input/misc/uinput.c:uinput_dev_upload_effect
  - drivers/input/misc/uinput.c:uinput_dev_event
```
</details>
</li>
</ul>

## Differences
