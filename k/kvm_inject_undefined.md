# Function: <code>kvm_inject_undefined</code>

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
void kvm_inject_undefined(struct kvm_vcpu *vcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kvm/inject_fault.c (ffff8000100cf3c8)
Location: arch/arm64/kvm/inject_fault.c:208
Inline: False
Direct callers:
  - arch/arm64/kvm/handle_exit.c:kvm_handle_unknown_ec
  - arch/arm64/kvm/sys_regs.c:kvm_handle_sys_reg
  - arch/arm64/kvm/sys_regs.c:unhandled_cp_access
  - arch/arm64/kvm/sys_regs.c:perform_access
  - arch/arm64/kvm/sys_regs.c:kvm_handle_cp14_load_store
  - arch/arm64/kvm/sys_regs.c:access_pminten
  - arch/arm64/kvm/sys_regs.c:check_pmu_access_disabled
  - arch/arm64/kvm/sys_regs.c:trap_loregion
  - arch/arm64/kvm/sys_regs.c:write_to_read_only
  - arch/arm64/kvm/sys_regs.c:read_from_write_only
```
**Symbols:**

```
ffff8000100cf3c8-ffff8000100cf4ac: kvm_inject_undefined (STB_GLOBAL)
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
