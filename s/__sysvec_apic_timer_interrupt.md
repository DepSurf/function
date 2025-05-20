# Function: <code>__sysvec_apic_timer_interrupt</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __sysvec_apic_timer_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1091
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
**Symbols:**

```
ffffffff8106cc30-ffffffff8106cd29: __sysvec_apic_timer_interrupt (STB_LOCAL)
ffffffff8106e15a-ffffffff8106e182: __sysvec_apic_timer_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __sysvec_apic_timer_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
**Symbols:**

```
ffffffff8106e3f0-ffffffff8106e4c4: __sysvec_apic_timer_interrupt (STB_LOCAL)
ffffffff81bd6eb3-ffffffff81bd6edc: __sysvec_apic_timer_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __sysvec_apic_timer_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
**Symbols:**

```
ffffffff8106eea0-ffffffff8106ef74: __sysvec_apic_timer_interrupt (STB_LOCAL)
ffffffff81bc906d-ffffffff81bc9096: __sysvec_apic_timer_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __sysvec_apic_timer_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1097
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
**Symbols:**

```
ffffffff8107a8a0-ffffffff8107a96e: __sysvec_apic_timer_interrupt (STB_LOCAL)
ffffffff81c9dac7-ffffffff81c9daf0: __sysvec_apic_timer_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __sysvec_apic_timer_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1106
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
**Symbols:**

```
ffffffff81089870-ffffffff8108997e: __sysvec_apic_timer_interrupt (STB_LOCAL)
ffffffff81e4cf50-ffffffff81e4cf77: __sysvec_apic_timer_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sysvec_apic_timer_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109d560)
Location: arch/x86/kernel/apic/apic.c:1107
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
**Symbols:**

```
ffffffff8109d560-ffffffff8109d695: __sysvec_apic_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sysvec_apic_timer_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a0540)
Location: arch/x86/kernel/apic/apic.c:1109
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
**Symbols:**

```
ffffffff810a0540-ffffffff810a0675: __sysvec_apic_timer_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sysvec_apic_timer_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a8090)
Location: arch/x86/kernel/apic/apic.c:1076
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
**Symbols:**

```
ffffffff810a8090-ffffffff810a81d6: __sysvec_apic_timer_interrupt (STB_LOCAL)
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
