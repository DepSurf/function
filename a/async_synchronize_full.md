# Function: <code>async_synchronize_full</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a31a0)
Location: kernel/async.c:237
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:SyS_delete_module
  - kernel/module.c:do_init_module
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
```
**Symbols:**

```
ffffffff810a31a0-ffffffff810a31b9: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a68b0)
Location: kernel/async.c:237
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810a68b0-ffffffff810a68c9: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810ac510)
Location: kernel/async.c:237
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810ac510-ffffffff810ac529: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a90e0)
Location: kernel/async.c:237
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810a90e0-ffffffff810a90f9: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810af960)
Location: kernel/async.c:241
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810af960-ffffffff810af979: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b67c0)
Location: kernel/async.c:241
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810b67c0-ffffffff810b67d9: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810bfc10)
Location: kernel/async.c:241
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810bfc10-ffffffff810bfc29: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c5d40)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810c5d40-ffffffff810c5d59: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810cee20)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
ffffffff810cee20-ffffffff810cee39: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d8b20)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810d8b20-ffffffff810d8b39: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d3cc0)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810d3cc0-ffffffff810d3cd9: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d5950)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810d5950-ffffffff810d5969: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810e8b70)
Location: kernel/async.c:239
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810e8b70-ffffffff810e8b89: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81103630)
Location: kernel/async.c:239
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module/main.c:do_init_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff81103630-ffffffff81103651: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81128cf0)
Location: kernel/async.c:239
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module/main.c:do_init_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff81128cf0-ffffffff81128d11: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff811361a0)
Location: kernel/async.c:239
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:find_resume_device
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module/main.c:do_init_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff811361a0-ffffffff811361c1: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81141350)
Location: kernel/async.c:281
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:find_resume_device
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module/main.c:do_init_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff81141350-ffffffff81141371: async_synchronize_full (STB_GLOBAL)
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
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffff80001012e7d0)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__arm64_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
ffff80001012e7d0-ffff80001012e7f4: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (c037e8f4)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
c037e8f4-c037e91c: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (c000000000177a10)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
c000000000177a10-c000000000177a2c: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffe0000e295c)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
ffffffe0000e295c-ffffffe0000e2982: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c91a0)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
ffffffff810c91a0-ffffffff810c91b9: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b79c0)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
ffffffff810b79c0-ffffffff810b79d9: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c86d0)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
ffffffff810c86d0-ffffffff810c86e9: async_synchronize_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void async_synchronize_full();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d0c10)
Location: kernel/async.c:242
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/ata/libata-core.c:ata_host_detach
```
**Symbols:**

```
ffffffff810d0c10-ffffffff810d0c29: async_synchronize_full (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
