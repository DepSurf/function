# Function: <code>vcpu_mode_priv</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/arm.c (ffff8000100c6848)
Location: arch/arm64/include/asm/kvm_emulate.h:239
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_in_kernel
```
```
In virt/kvm/arm/perf.c (ffff8000100cf0e0)
Location: arch/arm64/include/asm/kvm_emulate.h:239
Inline: True
Inline callers:
  - virt/kvm/arm/perf.c:kvm_is_user_mode
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d1498)
Location: arch/arm64/include/asm/kvm_emulate.h:239
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:kvm_handle_wfx
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d57e0)
Location: arch/arm64/include/asm/kvm_emulate.h:239
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:access_pminten
  - arch/arm64/kvm/sys_regs.c:check_pmu_access_disabled
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
