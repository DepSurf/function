# Function: <code>do_audit_syscall_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void do_audit_syscall_entry(struct pt_regs *regs, u32 arch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003110)
Location: arch/x86/entry/common.c:50
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter_phase1
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
```
**Symbols:**

```
ffffffff81003110-ffffffff8100317a: do_audit_syscall_entry (STB_LOCAL)
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
In arch/x86/entry/common.c (ffffffff810033de)
Location: arch/x86/entry/common.c:52
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff810033ba)
Location: arch/x86/entry/common.c:45
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff8100326e)
Location: arch/x86/entry/common.c:47
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff810031bb)
Location: arch/x86/entry/common.c:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff81003982)
Location: arch/x86/entry/common.c:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff81003e42)
Location: arch/x86/entry/common.c:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff81003c21)
Location: arch/x86/entry/common.c:51
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff81003c21)
Location: arch/x86/entry/common.c:51
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81005456)
Location: arch/x86/entry/common.c:138
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003c21)
Location: arch/x86/entry/common.c:51
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff81002101)
Location: arch/x86/entry/common.c:51
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff81003c21)
Location: arch/x86/entry/common.c:51
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
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
In arch/x86/entry/common.c (ffffffff81003cf1)
Location: arch/x86/entry/common.c:51
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
