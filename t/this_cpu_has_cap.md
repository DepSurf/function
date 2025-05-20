# Function: <code>this_cpu_has_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool this_cpu_has_cap(unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/cpufeature.c (ffff80001009af18)
Location: arch/arm64/kernel/cpufeature.c:2029
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/traps.c:arm64_is_fatal_ras_serror
  - arch/arm64/kernel/cpu_errata.c:has_ssbd_mitigation
  - arch/arm64/kernel/cpu_errata.c:has_ssbd_mitigation
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - arch/arm64/kvm/handle_exit.c:handle_exit_early
  - arch/arm64/kvm/handle_exit.c:kvm_handle_guest_serror
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - drivers/irqchip/irq-gic.c:gic_cpu_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_check_local_cap_erratum
```
**Symbols:**

```
ffff80001009af18-ffff80001009af70: this_cpu_has_cap (STB_GLOBAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
