# Function: <code>lock_device_hotplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81547d40)
Location: drivers/base/core.c:55
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81547d40-ffffffff81547d57: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815999a0)
Location: drivers/base/core.c:55
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff815999a0-ffffffff815999b7: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7c70)
Location: drivers/base/core.c:621
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff815c7c70-ffffffff815c7c87: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dc900)
Location: drivers/base/core.c:622
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff815dc900-ffffffff815dc917: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81643940)
Location: drivers/base/core.c:625
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81643940-ffffffff81643957: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167ecf0)
Location: drivers/base/core.c:658
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff8167ecf0-ffffffff8167ed07: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169f130)
Location: drivers/base/core.c:700
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8169f130-ffffffff8169f147: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d7770)
Location: drivers/base/core.c:845
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff816d7770-ffffffff816d7787: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fb890)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff816fb890-ffffffff816fb8a7: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b5030)
Location: drivers/base/core.c:1360
Inline: False
Direct callers:
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff817b5030-ffffffff817b5047: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c9720)
Location: drivers/base/core.c:1761
Inline: False
Direct callers:
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff817c9720-ffffffff817c9737: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817acf10)
Location: drivers/base/core.c:1973
Inline: False
Direct callers:
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff817acf10-ffffffff817acf27: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81836200)
Location: drivers/base/core.c:2010
Inline: False
Direct callers:
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81836200-ffffffff81836217: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819781d0)
Location: drivers/base/core.c:2022
Inline: False
Direct callers:
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff819781d0-ffffffff819781ed: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae49f0)
Location: drivers/base/core.c:2259
Inline: False
Direct callers:
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81ae49f0-ffffffff81ae4a0d: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b32d80)
Location: drivers/base/core.c:2265
Inline: False
Direct callers:
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81b32d80-ffffffff81b32d9d: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8a690)
Location: drivers/base/core.c:2280
Inline: False
Direct callers:
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81b8a690-ffffffff81b8a6ad: lock_device_hotplug (STB_GLOBAL)
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
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e6110)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffff8000108e6110-ffff8000108e6138: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d4788)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
c09d4788-c09d47ac: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097bd00)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
  - arch/powerpc/platforms/pseries/pmem.c:dlpar_hp_pmem
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
```
**Symbols:**

```
c00000000097bd00-c00000000097bd3c: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057ac00)
Location: drivers/base/core.c:882
Inline: False
```
**Symbols:**

```
ffffffe00057ac00-ffffffe00057ac2a: lock_device_hotplug (STB_GLOBAL)
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
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c1080)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff816c1080-ffffffff816c1097: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169c330)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff8169c330-ffffffff8169c347: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef550)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff816ef550-ffffffff816ef567: lock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709d90)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81709d90-ffffffff81709da7: lock_device_hotplug (STB_GLOBAL)
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
