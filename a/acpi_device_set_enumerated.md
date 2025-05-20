# Function: <code>acpi_device_set_enumerated</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ce59e)
Location: include/linux/acpi.h:552
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81647920)
Location: include/linux/acpi.h:552
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff816dd583)
Location: include/linux/acpi.h:552
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
In drivers/acpi/scan.c (ffffffff814f0452)
Location: include/linux/acpi.h:582
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81678a10)
Location: include/linux/acpi.h:582
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff8170d903)
Location: include/linux/acpi.h:582
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
In drivers/acpi/scan.c (ffffffff814fd78c)
Location: include/linux/acpi.h:580
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/spi/spi.c (ffffffff8168d2ee)
Location: include/linux/acpi.h:580
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724413)
Location: include/linux/acpi.h:580
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
In drivers/acpi/scan.c (ffffffff8153f7f2)
Location: include/linux/acpi.h:597
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffffffff81609d53)
Location: include/linux/acpi.h:597
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff816f6d10)
Location: include/linux/acpi.h:597
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795773)
Location: include/linux/acpi.h:597
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
In drivers/acpi/scan.c (ffffffff81575701)
Location: include/linux/acpi.h:606
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffffffff81643543)
Location: include/linux/acpi.h:606
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff8173225e)
Location: include/linux/acpi.h:606
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8239)
Location: include/linux/acpi.h:606
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
In drivers/acpi/scan.c (ffffffff8158d501)
Location: include/linux/acpi.h:613
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffffffff81661883)
Location: include/linux/acpi.h:613
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81754c4e)
Location: include/linux/acpi.h:613
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff4f9)
Location: include/linux/acpi.h:613
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
In drivers/acpi/scan.c (ffffffff815be2da)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffffffff816973af)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff817903a2)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81840903)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff815df59a)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffffffff816b9f77)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff817b3f8b)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81872263)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff8168a49f)
Location: include/linux/acpi.h:664
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
```
```
In drivers/tty/serdev/core.c (ffffffff8176e381)
Location: include/linux/acpi.h:664
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff8187b66b)
Location: include/linux/acpi.h:664
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819464e1)
Location: include/linux/acpi.h:664
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff816a815e)
Location: include/linux/acpi.h:668
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
```
```
In drivers/tty/serdev/core.c (ffffffff81788d54)
Location: include/linux/acpi.h:668
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff8188a321)
Location: include/linux/acpi.h:668
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194c434)
Location: include/linux/acpi.h:668
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff8168ab0e)
Location: include/linux/acpi.h:675
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
```
```
In drivers/tty/serdev/core.c (ffffffff8176c5f3)
Location: include/linux/acpi.h:675
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff8186ccfe)
Location: include/linux/acpi.h:675
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81930374)
Location: include/linux/acpi.h:675
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff817001ce)
Location: include/linux/acpi.h:679
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
```
```
In drivers/tty/serdev/core.c (ffffffff817f1d33)
Location: include/linux/acpi.h:679
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff818fcbae)
Location: include/linux/acpi.h:679
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d3646)
Location: include/linux/acpi.h:679
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff8182dd1d)
Location: include/linux/acpi.h:726
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
```
```
In drivers/tty/serdev/core.c (ffffffff8193247d)
Location: include/linux/acpi.h:726
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81a4e207)
Location: include/linux/acpi.h:726
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35da2)
Location: include/linux/acpi.h:726
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff81960a42)
Location: include/linux/acpi.h:733
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
```
```
In drivers/tty/serdev/core.c (ffffffff81a90f5b)
Location: include/linux/acpi.h:733
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81bd874d)
Location: include/linux/acpi.h:733
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccb01f)
Location: include/linux/acpi.h:733
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff819a6d51)
Location: include/linux/acpi.h:726
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
```
```
In drivers/tty/serdev/core.c (ffffffff81adc76a)
Location: include/linux/acpi.h:726
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81c2f13c)
Location: include/linux/acpi.h:726
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32d97)
Location: include/linux/acpi.h:726
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff819ef771)
Location: include/linux/acpi.h:727
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
```
```
In drivers/tty/serdev/core.c (ffffffff81b2fa6a)
Location: include/linux/acpi.h:727
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81ce1d84)
Location: include/linux/acpi.h:727
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8db7)
Location: include/linux/acpi.h:727
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/bus/hisi_lpc.c (ffff80001067f4e4)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
```
```
In drivers/acpi/scan.c (ffff80001076b99c)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffff8000108a9940)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffff8000109c32c0)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5bac)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/acpi/scan.c (ffffffff815d1741)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffffffff8167f9d7)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81778a6b)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
In drivers/acpi/scan.c (ffffffff815bb301)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/spi/spi.c (ffffffff8175881b)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
In drivers/acpi/scan.c (ffffffff815d387a)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffffffff816addb7)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff817a8e0b)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff818663f3)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
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
In drivers/acpi/scan.c (ffffffff815ed73a)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
```
```
In drivers/tty/serdev/core.c (ffffffff816c8217)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff817c2c9b)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff818816a3)
Location: include/linux/acpi.h:621
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
</ul>

## Differences
