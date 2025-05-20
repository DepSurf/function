# Function: <code>acpi_lock_hp_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8147fe1a)
Location: drivers/acpi/scan.c:73
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/acpi/scan.c:acpi_initialize_hp_context
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff8147fe1a-ffffffff8147fe31: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ce78d)
Location: drivers/acpi/scan.c:74
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
```
**Symbols:**

```
ffffffff814ce78d-ffffffff814ce7a4: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f06f7)
Location: drivers/acpi/scan.c:75
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
```
**Symbols:**

```
ffffffff814f06f7-ffffffff814f070e: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ff678)
Location: drivers/acpi/scan.c:69
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff814fdcd0-ffffffff814fdce7: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81541758)
Location: drivers/acpi/scan.c:70
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff8153faf0-ffffffff8153fb07: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81577628)
Location: drivers/acpi/scan.c:70
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff81575a40-ffffffff81575a57: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158f258)
Location: drivers/acpi/scan.c:70
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff8158d660-ffffffff8158d677: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bff88)
Location: drivers/acpi/scan.c:71
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff815be450-ffffffff815be467: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815e1248)
Location: drivers/acpi/scan.c:71
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff815df710-ffffffff815df727: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168c147)
Location: drivers/acpi/scan.c:70
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:hotplug_dock_devices
  - drivers/acpi/dock.c:hotplug_dock_devices
```
**Symbols:**

```
ffffffff8168ab90-ffffffff8168aba7: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816aa1bd)
Location: drivers/acpi/scan.c:70
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:hotplug_dock_devices
  - drivers/acpi/dock.c:hotplug_dock_devices
```
**Symbols:**

```
ffffffff816a88d0-ffffffff816a88e7: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168ca44)
Location: drivers/acpi/scan.c:68
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_event
```
**Symbols:**

```
ffffffff8168b050-ffffffff8168b067: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81702294)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_event
```
**Symbols:**

```
ffffffff81700b00-ffffffff81700b17: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182ff94)
Location: drivers/acpi/scan.c:66
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_event
```
**Symbols:**

```
ffffffff8182e770-ffffffff8182e78d: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819630dc)
Location: drivers/acpi/scan.c:65
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_event
```
**Symbols:**

```
ffffffff81961220-ffffffff8196123d: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a957c)
Location: drivers/acpi/scan.c:64
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_event
```
**Symbols:**

```
ffffffff819a7630-ffffffff819a764d: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f207c)
Location: drivers/acpi/scan.c:64
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_event
```
**Symbols:**

```
ffffffff819f0020-ffffffff819f003d: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076dad0)
Location: drivers/acpi/scan.c:71
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffff80001076be00-ffff80001076be28: acpi_lock_hp_context (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d35ba)
Location: drivers/acpi/scan.c:71
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff815d1b10-ffffffff815d1b27: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bd17a)
Location: drivers/acpi/scan.c:71
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff815bb6d0-ffffffff815bb6e7: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d5528)
Location: drivers/acpi/scan.c:71
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff815d39f0-ffffffff815d3a07: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_lock_hp_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ef3e8)
Location: drivers/acpi/scan.c:71
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_initialize_hp_context
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:cleanup_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
**Symbols:**

```
ffffffff815ed8b0-ffffffff815ed8c7: acpi_lock_hp_context (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
