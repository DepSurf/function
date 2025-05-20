# Function: <code>irq_get_next_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810da310)
Location: kernel/irq/irqdesc.c:532
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
```
**Symbols:**

```
ffffffff810da310-ffffffff810da330: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810df810)
Location: kernel/irq/irqdesc.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
```
**Symbols:**

```
ffffffff810df810-ffffffff810df830: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e60f0)
Location: kernel/irq/irqdesc.c:781
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
```
**Symbols:**

```
ffffffff810e60f0-ffffffff810e6110: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5740)
Location: kernel/irq/irqdesc.c:798
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810e5740-ffffffff810e5760: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810eda00)
Location: kernel/irq/irqdesc.c:787
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810eda00-ffffffff810eda20: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f5e40)
Location: kernel/irq/irqdesc.c:804
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810f5e40-ffffffff810f5e60: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811015d0)
Location: kernel/irq/irqdesc.c:809
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff811015d0-ffffffff811015f0: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109dd0)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81109dd0-ffffffff81109df0: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811161a0)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff811161a0-ffffffff811161c0: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81121e50)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_all_irqs
  - fs/proc/stat.c:show_all_irqs
```
**Symbols:**

```
ffffffff81121e50-ffffffff81121e70: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111ded0)
Location: kernel/irq/irqdesc.c:821
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_all_irqs
  - fs/proc/stat.c:show_all_irqs
```
**Symbols:**

```
ffffffff8111ded0-ffffffff8111def0: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111e160)
Location: kernel/irq/irqdesc.c:821
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8111e160-ffffffff8111e188: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113e5e0)
Location: kernel/irq/irqdesc.c:833
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8113e5e0-ffffffff8113e608: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161b70)
Location: kernel/irq/irqdesc.c:810
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81161b70-ffffffff81161baa: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81195340)
Location: kernel/irq/irqdesc.c:837
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81195340-ffffffff8119536a: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6cd0)
Location: kernel/irq/irqdesc.c:856
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff811a6cd0-ffffffff811a6d39: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b67f0)
Location: kernel/irq/irqdesc.c:856
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff811b67f0-ffffffff811b6859: irq_get_next_irq (STB_GLOBAL)
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
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010177d30)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffff800010177d30-ffff800010177d70: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c96f4)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c03c96f4-c03c9728: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d1770)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c0000000001d1770-c0000000001d17bc: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe00011299c)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffe00011299c-ffffffe0001129dc: irq_get_next_irq (STB_GLOBAL)
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
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e780)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8110e780-ffffffff8110e7a0: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ff4d0)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff810ff4d0-ffffffff810ff4f0: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c670)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8110c670-ffffffff8110c690: irq_get_next_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int irq_get_next_irq(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117b80)
Location: kernel/irq/irqdesc.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/topology.c:arch_register_cpu
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81117b80-ffffffff81117ba0: irq_get_next_irq (STB_GLOBAL)
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
