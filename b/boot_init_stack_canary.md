# Function: <code>boot_init_stack_canary</code>

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
In init/main.c (ffffffff81f59bbf)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/smpboot.c (ffffffff810516a0)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/sched/idle.c (ffffffff810c3d86)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In init/main.c (ffffffff81f81bba)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105184e)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/sched/idle.c (ffffffff810c7a66)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In init/main.c (ffffffff81fbdbf1)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/smpboot.c (ffffffff810541a1)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/sched/idle.c (ffffffff810cdd26)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In init/main.c (ffffffff8209dc7d)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053af1)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/sched/idle.c (ffffffff810ca686)
Location: arch/x86/include/asm/stackprotector.h:60
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In init/main.c (ffffffff826a3c85)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105785b)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/sched/idle.c (ffffffff810d1e96)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In init/main.c (ffffffff826ccd24)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a740)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/sched/idle.c (ffffffff810c4648)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In init/main.c (ffffffff82882d3c)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a671)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff810603c0)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In init/main.c (ffffffff8289a034)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c481)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063c9d)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In init/main.c (ffffffff8289d019)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cb61)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106434c)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In init/main.c (ffffffff82cc357e)
Location: arch/x86/include/asm/stackprotector.h:66
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102f331)
Location: arch/x86/include/asm/stackprotector.h:66
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106adea)
Location: arch/x86/include/asm/stackprotector.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In init/main.c (ffffffff82faf635)
Location: arch/x86/include/asm/stackprotector.h:66
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff831b9659)
Location: arch/x86/include/asm/stackprotector.h:51
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff832999db)
Location: arch/x86/include/asm/stackprotector.h:51
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff83447c0a)
Location: arch/x86/include/asm/stackprotector.h:51
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff83e61371)
Location: arch/x86/include/asm/stackprotector.h:50
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff836817e0)
Location: arch/x86/include/asm/stackprotector.h:50
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff838b0805)
Location: arch/x86/include/asm/stackprotector.h:50
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffff80001143100c)
Location: arch/arm64/include/asm/stackprotector.h:27
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c1500ff8)
Location: arch/arm/include/asm/stackprotector.h:31
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (c00000000134419c)
Location: arch/powerpc/include/asm/stackprotector.h:22
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/powerpc/kernel/smp.c (c00000000005642c)
Location: arch/powerpc/include/asm/stackprotector.h:22
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (0)
Location: include/linux/stackprotector.h:12
Inline: True
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
In init/main.c (ffffffff8288b019)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ccc1)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063e3c)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In init/main.c (ffffffff82888fb5)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105413f)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In init/main.c (ffffffff8289e019)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cb21)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff810642ec)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In init/main.c (ffffffff8289e020)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d921)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff810658b3)
Location: arch/x86/include/asm/stackprotector.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
</ul>

## Differences
