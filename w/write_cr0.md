# Function: <code>write_cr0</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101cd73)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d8cd)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810398c8)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_ctx_switch
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/bugs.c (ffffffff81f699b5)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039af4)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c04f)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
```
```
In arch/x86/power/cpu.c (ffffffff816fb0e6)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bf9c)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c9fc)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81f916aa)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_ctx_switch
```
```
In arch/x86/kernel/fpu/bugs.c (ffffffff81f918a9)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039979)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c1e6)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81760346)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c7ac)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
```
```
In arch/x86/kernel/traps.c (ffffffff8102e163)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81fcca43)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e636)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff8178d346)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102c280)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff820ad23d)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e5a6)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff817ab4c3)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102d199)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff826b3ace)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051f16)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff818229c3)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e17e)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff826dd2ac)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054bbd)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff8186cbe3)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f2ee)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828936f4)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105227d)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff8188cbf3)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/traps.c (ffffffff810310e0)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828aad1c)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105537d)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff818d76d5)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff810319a0)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828add8c)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c7d)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81909735)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void write_cr0(long unsigned int x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbd967)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810411e8)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105addb)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81bba2e7)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
```
**Symbols:**

```
ffffffff810411a0-ffffffff810411ad: write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void write_cr0(long unsigned int x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c360ca)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810410b8)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105993b)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81bceb57)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
```
**Symbols:**

```
ffffffff81041070-ffffffff8104107d: write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void write_cr0(long unsigned int x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c2856a)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81042aa3)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a2bb)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81bc2507)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
```
**Symbols:**

```
ffffffff81042a60-ffffffff81042a6d: write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void write_cr0(long unsigned int x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d466da)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81048e13)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8106370b)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81c92b95)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
```
**Symbols:**

```
ffffffff81048dd0-ffffffff81048ddd: write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void write_cr0(long unsigned int x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81f149fa)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff83459f57)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810703aa)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81e42501)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
**Symbols:**

```
ffffffff81052170-ffffffff81052196: write_cr0 (STB_LOCAL)
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
In arch/x86/kernel/traps.c (ffffffff820bbdba)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff83e79bef)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ac5e)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/power/cpu.c (ffffffff8201cee1)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff8213d4ea)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8369c30f)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c5ce)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/power/cpu.c (ffffffff8209d571)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff8221f50a)
Location: arch/x86/include/asm/paravirt.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff838cbfef)
Location: arch/x86/include/asm/paravirt.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8107381e)
Location: arch/x86/include/asm/paravirt.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/power/cpu.c (ffffffff82174d71)
Location: arch/x86/include/asm/paravirt.h:141
Inline: True
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031b00)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8289bdab)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810557fd)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff818a8af5)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff810215d5)
Location: arch/x86/include/asm/special_insns.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8289404b)
Location: arch/x86/include/asm/special_insns.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81045939)
Location: arch/x86/include/asm/special_insns.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff818637ac)
Location: arch/x86/include/asm/special_insns.h:148
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/traps.c (ffffffff81031960)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828aed6e)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c2d)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff818fa155)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff81032820)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828aed9c)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810570cd)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff8191b2b5)
Location: arch/x86/include/asm/paravirt.h:112
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
