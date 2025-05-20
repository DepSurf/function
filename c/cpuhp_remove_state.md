# Function: <code>cpuhp_remove_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81f853ac)
Location: include/linux/cpuhotplug.h:152
Inline: True
```
```
In arch/x86/events/amd/uncore.c (ffffffff81f85744)
Location: include/linux/cpuhotplug.h:152
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/kernel/hpet.c (ffffffff81f9cb43)
Location: include/linux/cpuhotplug.h:152
Inline: True
```
```
In kernel/profile.c (ffffffff81892dbc)
Location: include/linux/cpuhotplug.h:152
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
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
In arch/x86/events/core.c (ffffffff81fc07c9)
Location: include/linux/cpuhotplug.h:260
Inline: True
```
```
In arch/x86/events/amd/uncore.c (ffffffff81fc0b7e)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff821ccdd1)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81fce12a)
Location: include/linux/cpuhotplug.h:260
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81fce94f)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/hpet.c (ffffffff81fd8094)
Location: include/linux/cpuhotplug.h:260
Inline: True
```
```
In kernel/profile.c (ffffffff818c76b2)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff81ff212b)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff821ccf06)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff820a09fa)
Location: include/linux/cpuhotplug.h:292
Inline: True
```
```
In arch/x86/events/amd/uncore.c (ffffffff820a0e52)
Location: include/linux/cpuhotplug.h:292
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff822c1ed9)
Location: include/linux/cpuhotplug.h:292
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff820aeaca)
Location: include/linux/cpuhotplug.h:292
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff820af2f7)
Location: include/linux/cpuhotplug.h:292
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/hpet.c (ffffffff820b8ed6)
Location: include/linux/cpuhotplug.h:292
Inline: True
```
```
In kernel/profile.c (ffffffff818fee02)
Location: include/linux/cpuhotplug.h:292
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff820d478f)
Location: include/linux/cpuhotplug.h:292
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff822c200e)
Location: include/linux/cpuhotplug.h:292
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff826a6b45)
Location: include/linux/cpuhotplug.h:320
Inline: True
```
```
In arch/x86/events/amd/uncore.c (ffffffff826a6f9d)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff828d5059)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826b5337)
Location: include/linux/cpuhotplug.h:320
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff826b5b90)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/hpet.c (ffffffff826bf720)
Location: include/linux/cpuhotplug.h:320
Inline: True
```
```
In kernel/profile.c (ffffffff81988fdf)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff826dd355)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff828d518e)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff826cfcd1)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff826d0129)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff829068b8)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff826d88e5)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826df06d)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff826df8be)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/hpet.c (ffffffff826e94fa)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff819e5941)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff82707560)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff829069e5)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff82885d2b)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff828861e8)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82ade628)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288eb70)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82895871)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82ade680)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828a00b6)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81a20b41)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff828be932)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82ade7a7)
Location: include/linux/cpuhotplug.h:325
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff8289cc4d)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff8289d129)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82b03728)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a611b)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff828acd52)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828ad405)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82b037a3)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828b82ab)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81a91089)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff828d7af1)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82b038ca)
Location: include/linux/cpuhotplug.h:330
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff8289fc3d)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff828a0198)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82b12618)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a9123)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff828b0096)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b0749)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82b12693)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828be7a9)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81ac83c9)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff828dff62)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82b127c6)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff82cc5f2f)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff82cc6485)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82f240d0)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82cce9c6)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff82cd54de)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82cd5826)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82f2412d)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/hpet.c (ffffffff82ce2b57)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81bc0dc9)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff82cfd75b)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82f24241)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c2f70)
Location: include/linux/cpuhotplug.h:337
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff82fb183d)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff82fb1ddb)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8321c670)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82fba840)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff82fc1496)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82fc17de)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8321c6cd)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106987d)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
```
```
In arch/x86/kernel/hpet.c (ffffffff82fcfdf4)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81c39e59)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff82fea18c)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff8321c7e1)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3360)
Location: include/linux/cpuhotplug.h:342
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff831bbab7)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff831bc03f)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff83450668)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c4f0e)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff831cbb81)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff831cbec9)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff834506ca)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106a2cd)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
```
```
In arch/x86/kernel/hpet.c (ffffffff831da9e0)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81c2c429)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff831f4b06)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff834507de)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7cb9)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8329c043)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff83543c08)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5c21)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff832ad3d0)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff832ad72d)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83543c61)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81074a55)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
```
```
In arch/x86/kernel/hpet.c (ffffffff832bdc1a)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81d4ab19)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff832dadcc)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff83543d63)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81a55284)
Location: include/linux/cpuhotplug.h:435
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8344a85f)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff83721b50)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454d10)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8345e28b)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8345e5bf)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83721ba3)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810833af)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f612)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81f1a1cd)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff8348ff56)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff83721cd1)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc49f0)
Location: include/linux/cpuhotplug.h:441
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
In arch/x86/events/core.c (ffffffff83e64da7)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff842af3f0)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e728b0)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff83e7f334)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f7e5)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff842af500)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81095f5f)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
```
```
In arch/x86/kernel/hpet.c (ffffffff83e95c71)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff820c1e0d)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff83ec2815)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff842af750)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81d6a292)
Location: include/linux/cpuhotplug.h:445
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
In arch/x86/events/core.c (ffffffff83685464)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff83af1e60)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff836937d0)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff836a2084)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a2535)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83af1f70)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81098e1f)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
```
```
In arch/x86/kernel/hpet.c (ffffffff836b97f1)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff82145b4d)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff81435a50)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - mm/zswap.c:zswap_setup
```
```
In mm/zsmalloc.c (ffffffff83af22d0)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd5652)
Location: include/linux/cpuhotplug.h:443
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
In arch/x86/events/core.c (ffffffff838b45fc)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff83d4db80)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c33b3)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff838d2184)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d2635)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83d4dc90)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a043f)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
```
```
In arch/x86/kernel/hpet.c (ffffffff838ea121)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff8222826d)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zsmalloc.c (ffffffff83d4dfe0)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d7a2)
Location: include/linux/cpuhotplug.h:428
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/profile.c (ffff800010d9c27c)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffff800011459184)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffff8000114b8680)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725688)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4b8f8)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_reboot_notifier
  - drivers/firmware/arm_sdei.c:sdei_device_freeze
