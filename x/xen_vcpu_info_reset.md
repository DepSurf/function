# Function: <code>xen_vcpu_info_reset</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81019995)
Location: arch/x86/xen/enlighten.c:174
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff810198e0-ffffffff8101992d: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101a275)
Location: arch/x86/xen/enlighten.c:178
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101a1c0-ffffffff8101a20d: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ac55)
Location: arch/x86/xen/enlighten.c:186
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101aba0-ffffffff8101abed: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b425)
Location: arch/x86/xen/enlighten.c:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101b370-ffffffff8101b3bd: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101cf45)
Location: arch/x86/xen/enlighten.c:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101ce90-ffffffff8101cedd: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d8c5)
Location: arch/x86/xen/enlighten.c:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101d810-ffffffff8101d85d: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101fc80)
Location: arch/x86/xen/enlighten.c:188
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101fc80-ffffffff8101fccd: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81020720)
Location: arch/x86/xen/enlighten.c:188
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff81020720-ffffffff8102076d: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81022ac0)
Location: arch/x86/xen/enlighten.c:188
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff81022ac0-ffffffff81022b0d: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81026960)
Location: arch/x86/xen/enlighten.c:192
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff81026960-ffffffff81026a5f: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8102ab20)
Location: arch/x86/xen/enlighten.c:146
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
**Symbols:**

```
ffffffff8102ab20-ffffffff8102ac32: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031750)
Location: arch/x86/xen/enlighten.c:146
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
**Symbols:**

```
ffffffff81031750-ffffffff81031862: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031750)
Location: arch/x86/xen/enlighten.c:146
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
**Symbols:**

```
ffffffff81031750-ffffffff81031862: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81037a40)
Location: arch/x86/xen/enlighten.c:149
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
**Symbols:**

```
ffffffff81037a40-ffffffff81037b52: xen_vcpu_info_reset (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d8c5)
Location: arch/x86/xen/enlighten.c:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101d810-ffffffff8101d85d: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d885)
Location: arch/x86/xen/enlighten.c:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101d7d0-ffffffff8101d81d: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_info_reset(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101dad5)
Location: arch/x86/xen/enlighten.c:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_setup
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/xen/smp.c:xen_smp_cpus_done
```
**Symbols:**

```
ffffffff8101da20-ffffffff8101da6d: xen_vcpu_info_reset (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
