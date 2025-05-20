# Function: <code>vcpu_write_sys_reg</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void vcpu_write_sys_reg(struct kvm_vcpu *vcpu, u64 val, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kvm/sys_regs.c (ffff8000100d51fc)
Location: arch/arm64/kvm/sys_regs.c:112
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:reset_mpidr
  - arch/arm64/kvm/sys_regs.c:reset_amair_el1
Direct callers:
  - arch/arm64/kvm/inject_fault.c:kvm_inject_undefined
  - arch/arm64/kvm/inject_fault.c:inject_abt64
  - arch/arm64/kvm/inject_fault.c:inject_abt64
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/sys_regs.c:trap_debug_regs
  - arch/arm64/kvm/sys_regs.c:access_vm_reg
```
**Symbols:**

```
ffff8000100d8fc0-ffff8000100d90e4: vcpu_write_sys_reg (STB_GLOBAL)
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
