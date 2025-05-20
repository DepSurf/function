# Function: <code>therm_throt_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810493d0)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff810493d0-ffffffff81049518: therm_throt_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049580)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81049580-ffffffff810496c7: therm_throt_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b980)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff8104b980-ffffffff8104bac7: therm_throt_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b180)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff8104b180-ffffffff8104b28f: therm_throt_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104eb70)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff8104eb70-ffffffff8104ec7f: therm_throt_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff810518c0-ffffffff810519b5: therm_throt_process (STB_LOCAL)
ffffffff81051f5f-ffffffff81051f87: therm_throt_process.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:148
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff8104ef60-ffffffff8104f055: therm_throt_process (STB_LOCAL)
ffffffff8104f5c1-ffffffff8104f5e9: therm_throt_process.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81052030-ffffffff81052113: therm_throt_process (STB_LOCAL)
ffffffff81052702-ffffffff81052752: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81052920-ffffffff81052a03: therm_throt_process (STB_LOCAL)
ffffffff81052ff2-ffffffff81053042: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057bfb)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff810579e0-ffffffff81057b25: therm_throt_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8105697b)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81056760-ffffffff810568a5: therm_throt_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81947236)
Location: drivers/thermal/intel/therm_throt.c:312
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81946f90-ffffffff819470d5: therm_throt_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebf06)
Location: drivers/thermal/intel/therm_throt.c:312
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff819ebbd0-ffffffff819ebd46: therm_throt_process (STB_LOCAL)
ffffffff81d271a7-ffffffff81d271c2: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81b520e9)
Location: drivers/thermal/intel/therm_throt.c:313
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81b51c20-ffffffff81b51e0a: therm_throt_process (STB_LOCAL)
ffffffff81ef2fe0-ffffffff81ef306c: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea281)
Location: drivers/thermal/intel/therm_throt.c:317
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81ce9d90-ffffffff81ce9f7a: therm_throt_process (STB_LOCAL)
ffffffff820a7bb0-ffffffff820a7c3c: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52dc1)
Location: drivers/thermal/intel/therm_throt.c:373
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81d528d0-ffffffff81d52aba: therm_throt_process (STB_LOCAL)
ffffffff82128f8e-ffffffff8212901a: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09b21)
Location: drivers/thermal/intel/therm_throt.c:373
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81e09630-ffffffff81e0981a: therm_throt_process (STB_LOCAL)
ffffffff8220a977-ffffffff8220aa03: therm_throt_process.cold (STB_LOCAL)
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
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81052a20-ffffffff81052b03: therm_throt_process (STB_LOCAL)
ffffffff810530f2-ffffffff81053142: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81042410-ffffffff810424f3: therm_throt_process (STB_LOCAL)
ffffffff81042c3f-ffffffff81042c8f: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff810528d0-ffffffff810529b3: therm_throt_process (STB_LOCAL)
ffffffff81052fa2-ffffffff81052ff2: therm_throt_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void therm_throt_process(bool new_event, int event, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81053d50-ffffffff81053e33: therm_throt_process (STB_LOCAL)
ffffffff81054422-ffffffff81054472: therm_throt_process.cold (STB_LOCAL)
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
<code>int</code> ➡️ <code>void</code>
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
