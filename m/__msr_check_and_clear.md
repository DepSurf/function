# Function: <code>__msr_check_and_clear</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __msr_check_and_clear(long unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c0000000000202b0)
Location: arch/powerpc/kernel/process.c:141
Inline: False
Direct callers:
  - arch/powerpc/kernel/process.c:restore_math
  - arch/powerpc/kernel/process.c:giveup_all
  - arch/powerpc/kernel/process.c:flush_vsx_to_thread
  - arch/powerpc/kernel/process.c:giveup_altivec
  - arch/powerpc/kernel/process.c:giveup_fpu
  - arch/powerpc/lib/xor_vmx_glue.c:xor_altivec_5
  - arch/powerpc/lib/xor_vmx_glue.c:xor_altivec_4
  - arch/powerpc/lib/xor_vmx_glue.c:xor_altivec_3
  - arch/powerpc/lib/xor_vmx_glue.c:xor_altivec_2
  - arch/powerpc/lib/vmx-helper.c:exit_vmx_ops
  - arch/powerpc/lib/vmx-helper.c:exit_vmx_usercopy
```
**Symbols:**

```
c0000000000202b0-c0000000000202e0: __msr_check_and_clear (STB_GLOBAL)
```
</details>
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
