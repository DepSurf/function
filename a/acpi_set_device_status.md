# Function: <code>acpi_set_device_status</code>

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
In drivers/acpi/bus.c (ffffffff8147eab5)
Location: include/acpi/acpi_bus.h:434
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
```
In drivers/acpi/scan.c (ffffffff814805a9)
Location: include/acpi/acpi_bus.h:434
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (0)
Location: include/acpi/acpi_bus.h:443
Inline: True
```
```
In drivers/acpi/scan.c (0)
Location: include/acpi/acpi_bus.h:443
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
In drivers/acpi/bus.c (0)
Location: include/acpi/acpi_bus.h:443
Inline: True
```
```
In drivers/acpi/scan.c (0)
Location: include/acpi/acpi_bus.h:443
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
In drivers/acpi/bus.c (ffffffff814fc169)
Location: include/acpi/acpi_bus.h:446
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff814fe562)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff8153ded9)
Location: include/acpi/acpi_bus.h:457
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8154055e)
Location: include/acpi/acpi_bus.h:457
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff81573859)
Location: include/acpi/acpi_bus.h:460
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff81576fb6)
Location: include/acpi/acpi_bus.h:460
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff8158b479)
Location: include/acpi/acpi_bus.h:466
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8158eb98)
Location: include/acpi/acpi_bus.h:466
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff815bc2d9)
Location: include/acpi/acpi_bus.h:453
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815bf908)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff815dd599)
Location: include/acpi/acpi_bus.h:450
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815e0bc8)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff816880c9)
Location: include/acpi/acpi_bus.h:451
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8168bdba)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff816a5e39)
Location: include/acpi/acpi_bus.h:452
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff816a9c7b)
Location: include/acpi/acpi_bus.h:452
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff81688b39)
Location: include/acpi/acpi_bus.h:453
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8168c319)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff816fdf7d)
Location: include/acpi/acpi_bus.h:459
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
```
```
In drivers/acpi/scan.c (ffffffff81701c2e)
Location: include/acpi/acpi_bus.h:459
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff8182b905)
Location: include/acpi/acpi_bus.h:463
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
```
```
In drivers/acpi/scan.c (ffffffff8182f8a5)
Location: include/acpi/acpi_bus.h:463
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff8195e2a5)
Location: include/acpi/acpi_bus.h:469
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
```
```
In drivers/acpi/scan.c (ffffffff8196294b)
Location: include/acpi/acpi_bus.h:469
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff819a4695)
Location: include/acpi/acpi_bus.h:472
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
```
```
In drivers/acpi/scan.c (ffffffff819a8d60)
Location: include/acpi/acpi_bus.h:472
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff819ecfe5)
Location: include/acpi/acpi_bus.h:567
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
```
```
In drivers/acpi/scan.c (ffffffff819f179f)
Location: include/acpi/acpi_bus.h:567
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffff800010768eec)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/bus.c:acpi_bus_get_status
```
```
In drivers/acpi/scan.c (ffff80001076d4b0)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff815cfb29)
Location: include/acpi/acpi_bus.h:450
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815d2f46)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff815b96e9)
Location: include/acpi/acpi_bus.h:450
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815bcb06)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff815d1879)
Location: include/acpi/acpi_bus.h:450
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815d4ea8)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/bus.c (ffffffff815eb739)
Location: include/acpi/acpi_bus.h:450
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815eed68)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
</details>
</li>
</ul>

## Differences
