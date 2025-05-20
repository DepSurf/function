# Function: <code>unlock_device_hotplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81547d60)
Location: drivers/base/core.c:60
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81547d60-ffffffff81547d77: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159aebf)
Location: drivers/base/core.c:60
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff815999c0-ffffffff815999d7: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c941f)
Location: drivers/base/core.c:626
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
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
ffffffff815c7c90-ffffffff815c7ca7: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815de13f)
Location: drivers/base/core.c:627
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff815dc920-ffffffff815dc937: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8164513f)
Location: drivers/base/core.c:630
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81643960-ffffffff81643977: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8168057f)
Location: drivers/base/core.c:663
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff8167ed10-ffffffff8167ed27: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816a000f)
Location: drivers/base/core.c:705
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff8169f150-ffffffff8169f167: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d877f)
Location: drivers/base/core.c:850
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff816d7790-ffffffff816d77a7: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fc87f)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff816fb8b0-ffffffff816fb8c7: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b61f6)
Location: drivers/base/core.c:1365
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
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
  - drivers/base/memory.c:probe_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff817b5050-ffffffff817b5067: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817cb666)
Location: drivers/base/core.c:1766
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
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
  - drivers/base/memory.c:probe_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff817c9740-ffffffff817c9757: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aefd6)
Location: drivers/base/core.c:1978
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
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
  - drivers/base/memory.c:probe_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff817acf30-ffffffff817acf47: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818381f3)
Location: drivers/base/core.c:2015
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
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
  - drivers/base/memory.c:probe_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff81836220-ffffffff81836237: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8197a55b)
Location: drivers/base/core.c:2027
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
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
  - drivers/base/memory.c:probe_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff819781f0-ffffffff8197820d: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae73bb)
Location: drivers/base/core.c:2264
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
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
  - drivers/base/memory.c:probe_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff81ae4a20-ffffffff81ae4a3d: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b357eb)
Location: drivers/base/core.c:2270
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
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
  - drivers/base/memory.c:probe_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff81b32db0-ffffffff81b32dcd: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8d20b)
Location: drivers/base/core.c:2285
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:control_store
  - kernel/cpu.c:control_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:target_store
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
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
  - drivers/base/memory.c:probe_store
  - drivers/base/memory.c:state_store
```
**Symbols:**

```
ffffffff81b8a6c0-ffffffff81b8a6dd: unlock_device_hotplug (STB_GLOBAL)
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
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e7238)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffff8000108e6138-ffff8000108e6160: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d5824)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
c09d47ac-c09d47d0: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097d464)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
  - arch/powerpc/platforms/pseries/pmem.c:dlpar_hp_pmem
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
c00000000097bd40-c00000000097bd7c: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057ba20)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
**Symbols:**

```
ffffffe00057ac2a-ffffffe00057ac54: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c206f)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff816c10a0-ffffffff816c10b7: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d31f)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff8169c350-ffffffff8169c367: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f053f)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff816ef570-ffffffff816ef587: unlock_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void unlock_device_hotplug();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170ad7f)
Location: drivers/base/core.c:887
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:write_cpuhp_target
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/power/user.c:snapshot_ioctl
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81709db0-ffffffff81709dc7: unlock_device_hotplug (STB_GLOBAL)
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
