# Function: <code>_exception</code>

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
void _exception(int signr, struct pt_regs *regs, int code, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/traps.c (c00000000002da70)
Location: arch/powerpc/kernel/traps.c:368
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:altivec_assist_exception
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:vsx_unavailable_exception
  - arch/powerpc/kernel/traps.c:altivec_unavailable_exception
  - arch/powerpc/kernel/traps.c:alignment_exception
  - arch/powerpc/kernel/traps.c:program_check_exception
  - arch/powerpc/kernel/traps.c:program_check_exception
  - arch/powerpc/kernel/traps.c:program_check_exception
  - arch/powerpc/kernel/traps.c:RunModeException
  - arch/powerpc/kernel/traps.c:instruction_breakpoint_exception
  - arch/powerpc/kernel/traps.c:unknown_exception
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:bad_access
  - arch/powerpc/mm/fault.c:bad_area
  - arch/powerpc/mm/fault.c:bad_area_nosemaphore
  - arch/powerpc/mm/book3s64/hash_utils.c:low_hash_fault
  - arch/powerpc/mm/book3s64/hash_utils.c:low_hash_fault
  - arch/powerpc/mm/book3s64/slb.c:do_bad_slb_fault
  - arch/powerpc/platforms/powernv/opal.c:opal_machine_check
  - arch/powerpc/platforms/pseries/ras.c:pSeries_machine_check_exception
```
**Symbols:**

```
c00000000002da70-c00000000002db78: _exception (STB_GLOBAL)
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
