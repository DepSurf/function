# Function: <code>native_wbinvd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b940)
Location: arch/x86/include/asm/special_insns.h:101
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064590)
Location: arch/x86/include/asm/special_insns.h:101
Inline: False
```
**Symbols:**

```
ffffffff8101b940-ffffffff8101b948: native_wbinvd (STB_LOCAL)
ffffffff81064590-ffffffff81064598: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ad30)
Location: arch/x86/include/asm/special_insns.h:139
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff810641e0)
Location: arch/x86/include/asm/special_insns.h:139
Inline: False
```
**Symbols:**

```
ffffffff8101ad30-ffffffff8101ad38: native_wbinvd (STB_LOCAL)
ffffffff810641e0-ffffffff810641e8: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b460)
Location: arch/x86/include/asm/special_insns.h:131
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff810676d0)
Location: arch/x86/include/asm/special_insns.h:131
Inline: False
```
**Symbols:**

```
ffffffff8101b460-ffffffff8101b468: native_wbinvd (STB_LOCAL)
ffffffff810676d0-ffffffff810676d8: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101e550)
Location: arch/x86/include/asm/special_insns.h:131
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066990)
Location: arch/x86/include/asm/special_insns.h:131
Inline: False
```
**Symbols:**

```
ffffffff8101e550-ffffffff8101e558: native_wbinvd (STB_LOCAL)
ffffffff81066990-ffffffff81066998: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f280)
Location: arch/x86/include/asm/special_insns.h:132
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff81038547)
Location: arch/x86/include/asm/special_insns.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053fb9)
Location: arch/x86/include/asm/special_insns.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106ab50)
Location: arch/x86/include/asm/special_insns.h:132
Inline: False
```
**Symbols:**

```
ffffffff8101f280-ffffffff8101f288: native_wbinvd (STB_LOCAL)
ffffffff8106ab50-ffffffff8106ab58: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101fd40)
Location: arch/x86/include/asm/special_insns.h:132
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff81039a67)
Location: arch/x86/include/asm/special_insns.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056c19)
Location: arch/x86/include/asm/special_insns.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106d830)
Location: arch/x86/include/asm/special_insns.h:132
Inline: False
```
**Symbols:**

```
ffffffff8101fd40-ffffffff8101fd48: native_wbinvd (STB_LOCAL)
ffffffff8106d830-ffffffff8106d838: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f5c0)
Location: arch/x86/include/asm/special_insns.h:132
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff8103af97)
Location: arch/x86/include/asm/special_insns.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810542a9)
Location: arch/x86/include/asm/special_insns.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c936)
Location: arch/x86/include/asm/special_insns.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810739d0)
Location: arch/x86/include/asm/special_insns.h:132
Inline: False
```
**Symbols:**

```
ffffffff8101f5c0-ffffffff8101f5c8: native_wbinvd (STB_LOCAL)
ffffffff810739d0-ffffffff810739d8: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81021110)
Location: arch/x86/include/asm/special_insns.h:141
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff8103d5a9)
Location: arch/x86/include/asm/special_insns.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810574cb)
Location: arch/x86/include/asm/special_insns.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fca6)
Location: arch/x86/include/asm/special_insns.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077530)
Location: arch/x86/include/asm/special_insns.h:141
Inline: False
```
**Symbols:**

```
ffffffff81021110-ffffffff81021113: native_wbinvd (STB_LOCAL)
ffffffff81077530-ffffffff81077533: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81021a70)
Location: arch/x86/include/asm/special_insns.h:127
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff8103dd65)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057d9a)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060556)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810785a0)
Location: arch/x86/include/asm/special_insns.h:127
Inline: False
```
**Symbols:**

```
ffffffff81021a70-ffffffff81021a73: native_wbinvd (STB_LOCAL)
ffffffff810785a0-ffffffff810785a3: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810242a0)
Location: arch/x86/include/asm/special_insns.h:128
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff81040e23)
Location: arch/x86/include/asm/special_insns.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cf63)
Location: arch/x86/include/asm/special_insns.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066266)
Location: arch/x86/include/asm/special_insns.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f9c0)
Location: arch/x86/include/asm/special_insns.h:128
Inline: False
```
**Symbols:**

```
ffffffff810242a0-ffffffff810242a3: native_wbinvd (STB_LOCAL)
ffffffff8107f9c0-ffffffff8107f9c3: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81024a20)
Location: arch/x86/include/asm/special_insns.h:130
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff81040d83)
Location: arch/x86/include/asm/special_insns.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b7c3)
Location: arch/x86/include/asm/special_insns.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064516)
Location: arch/x86/include/asm/special_insns.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f5f0)
Location: arch/x86/include/asm/special_insns.h:130
Inline: False
```
**Symbols:**

```
ffffffff81024a20-ffffffff81024a23: native_wbinvd (STB_LOCAL)
ffffffff8107f5f0-ffffffff8107f5f3: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81026be0)
Location: arch/x86/include/asm/special_insns.h:130
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff81042783)
Location: arch/x86/include/asm/special_insns.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c173)
Location: arch/x86/include/asm/special_insns.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064ab6)
Location: arch/x86/include/asm/special_insns.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080700)
Location: arch/x86/include/asm/special_insns.h:130
Inline: False
```
**Symbols:**

```
ffffffff81026be0-ffffffff81026be3: native_wbinvd (STB_LOCAL)
ffffffff81080700-ffffffff81080703: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102b100)
Location: arch/x86/include/asm/special_insns.h:118
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff81048ad3)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8106590d)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106eb66)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f620)
Location: arch/x86/include/asm/special_insns.h:118
Inline: False
```
**Symbols:**

```
ffffffff8102b100-ffffffff8102b103: native_wbinvd (STB_LOCAL)
ffffffff8108f620-ffffffff8108f623: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102f980)
Location: arch/x86/include/asm/special_insns.h:118
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff81051da1)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810723ab)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c306)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0390)
Location: arch/x86/include/asm/special_insns.h:118
Inline: False
```
**Symbols:**

```
ffffffff8102f980-ffffffff8102f987: native_wbinvd (STB_LOCAL)
ffffffff810a0390-ffffffff810a0397: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81036d50)
Location: arch/x86/include/asm/special_insns.h:118
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff8105f470)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810821af)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108d5c6)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b7f10)
Location: arch/x86/include/asm/special_insns.h:118
Inline: False
```
**Symbols:**

```
ffffffff81036d50-ffffffff81036d57: native_wbinvd (STB_LOCAL)
ffffffff810b7f10-ffffffff810b7f17: native_wbinvd (STB_LOCAL)
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
In arch/x86/kernel/process.c (ffffffff81060b82)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81084649)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81090476)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff82140ee0)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_wbinvd
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
In arch/x86/kernel/process.c (ffffffff81067c32)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108bd67)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097806)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff82222e10)
Location: arch/x86/include/asm/special_insns.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_wbinvd
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
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81021bd0)
Location: arch/x86/include/asm/special_insns.h:127
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff8103dee5)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105791a)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810600d6)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810775a0)
Location: arch/x86/include/asm/special_insns.h:127
Inline: False
```
**Symbols:**

```
ffffffff81021bd0-ffffffff81021bd3: native_wbinvd (STB_LOCAL)
ffffffff810775a0-ffffffff810775a3: native_wbinvd (STB_LOCAL)
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
In arch/x86/kernel/process.c (ffffffff8102d6ff)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810458e1)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047afb)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81050406)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054d53)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828a33d9)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106bb21)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff8107072e)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8416)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff81545bd5)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff815b5155)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff815dbae8)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff815dc8fc)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff815dd12e)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815efc1d)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff8166a765)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81021a30)
Location: arch/x86/include/asm/special_insns.h:127
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff8103dd25)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057d4a)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060506)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077550)
Location: arch/x86/include/asm/special_insns.h:127
Inline: False
```
**Symbols:**

```
ffffffff81021a30-ffffffff81021a33: native_wbinvd (STB_LOCAL)
ffffffff81077550-ffffffff81077553: native_wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81021c80)
Location: arch/x86/include/asm/special_insns.h:127
Inline: False
```
```
In arch/x86/kernel/process.c (ffffffff8103ee85)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810591ea)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061a66)
Location: arch/x86/include/asm/special_insns.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810795f0)
Location: arch/x86/include/asm/special_insns.h:127
Inline: False
```
**Symbols:**

```
ffffffff81021c80-ffffffff81021c83: native_wbinvd (STB_LOCAL)
ffffffff810795f0-ffffffff810795f3: native_wbinvd (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
