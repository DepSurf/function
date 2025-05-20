# Function: <code>xen_setup_runstate_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81023910)
Location: arch/x86/xen/time.c:104
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff81023910-ffffffff81023967: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81518070)
Location: drivers/xen/time.c:91
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff81518070-ffffffff815180da: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81544580)
Location: drivers/xen/time.c:91
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff81544580-ffffffff815445ea: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81558410)
Location: drivers/xen/time.c:91
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff81558410-ffffffff8155847a: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff815bc7c0)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff815bc7c0-ffffffff815bc82a: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff815f4e20)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff815f4e20-ffffffff815f4e8a: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff8160fc80)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff8160fc80-ffffffff8160fcea: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81643ab0)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81643ab0-ffffffff81643b1a: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81666060)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81666060-ffffffff816660ca: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff817157a0)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff817157a0-ffffffff81715808: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81732170)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81732170-ffffffff817321d8: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81715c40)
Location: drivers/xen/time.c:161
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81715c40-ffffffff81715ca8: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81792e60)
Location: drivers/xen/time.c:161
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81792e60-ffffffff81792f0c: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff818cb7a0)
Location: drivers/xen/time.c:161
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff818cb7a0-ffffffff818cb866: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81a1cb30)
Location: drivers/xen/time.c:161
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81a1cb30-ffffffff81a1cbf6: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81a65d30)
Location: drivers/xen/time.c:161
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81a65d30-ffffffff81a65df6: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81ab8590)
Location: drivers/xen/time.c:161
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81ab8590-ffffffff81ab8656: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffff80001082fbc8)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/arm/xen/enlighten.c:xen_starting_cpu
```
**Symbols:**

```
ffff80001082fbc8-ffff80001082fc50: xen_setup_runstate_info (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff8162bd90)
Location: drivers/xen/time.c:186
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8162bd90-ffffffff8162bdfa: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81659ea0)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81659ea0-ffffffff81659f0a: xen_setup_runstate_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81674470)
Location: drivers/xen/time.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81674470-ffffffff816744da: xen_setup_runstate_info (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
