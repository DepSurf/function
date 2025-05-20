# Function: <code>subsys_system_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8154a9e0)
Location: drivers/base/bus.c:1247
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_stub.c:edac_get_sysfs_subsys
```
**Symbols:**

```
ffffffff8154a9e0-ffffffff8154aa1a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159c610)
Location: drivers/base/bus.c:1242
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff8159c610-ffffffff8159c64a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815cab70)
Location: drivers/base/bus.c:1242
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff815cab70-ffffffff815cabaa: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815df7e0)
Location: drivers/base/bus.c:1201
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff815df7e0-ffffffff815df81a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81646810)
Location: drivers/base/bus.c:1201
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff81646810-ffffffff8164684a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81681cf0)
Location: drivers/base/bus.c:1199
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff81681cf0-ffffffff81681d2a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a1790)
Location: drivers/base/bus.c:1206
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff816a1790-ffffffff816a17ca: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816da570)
Location: drivers/base/bus.c:1180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff816da570-ffffffff816da5aa: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fe520)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff816fe520-ffffffff816fe55a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b81d0)
Location: drivers/base/bus.c:1157
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff817b81d0-ffffffff817b820a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817ccec0)
Location: drivers/base/bus.c:1157
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff817ccec0-ffffffff817ccefa: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b0840)
Location: drivers/base/bus.c:1140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff817b0840-ffffffff817b087a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81839a60)
Location: drivers/base/bus.c:1136
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff81839a60-ffffffff81839a9a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197c0a0)
Location: drivers/base/bus.c:1138
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff8197c0a0-ffffffff8197c0e4: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae91c0)
Location: drivers/base/bus.c:1138
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff81ae91c0-ffffffff81ae9204: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b37420)
Location: drivers/base/bus.c:1267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff81b37420-ffffffff81b37464: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int subsys_system_register(const struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8eea0)
Location: drivers/base/bus.c:1267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff81b8eea0-ffffffff81b8eee4: subsys_system_register (STB_GLOBAL)
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
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e9458)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffff8000108e9458-ffff8000108e94ac: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d7560)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
c09d7560-c09d75a8: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097fe90)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_init_sys
  - arch/powerpc/platforms/pseries/suspend.c:__machine_initcall_pseries_pseries_suspend_init
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
c00000000097fe90-c00000000097ff1c: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057d43c)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffe00057d43c-ffffffe00057d48c: subsys_system_register (STB_GLOBAL)
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
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c3d10)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff816c3d10-ffffffff816c3d4a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169efc0)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff8169efc0-ffffffff8169effa: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f21e0)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff816f21e0-ffffffff816f221a: subsys_system_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int subsys_system_register(struct bus_type *subsys, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170ca20)
Location: drivers/base/bus.c:1156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/container.c:container_dev_init
  - drivers/base/node.c:register_node_type
  - drivers/base/memory.c:memory_dev_init
  - drivers/edac/edac_module.c:edac_init
```
**Symbols:**

```
ffffffff8170ca20-ffffffff8170ca5a: subsys_system_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type *subsys</code> ➡️ <code>const struct bus_type *subsys</code>
</li>
</ul>
</details>
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
