# Function: <code>__spurious_interrupt</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106e0ed)
Location: arch/x86/kernel/apic/apic.c:2125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81bd6e55)
Location: arch/x86/kernel/apic/apic.c:2151
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __spurious_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106ee60)
Location: arch/x86/kernel/apic/apic.c:2189
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
**Symbols:**

```
ffffffff8106ee60-ffffffff8106ee74: __spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __spurious_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107a860)
Location: arch/x86/kernel/apic/apic.c:2186
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
**Symbols:**

```
ffffffff8107a860-ffffffff8107a874: __spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __spurious_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81089830)
Location: arch/x86/kernel/apic/apic.c:2194
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
**Symbols:**

```
ffffffff81089830-ffffffff8108984c: __spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __spurious_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109d820)
Location: arch/x86/kernel/apic/apic.c:2228
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
**Symbols:**

```
ffffffff8109d820-ffffffff8109d83c: __spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __spurious_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a0800)
Location: arch/x86/kernel/apic/apic.c:2231
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
**Symbols:**

```
ffffffff810a0800-ffffffff810a081c: __spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __spurious_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a7d20)
Location: arch/x86/kernel/apic/apic.c:2169
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
**Symbols:**

```
ffffffff810a7d20-ffffffff810a7d3c: __spurious_interrupt (STB_LOCAL)
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
