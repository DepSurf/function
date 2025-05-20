# Function: <code>__sysvec_error_interrupt</code>

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
void __sysvec_error_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2168
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
```
**Symbols:**

```
ffffffff8106cf20-ffffffff8106d061: __sysvec_error_interrupt (STB_LOCAL)
ffffffff8106e1d9-ffffffff8106e239: __sysvec_error_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __sysvec_error_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2194
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
```
**Symbols:**

```
ffffffff8106e6c0-ffffffff8106e7e3: __sysvec_error_interrupt (STB_LOCAL)
ffffffff81bd6f33-ffffffff81bd6f93: __sysvec_error_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __sysvec_error_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2202
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
```
**Symbols:**

```
ffffffff8106f1b0-ffffffff8106f2d3: __sysvec_error_interrupt (STB_LOCAL)
ffffffff81bc90ed-ffffffff81bc914d: __sysvec_error_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __sysvec_error_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
```
**Symbols:**

```
ffffffff8107abb0-ffffffff8107ad0f: __sysvec_error_interrupt (STB_LOCAL)
ffffffff81c9db6f-ffffffff81c9dbad: __sysvec_error_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __sysvec_error_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2207
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
```
**Symbols:**

```
ffffffff81089c40-ffffffff81089ddb: __sysvec_error_interrupt (STB_LOCAL)
ffffffff81e4cff5-ffffffff81e4d033: __sysvec_error_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sysvec_error_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109db60)
Location: arch/x86/kernel/apic/apic.c:2241
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
```
**Symbols:**

```
ffffffff8109db60-ffffffff8109dd40: __sysvec_error_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sysvec_error_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a0b40)
Location: arch/x86/kernel/apic/apic.c:2244
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
```
**Symbols:**

```
ffffffff810a0b40-ffffffff810a0d19: __sysvec_error_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sysvec_error_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a7d80)
Location: arch/x86/kernel/apic/apic.c:2182
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
```
**Symbols:**

```
ffffffff810a7d80-ffffffff810a7f30: __sysvec_error_interrupt (STB_LOCAL)
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
