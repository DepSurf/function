# Function: <code>__sysvec_thermal</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sysvec_thermal(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057750)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:617
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
```
**Symbols:**

```
ffffffff81057750-ffffffff81057812: __sysvec_thermal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sysvec_thermal(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056500)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:617
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
```
**Symbols:**

```
ffffffff81056500-ffffffff8105659c: __sysvec_thermal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __sysvec_thermal(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:389
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
```
**Symbols:**

```
ffffffff81038590-ffffffff81038632: __sysvec_thermal (STB_LOCAL)
ffffffff81bc57d7-ffffffff81bc57ef: __sysvec_thermal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __sysvec_thermal(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
```
**Symbols:**

```
ffffffff8103d930-ffffffff8103d9cc: __sysvec_thermal (STB_LOCAL)
ffffffff81c984b4-ffffffff81c984cc: __sysvec_thermal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __sysvec_thermal(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
```
**Symbols:**

```
ffffffff810454b0-ffffffff8104558e: __sysvec_thermal (STB_LOCAL)
ffffffff81e479b9-ffffffff81e479d1: __sysvec_thermal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sysvec_thermal(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104f500)
Location: arch/x86/kernel/irq.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
```
**Symbols:**

```
ffffffff8104f500-ffffffff8104f5ef: __sysvec_thermal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sysvec_thermal(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810501b0)
Location: arch/x86/kernel/irq.c:398
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
```
**Symbols:**

```
ffffffff810501b0-ffffffff8105029f: __sysvec_thermal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sysvec_thermal(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810573f0)
Location: arch/x86/kernel/irq.c:398
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
```
**Symbols:**

```
ffffffff810573f0-ffffffff810574ce: __sysvec_thermal (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
