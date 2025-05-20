# Function: <code>disable_local_APIC</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81053bb0)
Location: arch/x86/kernel/apic/apic.c:1039
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81053bb0-ffffffff81053bfd: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81053ce0)
Location: arch/x86/kernel/apic/apic.c:1071
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81053ce0-ffffffff81053d2e: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810569e0)
Location: arch/x86/kernel/apic/apic.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810569e0-ffffffff81056a2e: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810564d0)
Location: arch/x86/kernel/apic/apic.c:1157
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810562f0-ffffffff81056329: disable_local_APIC.part.12 (STB_LOCAL)
ffffffff81056510-ffffffff81056536: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105a1ed)
Location: arch/x86/kernel/apic/apic.c:1144
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81059fe0-ffffffff8105a01f: disable_local_APIC.part.8 (STB_LOCAL)
ffffffff8105a220-ffffffff8105a246: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105d270)
Location: arch/x86/kernel/apic/apic.c:1148
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8105d270-ffffffff8105d2c4: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81062f00)
Location: arch/x86/kernel/apic/apic.c:1154
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81062f00-ffffffff81062f54: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810665a0)
Location: arch/x86/kernel/apic/apic.c:1229
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810665a0-ffffffff810665f4: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066e8b)
Location: arch/x86/kernel/apic/apic.c:1261
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81066e20-ffffffff81066e45: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106da9b)
Location: arch/x86/kernel/apic/apic.c:1213
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8106da30-ffffffff8106da55: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106f21b)
Location: arch/x86/kernel/apic/apic.c:1222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8106f1b0-ffffffff8106f1d5: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106fd4b)
Location: arch/x86/kernel/apic/apic.c:1222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8106fce0-ffffffff8106fd05: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107b77b)
Location: arch/x86/kernel/apic/apic.c:1219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8107b710-ffffffff8107b735: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8108a8f9)
Location: arch/x86/kernel/apic/apic.c:1228
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8108a880-ffffffff8108a8b1: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109e939)
Location: arch/x86/kernel/apic/apic.c:1224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8109e8b0-ffffffff8109e8e1: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a1919)
Location: arch/x86/kernel/apic/apic.c:1226
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810a1890-ffffffff810a18c1: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a8760)
Location: arch/x86/kernel/apic/apic.c:1192
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810a8760-ffffffff810a87b2: disable_local_APIC (STB_GLOBAL)
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
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106697b)
Location: arch/x86/kernel/apic/apic.c:1261
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81066910-ffffffff81066935: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056d5d)
Location: arch/x86/kernel/apic/apic.c:1261
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81056d00-ffffffff81056d25: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066e2b)
Location: arch/x86/kernel/apic/apic.c:1261
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81066dc0-ffffffff81066de5: disable_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void disable_local_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106840b)
Location: arch/x86/kernel/apic/apic.c:1261
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810683a0-ffffffff810683c5: disable_local_APIC (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
