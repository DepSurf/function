# Function: <code>acpi_dev_name</code>

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
In drivers/spi/spi.c (ffffffff815e6cd0)
Location: include/linux/acpi.h:81
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core.c (ffffffff8167c777)
Location: include/linux/acpi.h:81
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_new_device
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
In drivers/spi/spi.c (ffffffff816452c8)
Location: include/linux/acpi.h:83
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core.c (ffffffff816dd454)
Location: include/linux/acpi.h:83
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_new_device
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
In drivers/spi/spi.c (ffffffff816763c8)
Location: include/linux/acpi.h:104
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core.c (ffffffff8170d7d4)
Location: include/linux/acpi.h:104
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_new_device
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
In drivers/spi/spi.c (ffffffff8168a9a5)
Location: include/linux/acpi.h:109
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81720c35)
Location: include/linux/acpi.h:109
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/spi/spi.c (ffffffff816f40ef)
Location: include/linux/acpi.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81791ef7)
Location: include/linux/acpi.h:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/acpi/utils.c (ffffffff8156e87f)
Location: include/linux/acpi.h:107
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81730b2f)
Location: include/linux/acpi.h:107
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d48f7)
Location: include/linux/acpi.h:107
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/acpi/utils.c (ffffffff8158643f)
Location: include/linux/acpi.h:107
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817536ff)
Location: include/linux/acpi.h:107
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fba57)
Location: include/linux/acpi.h:107
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/spi/spi.c (ffffffff8178eadf)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183caca)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff817b269f)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186e4ca)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff8187abef)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819422ba)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff818898df)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81948614)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff8186c1ee)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192bf84)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff818f8a98)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_dev_set_name
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cf144)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff81a49e38)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_dev_set_name
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30fb5)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff81bd0318)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_dev_set_name
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5936)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff81c27f98)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_dev_set_name
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d5c2)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff81cda5a8)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_dev_set_name
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de355a)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffff8000109c29ac)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab1b7c)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (0)
Location: include/linux/acpi.h:735
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/acpi.h:735
Inline: True
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
In drivers/spi/spi.c (0)
Location: include/linux/acpi.h:735
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/acpi.h:735
Inline: True
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
In drivers/spi/spi.c (0)
Location: include/linux/acpi.h:735
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/acpi.h:735
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8177717f)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81756f2f)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff817a751f)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186265a)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
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
In drivers/spi/spi.c (ffffffff817c139f)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187d8ba)
Location: include/linux/acpi.h:95
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
</details>
</li>
</ul>

## Differences
