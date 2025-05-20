# Function: <code>acpi_execute_simple_method</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147ab4c)
Location: drivers/acpi/utils.c:561
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/battery.c:acpi_battery_set_alarm
```
**Symbols:**

```
ffffffff8147ab4c-ffffffff8147abb2: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c90fd)
Location: drivers/acpi/utils.c:558
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:sleep_notify_reboot
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/battery.c:acpi_battery_set_alarm
```
**Symbols:**

```
ffffffff814c90fd-ffffffff814c9163: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eb041)
Location: drivers/acpi/utils.c:558
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/battery.c:acpi_battery_set_alarm
```
**Symbols:**

```
ffffffff814eb041-ffffffff814eb0a7: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f7050)
Location: drivers/acpi/utils.c:558
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/battery.c:acpi_battery_set_alarm
```
**Symbols:**

```
ffffffff814f7050-ffffffff814f70be: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81538070)
Location: drivers/acpi/utils.c:559
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81538070-ffffffff815380de: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156dcf0)
Location: drivers/acpi/utils.c:559
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff8156dcf0-ffffffff8156dd5e: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815858b0)
Location: drivers/acpi/utils.c:559
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff815858b0-ffffffff8158591e: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6520)
Location: drivers/acpi/utils.c:546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff815b6520-ffffffff815b6587: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d7750)
Location: drivers/acpi/utils.c:546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff815d7750-ffffffff815d77b7: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8168232a)
Location: drivers/acpi/utils.c:553
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81681470-ffffffff816814d7: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0cba)
Location: drivers/acpi/utils.c:549
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff8169fdc0-ffffffff8169fe27: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81683aaa)
Location: drivers/acpi/utils.c:543
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_get_info
```
**Symbols:**

```
ffffffff81682b80-ffffffff81682be7: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f8c3a)
Location: drivers/acpi/utils.c:557
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_get_info
```
**Symbols:**

```
ffffffff816f7cd0-ffffffff816f7d37: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825dfb)
Location: drivers/acpi/utils.c:557
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan_core.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_get_info
```
**Symbols:**

```
ffffffff81824c80-ffffffff81824cfb: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819574fb)
Location: drivers/acpi/utils.c:595
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan_core.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_get_info
```
**Symbols:**

```
ffffffff81955dd0-ffffffff81955e4b: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199d9cb)
Location: drivers/acpi/utils.c:595
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan_core.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_get_info
```
**Symbols:**

```
ffffffff8199c1d0-ffffffff8199c24b: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e5fdb)
Location: drivers/acpi/utils.c:667
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan_core.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff819e4720-ffffffff819e479b: acpi_execute_simple_method (STB_GLOBAL)
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
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010765b58)
Location: drivers/acpi/utils.c:546
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/battery.c:acpi_battery_set_alarm
```
**Symbols:**

```
ffff800010764e98-ffff800010764f20: acpi_execute_simple_method (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cad20)
Location: drivers/acpi/utils.c:546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
```
**Symbols:**

```
ffffffff815cad20-ffffffff815cad87: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b3d70)
Location: drivers/acpi/utils.c:546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
```
**Symbols:**

```
ffffffff815b3d70-ffffffff815b3dd7: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cba30)
Location: drivers/acpi/utils.c:546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff815cba30-ffffffff815cba97: acpi_execute_simple_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_execute_simple_method(acpi_handle handle, char *method, u64 arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e58d0)
Location: drivers/acpi/utils.c:546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler_evt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_sleep_tts_switch
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff815e58d0-ffffffff815e5937: acpi_execute_simple_method (STB_GLOBAL)
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
