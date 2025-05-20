# Function: <code>show_fault_oops</code>

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
In arch/x86/mm/fault.c (ffffffff8106acc8)
Location: arch/x86/mm/fault.c:594
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff8106aa29)
Location: arch/x86/mm/fault.c:651
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff8106e64d)
Location: arch/x86/mm/fault.c:651
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff8106dd9a)
Location: arch/x86/mm/fault.c:692
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff81072daa)
Location: arch/x86/mm/fault.c:671
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff81075849)
Location: arch/x86/mm/fault.c:643
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff8107b653)
Location: arch/x86/mm/fault.c:620
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff8107f176)
Location: arch/x86/mm/fault.c:586
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff81080206)
Location: arch/x86/mm/fault.c:608
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void show_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:572
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81087130-ffffffff810872aa: show_fault_oops (STB_LOCAL)
ffffffff81088227-ffffffff810883ff: show_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void show_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:515
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810877b0-ffffffff8108792a: show_fault_oops (STB_LOCAL)
ffffffff81bd9407-ffffffff81bd95df: show_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void show_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:506
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81088370-ffffffff81088506: show_fault_oops (STB_LOCAL)
ffffffff81bcb394-ffffffff81bcb56c: show_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void show_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:507
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81097700-ffffffff810978a6: show_fault_oops (STB_LOCAL)
ffffffff81ca0a4f-ffffffff81ca0c3e: show_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void show_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:507
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff810aa210-ffffffff810aa3d4: show_fault_oops (STB_LOCAL)
ffffffff81e4ffb6-ffffffff81e501cc: show_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void show_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:528
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff810c3ae0-ffffffff810c3e94: show_fault_oops (STB_LOCAL)
ffffffff820549ed-ffffffff82054a09: show_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void show_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:508
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff810c7320-ffffffff810c76d4: show_fault_oops (STB_LOCAL)
ffffffff820d2ffb-ffffffff820d3017: show_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void show_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:508
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff810cf7f0-ffffffff810cfba4: show_fault_oops (STB_LOCAL)
ffffffff821ade69-ffffffff821ade85: show_fault_oops.cold (STB_LOCAL)
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
In arch/x86/mm/fault.c (ffffffff8107f206)
Location: arch/x86/mm/fault.c:608
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff8106e1e9)
Location: arch/x86/mm/fault.c:608
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff8107f1b6)
Location: arch/x86/mm/fault.c:608
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff810812a6)
Location: arch/x86/mm/fault.c:608
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
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
