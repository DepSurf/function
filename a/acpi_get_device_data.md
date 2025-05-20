# Function: <code>acpi_get_device_data</code>

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
In drivers/acpi/scan.c (ffffffff8147f4b9)
Location: drivers/acpi/scan.c:559
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_device
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
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
In drivers/acpi/scan.c (ffffffff814ce90d)
Location: drivers/acpi/scan.c:579
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_get_device
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
In drivers/acpi/scan.c (ffffffff814f0877)
Location: drivers/acpi/scan.c:580
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_get_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fde46)
Location: drivers/acpi/scan.c:578
Inline: True
Inline callers:
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
ffffffff814fd7a0-ffffffff814fd7e0: acpi_get_device_data.constprop.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8153f1a0)
Location: drivers/acpi/scan.c:579
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff8153f1a0-ffffffff8153f246: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815750f0)
Location: drivers/acpi/scan.c:580
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff815750f0-ffffffff81575188: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158cef0)
Location: drivers/acpi/scan.c:580
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff8158cef0-ffffffff8158cf88: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bdca0)
Location: drivers/acpi/scan.c:581
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff815bdca0-ffffffff815bdd38: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815def60)
Location: drivers/acpi/scan.c:581
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff815def60-ffffffff815deff8: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168af0a)
Location: drivers/acpi/scan.c:580
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
ffffffff81689ee0-ffffffff81689f78: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a8c4a)
Location: drivers/acpi/scan.c:580
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
ffffffff816a7a80-ffffffff816a7b1f: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076c034)
Location: drivers/acpi/scan.c:581
Inline: True
Inline callers:
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
ffff80001076ba08-ffff80001076ba70: acpi_get_device_data.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d1cf6)
Location: drivers/acpi/scan.c:581
Inline: True
Inline callers:
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
ffffffff815d17b0-ffffffff815d17f0: acpi_get_device_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bb8b6)
Location: drivers/acpi/scan.c:581
Inline: True
Inline callers:
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
ffffffff815bb370-ffffffff815bb3b0: acpi_get_device_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d3240)
Location: drivers/acpi/scan.c:581
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff815d3240-ffffffff815d32d8: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device **device, void (*callback)(void *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ed100)
Location: drivers/acpi/scan.c:581
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
```
**Symbols:**

```
ffffffff815ed100-ffffffff815ed198: acpi_get_device_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