```
```
In drivers/perf/arm-cci.c (ffff800010b90a40)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/profile.c (c0e988b8)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (c15330c0)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (c15be93c)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/perf/arm-cci.c (c0c7acf8)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
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
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eaaec)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012c068)
Location: include/linux/cpuhotplug.h:331
Inline: True
```
```
In kernel/profile.c (c0000000001f9810)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (c000000001382b98)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (c0000000013cb6f4)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/profile.c (ffffffe0008c4442)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffe00001770c)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffe0000a0798)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff8288dc3d)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff8288e198)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82af2838)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82897133)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8289e0b5)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8289e768)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82af28b3)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828a977f)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81a67239)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff828c8e16)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82af29e6)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff8288bb8a)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff8288c0e5)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82ac2c60)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288f449)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff82896286)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82896939)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82ac2cdb)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828a182b)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81a23cf9)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff828c153b)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82ac2e0e)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
```
In drivers/hv/vmbus_drv.c (ffffffff82ac46b4)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_exit
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - drivers/hv/vmbus_drv.c:hv_kexec_handler
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
In arch/x86/events/core.c (ffffffff828a0c3d)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff828a1198)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82b0d900)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828aa123)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff828b1078)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b172b)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82b0d97b)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828bc67e)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81ad3649)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff828dbb96)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82b0daae)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
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
In arch/x86/events/core.c (ffffffff828a0c42)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff828a119d)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82b02450)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828aa133)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff828b10a6)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b1759)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82b024cb)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828bf7d6)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/profile.c (ffffffff81adfb49)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/zswap.c (ffffffff828e0fb7)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82b025fe)
Location: include/linux/cpuhotplug.h:331
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_exit
```
</details>
</li>
</ul>

## Differences
