# Function: <code>do_boot_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051b58)
Location: arch/x86/kernel/smpboot.c:944
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051cf0)
Location: arch/x86/kernel/smpboot.c:956
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810545d7)
Location: arch/x86/kernel/smpboot.c:971
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053f2a)
Location: arch/x86/kernel/smpboot.c:974
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81057cdd)
Location: arch/x86/kernel/smpboot.c:910
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105aa22)
Location: arch/x86/kernel/smpboot.c:963
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810606a2)
Location: arch/x86/kernel/smpboot.c:964
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1023
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81063e30-ffffffff81064208: do_boot_cpu (STB_LOCAL)
ffffffff81064b58-ffffffff81064bcb: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1023
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810644e0-ffffffff8106488e: do_boot_cpu (STB_LOCAL)
ffffffff810651d8-ffffffff81065238: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106af40)
Location: arch/x86/kernel/smpboot.c:1036
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8106af40-ffffffff8106b1f0: do_boot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106cbb0)
Location: arch/x86/kernel/smpboot.c:1030
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8106cbb0-ffffffff8106ce5b: do_boot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106d650)
Location: arch/x86/kernel/smpboot.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8106d650-ffffffff8106d8ec: do_boot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1033
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81078da0-ffffffff8107907c: do_boot_cpu (STB_LOCAL)
ffffffff81c9d601-ffffffff81c9d616: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1076
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81087b80-ffffffff81087eb5: do_boot_cpu (STB_LOCAL)
ffffffff81e4ca9e-ffffffff81e4cab3: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8109b510-ffffffff8109b845: do_boot_cpu (STB_LOCAL)
ffffffff82053baf-ffffffff82053bc4: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109c400)
Location: arch/x86/kernel/smpboot.c:1030
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_kick_ap
```
**Symbols:**

```
ffffffff8109c400-ffffffff8109c60d: do_boot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_boot_cpu(u32 apicid, int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a39a0)
Location: arch/x86/kernel/smpboot.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_kick_ap
```
**Symbols:**

```
ffffffff810a39a0-ffffffff810a3b97: do_boot_cpu (STB_LOCAL)
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
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1023
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81063fd0-ffffffff8106437e: do_boot_cpu (STB_LOCAL)
ffffffff81064cc8-ffffffff81064d28: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1023
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810542d0-ffffffff8105467e: do_boot_cpu (STB_LOCAL)
ffffffff81054f9d-ffffffff81054ffd: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1023
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81064480-ffffffff8106482e: do_boot_cpu (STB_LOCAL)
ffffffff81065178-ffffffff810651d8: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct *idle, int *cpu0_nmi_registered);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1023
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81065a40-ffffffff81065e05: do_boot_cpu (STB_LOCAL)
ffffffff81066758-ffffffff810667b8: do_boot_cpu.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *cpu0_nmi_registered</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int apicid</code> ➡️ <code>u32 apicid</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
