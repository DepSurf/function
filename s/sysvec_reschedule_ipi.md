# Function: <code>sysvec_reschedule_ipi</code>

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
void sysvec_reschedule_ipi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81bbef80)
Location: arch/x86/kernel/smp.c:225
Inline: False
```
**Symbols:**

```
ffffffff81bbef80-ffffffff81bbf089: sysvec_reschedule_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysvec_reschedule_ipi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c37780)
Location: arch/x86/kernel/smp.c:225
Inline: False
```
**Symbols:**

```
ffffffff81c37780-ffffffff81c37862: sysvec_reschedule_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysvec_reschedule_ipi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c29e50)
Location: arch/x86/kernel/smp.c:225
Inline: False
```
**Symbols:**

```
ffffffff81c29e50-ffffffff81c29f32: sysvec_reschedule_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysvec_reschedule_ipi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81d483c0)
Location: arch/x86/kernel/smp.c:225
Inline: False
```
**Symbols:**

```
ffffffff81d483c0-ffffffff81d4849c: sysvec_reschedule_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysvec_reschedule_ipi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81f17310)
Location: arch/x86/kernel/smp.c:225
Inline: False
```
**Symbols:**

```
ffffffff81f17310-ffffffff81f1742c: sysvec_reschedule_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysvec_reschedule_ipi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff820be990)
Location: arch/x86/kernel/smp.c:225
Inline: False
```
**Symbols:**

```
ffffffff820be990-ffffffff820beaac: sysvec_reschedule_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysvec_reschedule_ipi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff821404f0)
Location: arch/x86/kernel/smp.c:269
Inline: False
```
**Symbols:**

```
ffffffff821404f0-ffffffff8214060c: sysvec_reschedule_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysvec_reschedule_ipi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff82222510)
Location: arch/x86/kernel/smp.c:244
Inline: False
```
**Symbols:**

```
ffffffff82222510-ffffffff8222261b: sysvec_reschedule_ipi (STB_GLOBAL)
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
