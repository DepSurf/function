# Function: <code>register_sys_off_handler</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sys_off_handler *register_sys_off_handler(enum sys_off_mode mode, int priority, int (*callback)(struct sys_off_data *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:377
Inline: False
Direct callers:
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:register_platform_power_off
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
```
**Symbols:**

```
ffffffff81e55053-ffffffff81e5506e: register_sys_off_handler.cold (STB_LOCAL)
ffffffff81102880-ffffffff81102a57: register_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sys_off_handler *register_sys_off_handler(enum sys_off_mode mode, int priority, int (*callback)(struct sys_off_data *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:389
Inline: False
Direct callers:
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:register_platform_power_off
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
```
**Symbols:**

```
ffffffff82056868-ffffffff82056883: register_sys_off_handler.cold (STB_LOCAL)
ffffffff81127cc0-ffffffff81127ea9: register_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sys_off_handler *register_sys_off_handler(enum sys_off_mode mode, int priority, int (*callback)(struct sys_off_data *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:389
Inline: False
Direct callers:
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:register_platform_power_off
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
```
**Symbols:**

```
ffffffff820d4ed7-ffffffff820d4ef2: register_sys_off_handler.cold (STB_LOCAL)
ffffffff81135160-ffffffff81135349: register_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sys_off_handler *register_sys_off_handler(enum sys_off_mode mode, int priority, int (*callback)(struct sys_off_data *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:403
Inline: False
Direct callers:
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:register_platform_power_off
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
```
**Symbols:**

```
ffffffff821afdbe-ffffffff821afdd9: register_sys_off_handler.cold (STB_LOCAL)
ffffffff811400a0-ffffffff811402b8: register_sys_off_handler (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
