# Function: <code>notify_package_thresholds</code>

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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104966a)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:332
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810497ea)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bbea)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:304
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b3a2)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104ed9b)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051afa)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f19a)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052263)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052b53)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void notify_package_thresholds(__u64 msr_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810575c0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:521
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff810575c0-ffffffff81057743: notify_package_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void notify_package_thresholds(__u64 msr_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056370)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:521
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81056370-ffffffff810564f3: notify_package_thresholds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81947191)
Location: drivers/thermal/intel/therm_throt.c:521
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebe2f)
Location: drivers/thermal/intel/therm_throt.c:521
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81b51f16)
Location: drivers/thermal/intel/therm_throt.c:533
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea0a6)
Location: drivers/thermal/intel/therm_throt.c:537
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52be6)
Location: drivers/thermal/intel/therm_throt.c:593
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09946)
Location: drivers/thermal/intel/therm_throt.c:593
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052c53)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104265f)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052b03)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81053f83)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
