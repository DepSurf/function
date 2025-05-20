# Function: <code>device_supports_offline</code>

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
In drivers/acpi/scan.c (ffffffff8147ff3a)
Location: include/linux/device.h:1005
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff81547146)
Location: include/linux/device.h:1005
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_online
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
In drivers/acpi/scan.c (ffffffff814ce8b2)
Location: include/linux/device.h:1021
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff8159ae04)
Location: include/linux/device.h:1021
Inline: True
Inline callers:
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff814f081c)
Location: include/linux/device.h:1130
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff815c9364)
Location: include/linux/device.h:1130
Inline: True
Inline callers:
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff814fdde6)
Location: include/linux/device.h:1134
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff815de087)
Location: include/linux/device.h:1134
Inline: True
Inline callers:
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff8153fc06)
Location: include/linux/device.h:1142
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff81645087)
Location: include/linux/device.h:1142
Inline: True
Inline callers:
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff81575b79)
Location: include/linux/device.h:1187
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff816804c7)
Location: include/linux/device.h:1187
Inline: True
Inline callers:
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff8158d798)
Location: include/linux/device.h:1240
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff8169ff57)
Location: include/linux/device.h:1240
Inline: True
Inline callers:
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff815be586)
Location: include/linux/device.h:1275
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff816d86c7)
Location: include/linux/device.h:1275
Inline: True
Inline callers:
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff815df846)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff816f9cc1)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff8168acc2)
Location: include/linux/device.h:834
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff817b2c9d)
Location: include/linux/device.h:834
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff816a8a02)
Location: include/linux/device.h:802
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff817c772d)
Location: include/linux/device.h:802
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add_attrs
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
In drivers/acpi/scan.c (ffffffff8168b182)
Location: include/linux/device.h:808
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff817aab9d)
Location: include/linux/device.h:808
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add_attrs
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
In drivers/acpi/scan.c (ffffffff81700c32)
Location: include/linux/device.h:841
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff81833d5d)
Location: include/linux/device.h:841
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add_attrs
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
In drivers/acpi/scan.c (ffffffff8182e8c2)
Location: include/linux/device.h:916
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff81975570)
Location: include/linux/device.h:916
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add_attrs
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
In drivers/acpi/scan.c (ffffffff819613b2)
Location: include/linux/device.h:915
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff81ae0da0)
Location: include/linux/device.h:915
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add_attrs
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
In drivers/acpi/scan.c (ffffffff819a77c2)
Location: include/linux/device.h:1042
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff81b2efd3)
Location: include/linux/device.h:1042
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add_attrs
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
In drivers/acpi/scan.c (ffffffff819f01b2)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff81b867d3)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add_attrs
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
In drivers/acpi/scan.c (ffff80001076bf78)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffff8000108e4170)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (c09d2c8c)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (c0000000009795cc)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/base/core.c (ffffffe00057919a)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff815d1c46)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff816bf4b1)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff815bb806)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff8169a761)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff815d3b26)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff816ed981)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
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
In drivers/acpi/scan.c (ffffffff815ed9e6)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_is_offline
```
```
In drivers/base/core.c (ffffffff817081c1)
Location: include/linux/device.h:1518
Inline: True
Inline callers:
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_add
```
</details>
</li>
</ul>

## Differences
