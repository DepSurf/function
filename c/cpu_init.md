# Function: <code>cpu_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041070)
Location: arch/x86/kernel/cpu/common.c:1329
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81041070-ffffffff8104142b: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040f90)
Location: arch/x86/kernel/cpu/common.c:1448
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81040f90-ffffffff81041353: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810409e0)
Location: arch/x86/kernel/cpu/common.c:1419
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810409e0-ffffffff81040daa: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103e960)
Location: arch/x86/kernel/cpu/common.c:1473
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8103e960-ffffffff8103ed47: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041630)
Location: arch/x86/kernel/cpu/common.c:1568
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81041630-ffffffff81041a30: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81042f00)
Location: arch/x86/kernel/cpu/common.c:1678
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81042f00-ffffffff810432f4: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810444e0)
Location: arch/x86/kernel/cpu/common.c:1697
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810444e0-ffffffff8104497c: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1781
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81047163-ffffffff81047176: cpu_init.cold (STB_LOCAL)
ffffffff81046ab0-ffffffff81046ef2: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047230)
Location: arch/x86/kernel/cpu/common.c:1813
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81047230-ffffffff81047689: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104b040)
Location: arch/x86/kernel/cpu/common.c:1846
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8104b040-ffffffff8104b3ed: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a710)
Location: arch/x86/kernel/cpu/common.c:1941
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8104a710-ffffffff8104aac0: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104bfb0)
Location: arch/x86/kernel/cpu/common.c:1945
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8104bfb0-ffffffff8104c39d: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810533c0)
Location: arch/x86/kernel/cpu/common.c:1985
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/cpu/common.c:cpu_init_secondary
```
**Symbols:**

```
ffffffff810533c0-ffffffff8105363a: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105ee60)
Location: arch/x86/kernel/cpu/common.c:2231
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/cpu/common.c:cpu_init_secondary
```
**Symbols:**

```
ffffffff8105ee60-ffffffff8105f0d6: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d5d0)
Location: arch/x86/kernel/cpu/common.c:2233
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/cpu/common.c:cpu_init_secondary
```
**Symbols:**

```
ffffffff8106d5d0-ffffffff8106d836: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106ef60)
Location: arch/x86/kernel/cpu/common.c:2223
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8106ef60-ffffffff8106f17f: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810762c0)
Location: arch/x86/kernel/cpu/common.c:2270
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810762c0-ffffffff8107653c: cpu_init (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c030d8e0)
Location: arch/arm/kernel/setup.c:522
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/smp.c:secondary_start_kernel
```
**Symbols:**

```
c030d8e0-c030d98c: cpu_init (STB_GLOBAL)
```
</details>
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
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810473b0)
Location: arch/x86/kernel/cpu/common.c:1813
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810473b0-ffffffff810477f9: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81036530)
Location: arch/x86/kernel/cpu/common.c:1813
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81036530-ffffffff81036b33: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810471f0)
Location: arch/x86/kernel/cpu/common.c:1813
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810471f0-ffffffff81047639: cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810485f0)
Location: arch/x86/kernel/cpu/common.c:1813
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810485f0-ffffffff81048a49: cpu_init (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
