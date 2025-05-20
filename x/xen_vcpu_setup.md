# Function: <code>xen_vcpu_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_vcpu_setup(int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c110)
Location: arch/x86/xen/enlighten.c:182
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_cpu_notify
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
```
**Symbols:**

```
ffffffff8101c110-ffffffff8101c23b: xen_vcpu_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c610)
Location: arch/x86/xen/enlighten.c:185
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_cpu_notify
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
**Symbols:**

```
ffffffff8101c610-ffffffff8101c763: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101cce0)
Location: arch/x86/xen/enlighten.c:187
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_prepare
  - arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
**Symbols:**

```
ffffffff8101cce0-ffffffff8101ce33: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81019930)
Location: arch/x86/xen/enlighten.c:185
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
```
**Symbols:**

```
ffffffff81019930-ffffffff81019acb: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101a210)
Location: arch/x86/xen/enlighten.c:189
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
```
**Symbols:**

```
ffffffff8101a210-ffffffff8101a3ab: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:197
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8101b075-ffffffff8101b092: xen_vcpu_setup.cold.2 (STB_LOCAL)
ffffffff8101abf0-ffffffff8101ad74: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8101b859-ffffffff8101b876: xen_vcpu_setup.cold.2 (STB_LOCAL)
ffffffff8101b3c0-ffffffff8101b544: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8101d38e-ffffffff8101d3ab: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff8101cee0-ffffffff8101d064: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8101dd2e-ffffffff8101dd4b: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff8101d860-ffffffff8101d9e4: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8102011e-ffffffff8102013b: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff8101fcd0-ffffffff8101fe23: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81bd268b-ffffffff81bd26a8: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff81020770-ffffffff810208c3: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81bc4900-ffffffff81bc491b: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff81022b10-ffffffff81022c65: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:203
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81c96ebe-ffffffff81c96ef1: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff81026a60-ffffffff81026c9b: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:157
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81e46317-ffffffff81e46326: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff8102ac40-ffffffff8102ae09: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031880)
Location: arch/x86/xen/enlighten.c:157
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81031880-ffffffff81031a58: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031880)
Location: arch/x86/xen/enlighten.c:157
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81031880-ffffffff81031a58: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81037b70)
Location: arch/x86/xen/enlighten.c:160
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81037b70-ffffffff81037d48: xen_vcpu_setup (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8101dd2e-ffffffff8101dd4b: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff8101d860-ffffffff8101d9e4: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8101dcee-ffffffff8101dd0b: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff8101d820-ffffffff8101d9a4: xen_vcpu_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xen_vcpu_setup(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:199
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8101df3e-ffffffff8101df5b: xen_vcpu_setup.cold (STB_LOCAL)
ffffffff8101da70-ffffffff8101dbf4: xen_vcpu_setup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
