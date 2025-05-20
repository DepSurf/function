# Function: <code>print_sys_reg_instr</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void print_sys_reg_instr(const struct sys_reg_params *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kvm/sys_regs.c (ffff8000100d6c4c)
Location: arch/arm64/kvm/sys_regs.h:65
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:write_to_read_only
  - arch/arm64/kvm/sys_regs.c:read_from_write_only
Direct callers:
  - arch/arm64/kvm/sys_regs.c:kvm_handle_sys_reg
  - arch/arm64/kvm/sys_regs.c:unhandled_cp_access
  - arch/arm64/kvm/sys_regs.c:write_to_read_only
  - arch/arm64/kvm/sys_regs.c:read_from_write_only
```
**Symbols:**

```
ffff8000100da2b0-ffff8000100da308: print_sys_reg_instr.part.0 (STB_LOCAL)
ffff8000100d5cd0-ffff8000100d5d10: print_sys_reg_instr (STB_LOCAL)
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
