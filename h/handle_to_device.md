# Function: <code>handle_to_device</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *handle_to_device(acpi_handle handle, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168b413)
Location: drivers/acpi/scan.c:577
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff8168a4f0-ffffffff8168a576: handle_to_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *handle_to_device(acpi_handle handle, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816ff9f0)
Location: drivers/acpi/scan.c:574
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_dev_get_first_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff816ff9f0-ffffffff816ffa73: handle_to_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *handle_to_device(acpi_handle handle, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182d4d0)
Location: drivers/acpi/scan.c:576
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_dev_get_first_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff8182d4d0-ffffffff8182d55e: handle_to_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *handle_to_device(acpi_handle handle, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81960250)
Location: drivers/acpi/scan.c:568
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff81960250-ffffffff819602de: handle_to_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *handle_to_device(acpi_handle handle, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a6640)
Location: drivers/acpi/scan.c:567
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff819a6640-ffffffff819a66ce: handle_to_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *handle_to_device(acpi_handle handle, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819ef020)
Location: drivers/acpi/scan.c:567
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff819ef020-ffffffff819ef0ae: handle_to_device (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
