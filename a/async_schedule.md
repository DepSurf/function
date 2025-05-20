# Function: <code>async_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
async_cookie_t async_schedule(async_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a33a0)
Location: kernel/async.c:207
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/ata/libata-core.c:ata_host_register
```
**Symbols:**

```
ffffffff810a33a0-ffffffff810a33b7: async_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
async_cookie_t async_schedule(async_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a6ac0)
Location: kernel/async.c:207
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_register
```
**Symbols:**

```
ffffffff810a6ac0-ffffffff810a6ad7: async_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
async_cookie_t async_schedule(async_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810ac720)
Location: kernel/async.c:207
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_register
```
**Symbols:**

```
ffffffff810ac720-ffffffff810ac737: async_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
async_cookie_t async_schedule(async_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a92f0)
Location: kernel/async.c:207
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810a92f0-ffffffff810a9307: async_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
async_cookie_t async_schedule(async_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810afb80)
Location: kernel/async.c:211
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810afb80-ffffffff810afb97: async_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
async_cookie_t async_schedule(async_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b69e0)
Location: kernel/async.c:211
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810b69e0-ffffffff810b69f7: async_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
async_cookie_t async_schedule(async_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810bfa80)
Location: kernel/async.c:211
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810bfa80-ffffffff810bfa97: async_schedule (STB_GLOBAL)
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
In drivers/acpi/battery.c (ffffffff828f4590)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/base/power/main.c (ffffffff816eb481)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81753cec)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81771e73)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff828fd5e7)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/base/power/main.c (ffffffff8170f441)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81777f6c)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81795e22)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff82d14525)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8183aecc)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81859fba)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff830021a6)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184b7a2)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81c17fcd)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff8320d245)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182ec0c)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81c09dc5)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff832f5a5d)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff818ba9dc)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81d0e53f)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff834ade96)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a06437)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81ed7391)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff83ee7024)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b85237)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81bac743)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff8370c9e4)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd8fb7)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81c038d3)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff839400c4)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2dce6)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81c5907d)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffff800011480334)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/base/power/main.c (ffff8000108ffaa4)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffff80001097ca0c)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffff80001099ee4c)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09e9e00)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (c0a502e4)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (c0a6f564)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099cdec)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (c000000000a37ca4)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (c000000000a63358)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e3654)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffe0005fed46)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/base/power/main.c (ffffffff816d5181)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172c65c)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/nvme/host/pci.c (ffffffff81751427)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/ata/libata-core.c (ffffffff8175af39)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/base/power/main.c (ffffffff816afe31)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81705a7c)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/nvme/host/pci.c (ffffffff817312c7)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/ata/libata-core.c (ffffffff8173add9)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff828f890a)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/base/power/main.c (ffffffff81703101)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176b42c)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8178aca2)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
In drivers/acpi/battery.c (ffffffff828fe63b)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_init
```
```
In drivers/base/power/main.c (ffffffff8171d981)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81786b76)
Location: include/linux/async.h:52
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff817a4af2)
Location: include/linux/async.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
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
</ul>
