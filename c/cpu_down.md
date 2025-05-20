# Function: <code>cpu_down</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081800)
Location: kernel/cpu.c:433
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff81081800-ffffffff81081849: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084780)
Location: kernel/cpu.c:872
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff81084780-ffffffff81084792: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089720)
Location: kernel/cpu.c:833
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff81089720-ffffffff81089732: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086770)
Location: kernel/cpu.c:756
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff81086770-ffffffff81086782: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108d520)
Location: kernel/cpu.c:932
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff8108d520-ffffffff8108d532: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090e50)
Location: kernel/cpu.c:1017
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff81090e50-ffffffff81090e62: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81098fa0)
Location: kernel/cpu.c:1033
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff81098fa0-ffffffff81098fb2: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d530)
Location: kernel/cpu.c:1045
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff8109d530-ffffffff8109d542: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3a80)
Location: kernel/cpu.c:1054
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810a3a80-ffffffff810a3a92: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aadfa)
Location: kernel/cpu.c:1060
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_device_down
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a668a)
Location: kernel/cpu.c:1064
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_device_down
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a76fa)
Location: kernel/cpu.c:1169
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_device_down
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b913d)
Location: kernel/cpu.c:1193
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpu_device_down
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cfab6)
Location: kernel/cpu.c:1205
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpu_device_down
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810edec8)
Location: kernel/cpu.c:1231
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpu_device_down
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f9fad)
Location: kernel/cpu.c:1505
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpu_device_down
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff811033cd)
Location: kernel/cpu.c:1543
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpu_device_down
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
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f93b0)
Location: kernel/cpu.c:1054
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffff8000100f93b0-ffff8000100f93e0: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c03576b0)
Location: kernel/cpu.c:1054
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
c03576b0-c03576d0: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140180)
Location: kernel/cpu.c:1054
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
c000000000140180-c000000000140198: cpu_down (STB_GLOBAL)
```
</details>
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
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d3a0)
Location: kernel/cpu.c:1054
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff8109d3a0-ffffffff8109d3b2: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bdc0)
Location: kernel/cpu.c:1054
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff8108bdc0-ffffffff8108bdd2: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d350)
Location: kernel/cpu.c:1054
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff8109d350-ffffffff8109d362: cpu_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpu_down(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a51d0)
Location: kernel/cpu.c:1054
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810a51d0-ffffffff810a51e2: cpu_down (STB_GLOBAL)
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
