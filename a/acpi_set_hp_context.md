# Function: <code>acpi_set_hp_context</code>

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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452885)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/scan.c (ffffffff8147fe71)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fcac)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff814ce7e4)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c182c)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff814f074e)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cbe38)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff814fce37)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150c40f)
Location: include/acpi/acpi_bus.h:462
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff8153eb77)
Location: include/acpi/acpi_bus.h:462
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81541228)
Location: include/acpi/acpi_bus.h:465
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff81574ab7)
Location: include/acpi/acpi_bus.h:465
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81558588)
Location: include/acpi/acpi_bus.h:471
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff8158c6d7)
Location: include/acpi/acpi_bus.h:471
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81588591)
Location: include/acpi/acpi_bus.h:458
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff815bd4b7)
Location: include/acpi/acpi_bus.h:458
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9f91)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff815de777)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81652ddf)
Location: include/acpi/acpi_bus.h:456
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff81689127)
Location: include/acpi/acpi_bus.h:456
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8167579f)
Location: include/acpi/acpi_bus.h:457
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff816a6cb7)
Location: include/acpi/acpi_bus.h:457
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81657ccb)
Location: include/acpi/acpi_bus.h:458
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff81689947)
Location: include/acpi/acpi_bus.h:458
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c9cf6)
Location: include/acpi/acpi_bus.h:464
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff816fee27)
Location: include/acpi/acpi_bus.h:464
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817effd7)
Location: include/acpi/acpi_bus.h:468
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff8182c7d7)
Location: include/acpi/acpi_bus.h:468
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81918187)
Location: include/acpi/acpi_bus.h:474
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff8195f457)
Location: include/acpi/acpi_bus.h:474
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b7ac)
Location: include/acpi/acpi_bus.h:477
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff819a5857)
Location: include/acpi/acpi_bus.h:477
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4dc7)
Location: include/acpi/acpi_bus.h:572
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff819ee1d7)
Location: include/acpi/acpi_bus.h:572
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010713314)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffff80001076abfc)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d761)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff815d0c57)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158c8f1)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff815ba817)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159dce1)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff815d2a57)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b8111)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/acpi/scan.c (ffffffff815ec917)
Location: include/acpi/acpi_bus.h:455
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_initialize_hp_context
```
</details>
</li>
</ul>

## Differences
