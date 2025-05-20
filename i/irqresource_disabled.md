# Function: <code>irqresource_disabled</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816aabdb)
Location: include/linux/ioport.h:330
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
```
```
In drivers/base/platform.c (ffffffff817d129e)
Location: include/linux/ioport.h:330
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
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
In drivers/acpi/resource.c (ffffffff8168d47e)
Location: include/linux/ioport.h:331
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
```
```
In drivers/base/platform.c (ffffffff817b4cc4)
Location: include/linux/ioport.h:331
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
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
In drivers/acpi/resource.c (ffffffff81702cae)
Location: include/linux/ioport.h:331
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
```
```
In drivers/base/platform.c (ffffffff8183e0a4)
Location: include/linux/ioport.h:331
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
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
In drivers/acpi/resource.c (ffffffff818308a6)
Location: include/linux/ioport.h:333
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
```
```
In drivers/base/platform.c (ffffffff81980e97)
Location: include/linux/ioport.h:333
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
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
In drivers/acpi/resource.c (ffffffff819645a6)
Location: include/linux/ioport.h:344
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
```
```
In drivers/base/platform.c (ffffffff81aeea37)
Location: include/linux/ioport.h:344
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
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
In drivers/acpi/resource.c (ffffffff819aaa90)
Location: include/linux/ioport.h:344
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
```
```
In drivers/base/platform.c (ffffffff81b3ce27)
Location: include/linux/ioport.h:344
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
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
In drivers/acpi/resource.c (ffffffff819f4d60)
Location: include/linux/ioport.h:347
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_resource_interrupt
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
```
```
In drivers/base/platform.c (ffffffff81b9495b)
Location: include/linux/ioport.h:347
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
