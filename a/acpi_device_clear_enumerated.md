# Function: <code>acpi_device_clear_enumerated</code>

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
In drivers/acpi/scan.c (ffffffff814ce45e)
Location: include/linux/acpi.h:557
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81644825)
Location: include/linux/acpi.h:557
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_device
```
```
In drivers/i2c/i2c-core.c (ffffffff816da263)
Location: include/linux/acpi.h:557
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_unregister_device
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
In drivers/acpi/scan.c (ffffffff814f0332)
Location: include/linux/acpi.h:587
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff816758f5)
Location: include/linux/acpi.h:587
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_device
```
```
In drivers/i2c/i2c-core.c (ffffffff8170a833)
Location: include/linux/acpi.h:587
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_unregister_device
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
In drivers/acpi/scan.c (ffffffff814fd3c0)
Location: include/linux/acpi.h:585
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81689ff4)
Location: include/linux/acpi.h:585
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f053)
Location: include/linux/acpi.h:585
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
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
In drivers/acpi/scan.c (ffffffff8153f103)
Location: include/linux/acpi.h:602
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff816f44d6)
Location: include/linux/acpi.h:602
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81790e76)
Location: include/linux/acpi.h:602
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
In drivers/acpi/scan.c (ffffffff8157677e)
Location: include/linux/acpi.h:611
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81730f36)
Location: include/linux/acpi.h:611
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d38b6)
Location: include/linux/acpi.h:611
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
In drivers/acpi/scan.c (ffffffff8158e31a)
Location: include/linux/acpi.h:618
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81753926)
Location: include/linux/acpi.h:618
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fa9f6)
Location: include/linux/acpi.h:618
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
In drivers/acpi/scan.c (ffffffff815bef7a)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff8178f157)
Location: include/linux/acpi.h:626
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183b716)
Location: include/linux/acpi.h:626
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
In drivers/acpi/scan.c (ffffffff815e023a)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff817b2d17)
Location: include/linux/acpi.h:626
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186d0a6)
Location: include/linux/acpi.h:626
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
In drivers/acpi/scan.c (ffffffff8168bb1f)
Location: include/linux/acpi.h:669
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff818786d7)
Location: include/linux/acpi.h:669
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81940ab6)
Location: include/linux/acpi.h:669
Inline: True
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
In drivers/acpi/scan.c (ffffffff816a9954)
Location: include/linux/acpi.h:673
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81886f47)
Location: include/linux/acpi.h:673
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81946e86)
Location: include/linux/acpi.h:673
Inline: True
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
In drivers/acpi/scan.c (ffffffff8168c0df)
Location: include/linux/acpi.h:680
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81869777)
Location: include/linux/acpi.h:680
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192a786)
Location: include/linux/acpi.h:680
Inline: True
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
In drivers/acpi/scan.c (ffffffff8170189f)
Location: include/linux/acpi.h:684
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff818f9287)
Location: include/linux/acpi.h:684
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cd926)
Location: include/linux/acpi.h:684
Inline: True
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
In drivers/acpi/scan.c (ffffffff8182f53e)
Location: include/linux/acpi.h:731
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81a4a6b6)
Location: include/linux/acpi.h:731
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2eb04)
Location: include/linux/acpi.h:731
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
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
In drivers/acpi/scan.c (ffffffff819625ab)
Location: include/linux/acpi.h:738
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81bd1466)
Location: include/linux/acpi.h:738
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc27a4)
Location: include/linux/acpi.h:738
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
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
In drivers/acpi/scan.c (ffffffff819a89ab)
Location: include/linux/acpi.h:731
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81c290d6)
Location: include/linux/acpi.h:731
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2a1c4)
Location: include/linux/acpi.h:731
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
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
In drivers/acpi/scan.c (ffffffff819f13bb)
Location: include/linux/acpi.h:732
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff81cdbb16)
Location: include/linux/acpi.h:732
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de0084)
Location: include/linux/acpi.h:732
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
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
In drivers/bus/hisi_lpc.c (ffff80001067f0c0)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_remove
```
```
In drivers/acpi/scan.c (ffff80001076cb9c)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffff8000109c4064)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_device
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab02f0)
Location: include/linux/acpi.h:626
Inline: True
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
In drivers/acpi/scan.c (ffffffff815d2648)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff817777f7)
Location: include/linux/acpi.h:626
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
In drivers/acpi/scan.c (ffffffff815bc208)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff817575a7)
Location: include/linux/acpi.h:626
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
In drivers/acpi/scan.c (ffffffff815d451a)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff817a7b97)
Location: include/linux/acpi.h:626
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81861236)
Location: include/linux/acpi.h:626
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
In drivers/acpi/scan.c (ffffffff815ee3da)
Location: include/linux/acpi.h:626
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/spi/spi.c (ffffffff817c1a17)
Location: include/linux/acpi.h:626
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187c446)
Location: include/linux/acpi.h:626
Inline: True
```
</details>
</li>
</ul>

## Differences
