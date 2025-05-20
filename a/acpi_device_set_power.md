# Function: <code>acpi_device_set_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147cdc9)
Location: drivers/acpi/device_pm.c:149
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff8147cdc9-ffffffff8147cf99: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cb55c)
Location: drivers/acpi/device_pm.c:150
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff814cb55c-ffffffff814cb729: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814ed488)
Location: drivers/acpi/device_pm.c:150
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff814ed488-ffffffff814ed655: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814fa040)
Location: drivers/acpi/device_pm.c:151
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff814fa040-ffffffff814fa2ef: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153bd00)
Location: drivers/acpi/device_pm.c:151
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff8153bd00-ffffffff8153c076: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81571b00)
Location: drivers/acpi/device_pm.c:151
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff81571b00-ffffffff81571e7f: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815898d0)
Location: drivers/acpi/device_pm.c:152
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff815898d0-ffffffff81589c58: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff815bb3a2-ffffffff815bb476: acpi_device_set_power.cold (STB_LOCAL)
ffffffff815ba410-ffffffff815ba6c0: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff815dc672-ffffffff815dc73a: acpi_device_set_power.cold (STB_LOCAL)
ffffffff815db650-ffffffff815db953: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff81686d85-ffffffff81686e24: acpi_device_set_power.cold (STB_LOCAL)
ffffffff81685df0-ffffffff81686157: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff81c00e3a-ffffffff81c00ed9: acpi_device_set_power.cold (STB_LOCAL)
ffffffff816a3bb0-ffffffff816a3f20: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff81bf2863-ffffffff81bf2909: acpi_device_set_power.cold (STB_LOCAL)
ffffffff81686840-ffffffff81686b5d: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff81cef1f6-ffffffff81cef295: acpi_device_set_power.cold (STB_LOCAL)
ffffffff816fbbe0-ffffffff816fbf38: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81829220)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan_core.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff81829220-ffffffff81829661: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195b550)
Location: drivers/acpi/device_pm.c:162
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim_one
  - drivers/acpi/fan_core.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff8195b550-ffffffff8195b9bc: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a1a20)
Location: drivers/acpi/device_pm.c:162
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim_one
  - drivers/acpi/fan_core.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff819a1a20-ffffffff819a1e94: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819ea0d0)
Location: drivers/acpi/device_pm.c:162
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim_one
  - drivers/acpi/fan_core.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff819ea0d0-ffffffff819ea544: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff8000107676d0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffff8000107676d0-ffff8000107679e4: acpi_device_set_power (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff815cecc2-ffffffff815ced8a: acpi_device_set_power.cold (STB_LOCAL)
ffffffff815cde30-ffffffff815ce080: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff815b8882-ffffffff815b894a: acpi_device_set_power.cold (STB_LOCAL)
ffffffff815b79a0-ffffffff815b7bf0: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff815d0952-ffffffff815d0a1a: acpi_device_set_power.cold (STB_LOCAL)
ffffffff815cf930-ffffffff815cfc33: acpi_device_set_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_device_set_power(struct acpi_device *device, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/device_pm.c:160
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_device_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/fan.c:fan_set_cur_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff815ea812-ffffffff815ea8da: acpi_device_set_power.cold (STB_LOCAL)
ffffffff815e97f0-ffffffff815e9af3: acpi_device_set_power (STB_GLOBAL)
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
