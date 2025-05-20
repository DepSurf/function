# Function: <code>__sysvec_reboot</code>

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
void __sysvec_reboot(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81069250)
Location: arch/x86/kernel/smp.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:sysvec_reboot
```
**Symbols:**

```
ffffffff81069250-ffffffff8106930a: __sysvec_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sysvec_reboot(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff8106ae70)
Location: arch/x86/kernel/smp.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:sysvec_reboot
```
**Symbols:**

```
ffffffff8106ae70-ffffffff8106af2a: __sysvec_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sysvec_reboot(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff8106bc60)
Location: arch/x86/kernel/smp.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:sysvec_reboot
```
**Symbols:**

```
ffffffff8106bc60-ffffffff8106bd1a: __sysvec_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sysvec_reboot(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81076740)
Location: arch/x86/kernel/smp.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:sysvec_reboot
```
**Symbols:**

```
ffffffff81076740-ffffffff810767fa: __sysvec_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sysvec_reboot(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81085320)
Location: arch/x86/kernel/smp.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:sysvec_reboot
```
**Symbols:**

```
ffffffff81085320-ffffffff8108539e: __sysvec_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sysvec_reboot(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81098520)
Location: arch/x86/kernel/smp.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:sysvec_reboot
```
**Symbols:**

```
ffffffff81098520-ffffffff8109854b: __sysvec_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sysvec_reboot(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff8109b5e0)
Location: arch/x86/kernel/smp.c:136
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:sysvec_reboot
```
**Symbols:**

```
ffffffff8109b5e0-ffffffff8109b60b: __sysvec_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sysvec_reboot(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810a2bb0)
Location: arch/x86/kernel/smp.c:136
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:sysvec_reboot
```
**Symbols:**

```
ffffffff810a2bb0-ffffffff810a2bca: __sysvec_reboot (STB_LOCAL)
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
