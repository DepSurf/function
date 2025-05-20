# Function: <code>native_write_msr_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bbe2)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff8102623f)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81064412)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
```
```
In arch/x86/kernel/paravirt.c (ffffffff810644b0)
Location: arch/x86/include/asm/msr.h:91
Inline: False
```
**Symbols:**

```
ffffffff810644b0-ffffffff810644be: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b084)
Location: arch/x86/include/asm/msr.h:130
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff8102567a)
Location: arch/x86/include/asm/msr.h:130
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81064094)
Location: arch/x86/include/asm/msr.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
```
```
In arch/x86/kernel/paravirt.c (ffffffff810646d0)
Location: arch/x86/include/asm/msr.h:130
Inline: False
```
**Symbols:**

```
ffffffff810646d0-ffffffff81064705: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b7b4)
Location: arch/x86/include/asm/msr.h:144
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff81025d9a)
Location: arch/x86/include/asm/msr.h:144
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81067594)
Location: arch/x86/include/asm/msr.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067bb0)
Location: arch/x86/include/asm/msr.h:144
Inline: False
```
**Symbols:**

```
ffffffff81067bb0-ffffffff81067be5: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101c72f)
Location: arch/x86/include/asm/msr.h:155
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101e8c4)
Location: arch/x86/include/asm/msr.h:155
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81066864)
Location: arch/x86/include/asm/msr.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066e90)
Location: arch/x86/include/asm/msr.h:155
Inline: False
```
**Symbols:**

```
ffffffff81066e90-ffffffff81066ec5: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d3cf)
Location: arch/x86/include/asm/msr.h:156
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f574)
Location: arch/x86/include/asm/msr.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8106aa34)
Location: arch/x86/include/asm/msr.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106afc0)
Location: arch/x86/include/asm/msr.h:156
Inline: False
```
**Symbols:**

```
ffffffff8106afc0-ffffffff8106aff6: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101dd5c)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102007a)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8106d717)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106dc60)
Location: arch/x86/include/asm/msr.h:170
Inline: False
```
**Symbols:**

```
ffffffff8106dc60-ffffffff8106dc8f: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d5d6)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f8fa)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073cd0)
Location: arch/x86/include/asm/msr.h:170
Inline: False
```
**Symbols:**

```
ffffffff81073cd0-ffffffff81073cff: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101f155)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021459)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077840)
Location: arch/x86/include/asm/msr.h:170
Inline: False
```
**Symbols:**

```
ffffffff81077840-ffffffff8107786e: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fab5)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021da9)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff810788b0)
Location: arch/x86/include/asm/msr.h:170
Inline: False
```
**Symbols:**

```
ffffffff810788b0-ffffffff810788de: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810221c5)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024699)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fcc0)
Location: arch/x86/include/asm/msr.h:170
Inline: False
```
**Symbols:**

```
ffffffff8107fcc0-ffffffff8107fcee: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810228a5)
Location: arch/x86/include/asm/msr.h:168
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024e19)
Location: arch/x86/include/asm/msr.h:168
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f8e0)
Location: arch/x86/include/asm/msr.h:168
Inline: False
```
**Symbols:**

```
ffffffff8107f8e0-ffffffff8107f90e: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81024b25)
Location: arch/x86/include/asm/msr.h:168
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81026fd9)
Location: arch/x86/include/asm/msr.h:168
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080960)
Location: arch/x86/include/asm/msr.h:168
Inline: False
```
**Symbols:**

```
ffffffff81080960-ffffffff8108098e: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81028f65)
Location: arch/x86/include/asm/msr.h:168
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102b479)
Location: arch/x86/include/asm/msr.h:168
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f8b0)
Location: arch/x86/include/asm/msr.h:168
Inline: False
```
**Symbols:**

```
ffffffff8108f8b0-ffffffff8108f8db: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8102d83d)
Location: arch/x86/include/asm/msr.h:153
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102fcbc)
Location: arch/x86/include/asm/msr.h:153
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0600)
Location: arch/x86/include/asm/msr.h:153
Inline: False
```
**Symbols:**

```
ffffffff810a0600-ffffffff810a0643: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034b52)
Location: arch/x86/include/asm/msr.h:153
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103852a)
Location: arch/x86/include/asm/msr.h:153
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8240)
Location: arch/x86/include/asm/msr.h:153
Inline: False
```
**Symbols:**

```
ffffffff810b8240-ffffffff810b8283: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034ad2)
Location: arch/x86/include/asm/msr.h:153
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810383c5)
Location: arch/x86/include/asm/msr.h:153
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb3d0)
Location: arch/x86/include/asm/msr.h:153
Inline: False
```
**Symbols:**

```
ffffffff810bb3d0-ffffffff810bb413: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8103acd2)
Location: arch/x86/include/asm/msr.h:153
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103e735)
Location: arch/x86/include/asm/msr.h:153
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c27e0)
Location: arch/x86/include/asm/msr.h:153
Inline: False
```
**Symbols:**

```
ffffffff810c27e0-ffffffff810c2823: native_write_msr_safe (STB_LOCAL)
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fc15)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021f09)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff810778b0)
Location: arch/x86/include/asm/msr.h:170
Inline: False
```
**Symbols:**

```
ffffffff810778b0-ffffffff810778de: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8288b894)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100cd7d)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff81010fe6)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff810131c0)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff81013853)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103641b)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a97f)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103ff02)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042513)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810457f5)
Location: arch/x86/include/asm/msr.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82899307)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81052417)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff815458f9)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8154628d)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f0924)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8184b0e5)
Location: arch/x86/include/asm/msr.h:170
Inline: True
```
**Symbols:**

```
ffffffff8100d772-ffffffff8100d7a1: native_write_msr_safe (STB_LOCAL)
ffffffff81012ac0-ffffffff81012ae9: native_write_msr_safe.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fa75)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021d69)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077860)
Location: arch/x86/include/asm/msr.h:170
Inline: False
```
**Symbols:**

```
ffffffff81077860-ffffffff8107788e: native_write_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101fcc5)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021fb9)
Location: arch/x86/include/asm/msr.h:170
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079900)
Location: arch/x86/include/asm/msr.h:170
Inline: False
```
**Symbols:**

```
ffffffff81079900-ffffffff8107992e: native_write_msr_safe (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int low</code> ➡️ <code>u32 low</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int high</code> ➡️ <code>u32 high</code>
</li>
</ul>
</details>
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
