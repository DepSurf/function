# Function: <code>xen_pmu_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81026550)
Location: arch/x86/xen/pmu.c:512
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81fa53a6)
Location: drivers/xen/sys-hypervisor.c:483
Inline: True
```
**Symbols:**

```
ffffffff81026550-ffffffff810267a4: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810259f0)
Location: arch/x86/xen/pmu.c:512
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81fd1936)
Location: drivers/xen/sys-hypervisor.c:458
Inline: True
```
**Symbols:**

```
ffffffff810259f0-ffffffff81025c52: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81026110)
Location: arch/x86/xen/pmu.c:512
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81026110-ffffffff810263ad: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101ca70)
Location: arch/x86/xen/pmu.c:512
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8101ca70-ffffffff8101cd03: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d720)
Location: arch/x86/xen/pmu.c:513
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8101d720-ffffffff8101d9b3: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:513
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8101e46c-ffffffff8101e4b2: xen_pmu_init.cold.9 (STB_LOCAL)
ffffffff8101e0b0-ffffffff8101e308: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8101dcfc-ffffffff8101dd42: xen_pmu_init.cold.9 (STB_LOCAL)
ffffffff8101d930-ffffffff8101db92: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8101f8a0-ffffffff8101f8e6: xen_pmu_init.cold (STB_LOCAL)
ffffffff8101f4d0-ffffffff8101f734: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81020200-ffffffff81020246: xen_pmu_init.cold (STB_LOCAL)
ffffffff8101fe30-ffffffff81020094: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81022851-ffffffff81022897: xen_pmu_init.cold (STB_LOCAL)
ffffffff81022550-ffffffff810226e8: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81bd2b01-ffffffff81bd2b47: xen_pmu_init.cold (STB_LOCAL)
ffffffff81022c30-ffffffff81022dc8: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81bc4c9f-ffffffff81bc4ce3: xen_pmu_init.cold (STB_LOCAL)
ffffffff81024e80-ffffffff810250ea: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81c97424-ffffffff81c97493: xen_pmu_init.cold (STB_LOCAL)
ffffffff810292f0-ffffffff810295cd: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:511
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81e46857-ffffffff81e468ef: xen_pmu_init.cold (STB_LOCAL)
ffffffff8102dbe0-ffffffff8102df34: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:524
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff820519e6-ffffffff82051a3e: xen_pmu_init.cold (STB_LOCAL)
ffffffff81034fa0-ffffffff81035319: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:524
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff820cfed2-ffffffff820cff2a: xen_pmu_init.cold (STB_LOCAL)
ffffffff81034f20-ffffffff81035299: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:524
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff821aa83f-ffffffff821aa897: xen_pmu_init.cold (STB_LOCAL)
ffffffff8103b120-ffffffff8103b499: xen_pmu_init (STB_GLOBAL)
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
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81020360-ffffffff810203a6: xen_pmu_init.cold (STB_LOCAL)
ffffffff8101ff90-ffffffff810201f4: xen_pmu_init (STB_GLOBAL)
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
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff810201c0-ffffffff81020206: xen_pmu_init.cold (STB_LOCAL)
ffffffff8101fdf0-ffffffff81020054: xen_pmu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_pmu_init(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:520
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81020410-ffffffff81020456: xen_pmu_init.cold (STB_LOCAL)
ffffffff81020040-ffffffff810202a4: xen_pmu_init (STB_GLOBAL)
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
