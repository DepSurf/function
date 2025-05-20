# Function: <code>mpx_fault_info</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mpx_fault_info(struct mpx_fault_info *info, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81089170)
Location: arch/x86/mm/mpx.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff81089170-ffffffff8108930d: mpx_fault_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mpx_fault_info(struct mpx_fault_info *info, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108d2a0)
Location: arch/x86/mm/mpx.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8108d2a0-ffffffff8108d445: mpx_fault_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mpx_fault_info(struct mpx_fault_info *info, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108df00)
Location: arch/x86/mm/mpx.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8108df00-ffffffff8108e0a5: mpx_fault_info (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
int mpx_fault_info(struct mpx_fault_info *info, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108cec0)
Location: arch/x86/mm/mpx.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8108cec0-ffffffff8108d065: mpx_fault_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mpx_fault_info(struct mpx_fault_info *info, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107b9f0)
Location: arch/x86/mm/mpx.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8107b9f0-ffffffff8107bb95: mpx_fault_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mpx_fault_info(struct mpx_fault_info *info, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108ce70)
Location: arch/x86/mm/mpx.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8108ce70-ffffffff8108d015: mpx_fault_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mpx_fault_info(struct mpx_fault_info *info, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108f1f0)
Location: arch/x86/mm/mpx.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff8108f1f0-ffffffff8108f3b1: mpx_fault_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
