# Function: <code>native_read_msr_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bc85)
Location: arch/x86/include/asm/msr.h:68
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff8102612c)
Location: arch/x86/include/asm/msr.h:68
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064490)
Location: arch/x86/include/asm/msr.h:68
Inline: False
```
**Symbols:**

```
ffffffff81064490-ffffffff810644a7: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b107)
Location: arch/x86/include/asm/msr.h:96
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff810257dc)
Location: arch/x86/include/asm/msr.h:96
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064710)
Location: arch/x86/include/asm/msr.h:96
Inline: False
```
**Symbols:**

```
ffffffff81064710-ffffffff81064748: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b837)
Location: arch/x86/include/asm/msr.h:96
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff81025efc)
Location: arch/x86/include/asm/msr.h:96
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067bf0)
Location: arch/x86/include/asm/msr.h:96
Inline: False
```
**Symbols:**

```
ffffffff81067bf0-ffffffff81067c28: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101c82b)
Location: arch/x86/include/asm/msr.h:122
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101e9a2)
Location: arch/x86/include/asm/msr.h:122
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066ed0)
Location: arch/x86/include/asm/msr.h:122
Inline: False
```
**Symbols:**

```
ffffffff81066ed0-ffffffff81066f08: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d4cb)
Location: arch/x86/include/asm/msr.h:123
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810201f2)
Location: arch/x86/include/asm/msr.h:123
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b000)
Location: arch/x86/include/asm/msr.h:123
Inline: False
```
**Symbols:**

```
ffffffff8106b000-ffffffff8106b039: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101debc)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020a72)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106dc90)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
**Symbols:**

```
ffffffff8106dc90-ffffffff8106dccc: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d6b0)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f972)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073d00)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
**Symbols:**

```
ffffffff81073d00-ffffffff81073d3c: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101f2be)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810214d3)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077870)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
**Symbols:**

```
ffffffff81077870-ffffffff810778b1: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fc1e)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021e23)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff810788e0)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
**Symbols:**

```
ffffffff810788e0-ffffffff81078921: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8102230e)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024713)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fcf0)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
**Symbols:**

```
ffffffff8107fcf0-ffffffff8107fd35: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810229ee)
Location: arch/x86/include/asm/msr.h:135
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024e93)
Location: arch/x86/include/asm/msr.h:135
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f910)
Location: arch/x86/include/asm/msr.h:135
Inline: False
```
**Symbols:**

```
ffffffff8107f910-ffffffff8107f955: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81024c8b)
Location: arch/x86/include/asm/msr.h:135
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81027053)
Location: arch/x86/include/asm/msr.h:135
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080990)
Location: arch/x86/include/asm/msr.h:135
Inline: False
```
**Symbols:**

```
ffffffff81080990-ffffffff810809d5: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810290c8)
Location: arch/x86/include/asm/msr.h:135
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102b4f3)
Location: arch/x86/include/asm/msr.h:135
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f8e0)
Location: arch/x86/include/asm/msr.h:135
Inline: False
```
**Symbols:**

```
ffffffff8108f8e0-ffffffff8108f922: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8102d948)
Location: arch/x86/include/asm/msr.h:126
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102fd56)
Location: arch/x86/include/asm/msr.h:126
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0650)
Location: arch/x86/include/asm/msr.h:126
Inline: False
```
**Symbols:**

```
ffffffff810a0650-ffffffff810a06a9: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034cb8)
Location: arch/x86/include/asm/msr.h:126
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103702a)
Location: arch/x86/include/asm/msr.h:126
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b82a0)
Location: arch/x86/include/asm/msr.h:126
Inline: False
```
**Symbols:**

```
ffffffff810b82a0-ffffffff810b82f9: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034c38)
Location: arch/x86/include/asm/msr.h:126
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81036f7a)
Location: arch/x86/include/asm/msr.h:126
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb430)
Location: arch/x86/include/asm/msr.h:126
Inline: False
```
**Symbols:**

```
ffffffff810bb430-ffffffff810bb489: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8103ae38)
Location: arch/x86/include/asm/msr.h:126
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d1fa)
Location: arch/x86/include/asm/msr.h:126
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2840)
Location: arch/x86/include/asm/msr.h:126
Inline: False
```
**Symbols:**

```
ffffffff810c2840-ffffffff810c2899: native_read_msr_safe (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fd7e)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021f83)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff810778e0)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
**Symbols:**

```
ffffffff810778e0-ffffffff81077921: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006f65)
Location: arch/x86/include/asm/msr.h:137
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff81007170)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100d7a1)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f329)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81039166)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a94b)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103ae18)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c6be)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8103f0c9)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fe32)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041044)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8289828e)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105232b)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810572bd)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289f239)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289ff97)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c18c)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cf35)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d776)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81067d9e)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff81545a13)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81546265)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815cb76f)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f0c9f)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816883b2)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696f95)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/edac/mce_amd.c (ffffffff81829b83)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - drivers/edac/mce_amd.c:amd_decode_mce
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183ade1)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81849e4e)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8184b12c)
Location: arch/x86/include/asm/msr.h:137
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff828f8df1)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff81863641)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff81006f65-ffffffff81006fa4: native_read_msr_safe (STB_LOCAL)
ffffffff8100d7a1-ffffffff8100d7e0: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fbde)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021de3)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077890)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
**Symbols:**

```
ffffffff81077890-ffffffff810778d1: native_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fe2e)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022033)
Location: arch/x86/include/asm/msr.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079930)
Location: arch/x86/include/asm/msr.h:137
Inline: False
```
**Symbols:**

```
ffffffff81079930-ffffffff81079971: native_read_msr_safe (STB_LOCAL)
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
