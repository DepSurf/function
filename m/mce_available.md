# Function: <code>mce_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046060)
Location: arch/x86/kernel/cpu/mcheck/mce.c:442
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_restart
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear
```
**Symbols:**

```
ffffffff81046060-ffffffff8104608d: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046050)
Location: arch/x86/kernel/cpu/mcheck/mce.c:485
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81046050-ffffffff8104607d: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047ce0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:510
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81047ce0-ffffffff81047d0d: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810475b0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:441
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff810475b0-ffffffff810475dd: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b070)
Location: arch/x86/kernel/cpu/mcheck/mce.c:450
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104b070-ffffffff8104b09d: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104d9b0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:447
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104d9b0-ffffffff8104d9dd: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b0b0)
Location: arch/x86/kernel/cpu/mce/core.c:445
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104b0b0-ffffffff8104b0dd: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dfa0)
Location: arch/x86/kernel/cpu/mce/core.c:462
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104dfa0-ffffffff8104dfc9: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e930)
Location: arch/x86/kernel/cpu/mce/core.c:462
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104e930-ffffffff8104e959: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052d9e)
Location: arch/x86/kernel/cpu/mce/core.c:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81053590-ffffffff810535b9: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051eee)
Location: arch/x86/kernel/cpu/mce/core.c:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff810526b0-ffffffff810526d9: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105365e)
Location: arch/x86/kernel/cpu/mce/core.c:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81053f60-ffffffff81053f89: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105bd2f)
Location: arch/x86/kernel/cpu/mce/core.c:519
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8105c820-ffffffff8105c849: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810681fe)
Location: arch/x86/kernel/cpu/mce/core.c:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81068f40-ffffffff81068f71: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f691)
Location: arch/x86/kernel/cpu/mce/core.c:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81078ab0-ffffffff81078ae1: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a23e1)
Location: arch/x86/kernel/cpu/mce/core.c:438
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8107ad60-ffffffff8107ad91: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d24e1)
Location: arch/x86/kernel/cpu/mce/core.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
```
**Symbols:**

```
ffffffff81082200-ffffffff81082231: mce_available (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ea90)
Location: arch/x86/kernel/cpu/mce/core.c:462
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104ea90-ffffffff8104eab9: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103df60)
Location: arch/x86/kernel/cpu/mce/core.c:462
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8103df60-ffffffff8103df89: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e8e0)
Location: arch/x86/kernel/cpu/mce/core.c:462
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104e8e0-ffffffff8104e909: mce_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mce_available(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104fd20)
Location: arch/x86/kernel/cpu/mce/core.c:462
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104fd20-ffffffff8104fd49: mce_available (STB_GLOBAL)
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
