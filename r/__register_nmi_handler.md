# Function: <code>__register_nmi_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032460)
Location: arch/x86/kernel/nmi.c:151
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/hw_nmi.c:register_trigger_all_cpu_backtrace
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81032460-ffffffff810325f0: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031590)
Location: arch/x86/kernel/nmi.c:154
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/hw_nmi.c:register_trigger_all_cpu_backtrace
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81031590-ffffffff8103173c: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810311e0)
Location: arch/x86/kernel/nmi.c:154
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff810311e0-ffffffff8103138c: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8102f4c0)
Location: arch/x86/kernel/nmi.c:156
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8102f4c0-ffffffff8102f5a8: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810314c0)
Location: arch/x86/kernel/nmi.c:156
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff810314c0-ffffffff810315a8: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032410)
Location: arch/x86/kernel/nmi.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81032410-ffffffff810324f8: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810336d0)
Location: arch/x86/kernel/nmi.c:156
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff810336d0-ffffffff810337b8: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035890)
Location: arch/x86/kernel/nmi.c:159
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81035890-ffffffff81035979: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035fb0)
Location: arch/x86/kernel/nmi.c:159
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81035fb0-ffffffff81036089: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81037fd0)
Location: arch/x86/kernel/nmi.c:155
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81037fd0-ffffffff810380b2: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81038b10)
Location: arch/x86/kernel/nmi.c:155
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81038b10-ffffffff81038bf2: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103a620)
Location: arch/x86/kernel/nmi.c:155
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8103a620-ffffffff8103a702: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103ffd0)
Location: arch/x86/kernel/nmi.c:155
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8103ffd0-ffffffff810400ce: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810476a0)
Location: arch/x86/kernel/nmi.c:155
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff810476a0-ffffffff810477ce: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810520d0)
Location: arch/x86/kernel/nmi.c:155
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff810520d0-ffffffff810521fe: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81052e30)
Location: arch/x86/kernel/nmi.c:164
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81052e30-ffffffff81052f5e: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8105a050)
Location: arch/x86/kernel/nmi.c:165
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8105a050-ffffffff8105a17e: __register_nmi_handler (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036110)
Location: arch/x86/kernel/nmi.c:159
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
```
**Symbols:**

```
ffffffff81036110-ffffffff810361e9: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81025a60)
Location: arch/x86/kernel/nmi.c:159
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
```
**Symbols:**

```
ffffffff81025a60-ffffffff81025b39: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035f70)
Location: arch/x86/kernel/nmi.c:159
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81035f70-ffffffff81036049: __register_nmi_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction *action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036f50)
Location: arch/x86/kernel/nmi.c:159
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81036f50-ffffffff81037029: __register_nmi_handler (STB_GLOBAL)
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
