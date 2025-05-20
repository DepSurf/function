# Function: <code>common_cpu_die</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810526e0)
Location: arch/x86/kernel/smpboot.c:1509
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff810526e0-ffffffff8105272d: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810527f0)
Location: arch/x86/kernel/smpboot.c:1536
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff810527f0-ffffffff8105283d: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81055100)
Location: arch/x86/kernel/smpboot.c:1564
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff81055100-ffffffff8105514d: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054a20)
Location: arch/x86/kernel/smpboot.c:1570
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff81054a20-ffffffff81054a6d: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810587e0)
Location: arch/x86/kernel/smpboot.c:1483
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff810587e0-ffffffff8105882d: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1539
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff8105b8b6-ffffffff8105b8e1: common_cpu_die.cold.11 (STB_LOCAL)
ffffffff8105b470-ffffffff8105b4a0: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1540
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff81061540-ffffffff8106156b: common_cpu_die.cold.13 (STB_LOCAL)
ffffffff810610f0-ffffffff81061120: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1605
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff81064c08-ffffffff81064c35: common_cpu_die.cold (STB_LOCAL)
ffffffff81064790-ffffffff810647c3: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1605
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff81065275-ffffffff810652a2: common_cpu_die.cold (STB_LOCAL)
ffffffff81064e10-ffffffff81064e43: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b555)
Location: arch/x86/kernel/smpboot.c:1632
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8106bb66-ffffffff8106bb93: common_cpu_die.cold (STB_LOCAL)
ffffffff8106b510-ffffffff8106b545: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106d1d3)
Location: arch/x86/kernel/smpboot.c:1626
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81bd6ad3-ffffffff81bd6b00: common_cpu_die.cold (STB_LOCAL)
ffffffff8106d180-ffffffff8106d1b5: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106dc73)
Location: arch/x86/kernel/smpboot.c:1627
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81bc8cad-ffffffff81bc8cda: common_cpu_die.cold (STB_LOCAL)
ffffffff8106dc20-ffffffff8106dc55: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81079483)
Location: arch/x86/kernel/smpboot.c:1634
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81c9d653-ffffffff81c9d680: common_cpu_die.cold (STB_LOCAL)
ffffffff81079430-ffffffff81079465: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81088301)
Location: arch/x86/kernel/smpboot.c:1699
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81e4caee-ffffffff81e4cb17: common_cpu_die.cold (STB_LOCAL)
ffffffff810882b0-ffffffff810882eb: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109bd61)
Location: arch/x86/kernel/smpboot.c:1699
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8109bce0-ffffffff8109bd38: common_cpu_die (STB_GLOBAL)
```
</details>
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
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1605
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff81064d65-ffffffff81064d92: common_cpu_die.cold (STB_LOCAL)
ffffffff81064900-ffffffff81064933: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1605
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff8105503a-ffffffff81055067: common_cpu_die.cold (STB_LOCAL)
ffffffff81054bf0-ffffffff81054c23: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1605
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff81065215-ffffffff81065242: common_cpu_die.cold (STB_LOCAL)
ffffffff81064db0-ffffffff81064de3: common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1605
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/smpboot.c:native_cpu_die
```
**Symbols:**

```
ffffffff810667f5-ffffffff81066822: common_cpu_die.cold (STB_LOCAL)
ffffffff81066390-ffffffff810663c3: common_cpu_die (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
