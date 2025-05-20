# Function: <code>resource_overlaps</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8148562a)
Location: include/linux/ioport.h:246
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814d424a)
Location: include/linux/ioport.h:278
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814f6899)
Location: include/linux/ioport.h:278
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
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
In drivers/acpi/pci_root.c (ffffffff81504f71)
Location: include/linux/ioport.h:278
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff820ed90a)
Location: include/linux/ioport.h:278
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In drivers/acpi/pci_root.c (ffffffff81547291)
Location: include/linux/ioport.h:284
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff826f686d)
Location: include/linux/ioport.h:284
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In drivers/acpi/pci_root.c (ffffffff8157d277)
Location: include/linux/ioport.h:284
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82720886)
Location: include/linux/ioport.h:284
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In drivers/acpi/pci_root.c (ffffffff815950f7)
Location: include/linux/ioport.h:284
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828d881c)
Location: include/linux/ioport.h:284
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810a1f8c)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff815c6148)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828f26de)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810a854c)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff815e7378)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828fb8e5)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810b084c)
Location: include/linux/ioport.h:295
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff81692a0e)
Location: include/linux/ioport.h:295
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82d12123)
Location: include/linux/ioport.h:295
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810abf6d)
Location: include/linux/ioport.h:234
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff816b044c)
Location: include/linux/ioport.h:234
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82fffc02)
Location: include/linux/ioport.h:234
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810ac6b5)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - kernel/resource.c:__region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff81692a3b)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8320acf0)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810be235)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - kernel/resource.c:__region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff8170858b)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff832f3235)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810d52b9)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - kernel/resource.c:__region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff818368be)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff834ab349)
Location: include/linux/ioport.h:235
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810f4af5)
Location: include/linux/ioport.h:242
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff8196a99c)
Location: include/linux/ioport.h:242
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff83ee375a)
Location: include/linux/ioport.h:242
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff81100f25)
Location: include/linux/ioport.h:242
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff819b0f5c)
Location: include/linux/ioport.h:242
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8370915a)
Location: include/linux/ioport.h:242
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/pnp/quirks.c (ffffffff81a39627)
Location: include/linux/ioport.h:242
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_system_pci_resources
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
In kernel/resource.c (ffffffff8110a735)
Location: include/linux/ioport.h:242
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff819fb43c)
Location: include/linux/ioport.h:242
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8393c5ba)
Location: include/linux/ioport.h:242
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/pnp/quirks.c (ffffffff81a84e54)
Location: include/linux/ioport.h:242
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_system_pci_resources
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
In kernel/resource.c (ffff800010100364)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffff8000107745b8)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffff80001147eab8)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (c035d3c0)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
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
In kernel/resource.c (c000000000146f20)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
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
In kernel/resource.c (ffffffe0000c7690)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
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
In kernel/resource.c (ffffffff810a1e6c)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff815d8658)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828e4579)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff8109084c)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff815c2248)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828dc620)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810a1e1c)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff815db658)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828f74e1)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff810a9e47)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - kernel/resource.c:region_intersects
```
```
In drivers/acpi/pci_root.c (ffffffff815f5518)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828fc939)
Location: include/linux/ioport.h:293
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
</details>
</li>
</ul>

## Differences
